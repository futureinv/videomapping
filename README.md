(English version below)

# Videomapping #
Il videomapping è una tecnica che consente di proiettare immagini, animazioni e video su superfici diverse dal classico schermo. Tramite l'utilizzo di un software, infatti, è possibile adattare la proiezione video alla forma e alla dimensione della superficie stessa.

La patch contenuta all'interno del progetto è progettata per rendere accessibile ad un pubblico non esperto la tecnica del videomapping, partendo dal software Isadora - Projection Mapping.
L'estensione è stata sviluppata per il Museo Nazionale della Scienza e della Tecnologia Leonardo da Vinci (MUST).

# Requisiti
  - Programma:
    Isadora - Projection Mapping (Troikatronik offre una versione gratuita del programma, compatibile con l'estensione di GitHub ma che non permette di salvare i contenuti una volta ultimato il lavoro)
  - Sistema operativo:
    - Windows 10
    - Windows 11
    - macOS 10.14 (Mojave)
    - macOS 13 (Ventura)
  - Computer con scheda grafica dedicata
  - Proiettore
  - Webcam

# Installazione

## Isadora - Projection Mapping
Per poter utilizzare l'estensione è necessario scaricare il programma Isadora - Projection Mapping dal [sito ufficiale](https://troikatronix.com/get-it/). Una volta scaricato fare doppio click sul file .exe per installare: per mandare avanti l'installazione è sufficiente cliccare sempre su "Next", nella seconda schermata è necessario selezionare "I accept the terms in the license Agreement". L'installazione può richiedere qualche minuto.

## Estensione
- Scaricare l'estensione dalla pagina GitHub.
- Estrarre i file dalla cartella.
- Aprire con doppio click il file "mappingClient_light_v3_0.izz" per accedere alla versione 3 della patch.

Se dovesse comparire l'avviso "Located Missing Media File" cliccare inizialmente su "skip all file".
Le immagini e i video potranno essere importati in un secondo momento.

## Proiettore
Collegare un proiettore al computer tramite cavo HDMI o USB. Qualsiasi tipo di proiettore è adatto all'attività. È fortemente consigliato l'utilizzo di un cavalletto o di un sistema di stabilizzazione per evitare di compromettere il lavoro del mapping.

## Webcam
Collegare una webcam al computer tramite cavo HDMI o USB. La webcam facilita la creazione di contenuti personalizzati, nel caso in cui non fosse possibile reperirla è possibile utilizzare quella del proprio computer.

# Come usare l'estensione
L'interfaccia della patch presenta diverse aree e funzioni. Realizzare un videomapping prevede due fasi:
1. Mapping: creare una figura geometrica e adattarla alla superficie su cui viene proiettata.
2. Personalizzazione: proiettare delle immagini o dei video all'interno della forma precedentemente creata. È possibile scegliere tra una serie di elementi presenti nell'estensione, crearne di propri contenuti attraverso una webcam oppure caricare immagini o video dal propio computer.
   
<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/Interface.jpg" width="500" />

## MAPPING

### Proiettare una figura 
   Per proiettare una figura sulla parete o sulla superficie desiderata, assicurarsi che il proiettore sia collegato al PC. In seguito dalla barra delle funzioni in alto selezionare "output" →
   "show stages". 

### Selezionare una figura
Nell'area in alto a sinistra dell'interfaccia è presente una lista di figure. Premendo uno dei pulsanti "Shape01 ... Shape12" è possibile selezionare una forma da modificare. Sulla loro destra è anche presente un pulsante "on/off" per visualizzare o nascondere le singole figure. Il pulsante "set" sulla sinistra invece consente di raggruppare tre figure; in questo modo quando vengono aggiunti dei contenuti tutte le tre figure del set avranno lo stesso contenuto della prima forma del trio. 

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/ShapeList.jpg" width="100" />

### Modificare la figura selezionata 
In questa parte dell'interfaccia è possibile modificare la forma della figura selezionata. Una volta selezionata una forma tramite il pulsante "Shape01 ... Shape12" , è possibile spostare la forma
utilizzando il cursore del rettangolo grigio oppure spostare i singoli vertici con i cursori dei quadrati rossi. Nel menù a tendina in alto a sinistra è possibile anche cambiare il tipo di figura (quadrato,cerchio o triangolo). Infine è possibile cambiare la tinta della figura tramite il pannello rettangolare dei colori.

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/SelectShape.jpg" width="300" />

## PERSONALIZZAZIONE

### Importare immagini e video predefiniti
Assieme alla patch sono stati messi a disposizione delle immagini, dei video e delle maschere.
Se i file non compaiono in basso nelle sezioni "Pictures" e "Video Files", basterà importarli nell'estensione manualmente.
Per farlo dalla barra delle funzioni selezionare l'opzione "File" →"Import Media". Tenendo premuto il tassto SHIFT, selezionare tutti i video nella cartella "Videos" e cliccare su "importa".
Ripetere lo stesso procedimento per importare le immagini e le maschere.

### Proiettare immagini e videdo
Per sostituire la tinta unita della figura con delle immagini o dei video bisogna cliccare sul pulsante blu "show solid color" sotto il pannello dei colori.
A questo punto è possibile scegliere una serie di contenuti (immagini o video) tra quelli presenti in basso nelle sezioni "Pictures" e "Video Files".

### Aggiungere gli effetti
È possibile capovolgere il contenuto della forma orizzontale o verticale. Inoltre è possibile applicare alle immagini e ai video degli effetti. Per attivare o disattivare l'effetto è sufficiente cliccare sul pulsante con il suo nome nel pannello "Video Effects"; tramite lo slider è anche possibile modificarne l'intensità.

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/Effect.jpg" width="200" />

### Aggiungere le maschere
Le maschere, contenute nella sezione "Masks", sono dei filtri che è possibile aggiungere ai video e alle immagini statiche. Per poterli applicare è necessario cliccare sul pulsante "Enable Alfa Mask" e selezionare il filtro desiderato.

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/Mask.jpg" width="400" />

### La modalità "Animate"
Se il contenuto  scelto è un'immagine, si può usare il pulsante "Animate" per mettere in movimento la foto scegliendo la velocità e l'offset.

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/AnimatePicture.jpg" width="100" />

### La modalità "Sequence"
Quando si lavora con le diverse forme si ha la possibilità di impostare una sequenza di contenuti da riprodurre in sequenza automaticamente. Per farlo bisogna abbinare a ciascuno "step" della sequenza un'immagine o un video. Tramite il menù a tendina è possibile selezionare lo "step01...step08" e poi scegliere il video o l'immagine da riprodurre in quello step. Tramite la rotella "time image" si può regolare il tempo di visualizzazione in secondi dell'immagine. Il passagio può essere ripetuto fino a un numero massimo di 8 volte. Premendo poi sul tasto "on/off" si avvia la riproduzione della sequenza. Con il pulsante "loop" è possibile attivare/disattivare il loop della sequenza. Quando la sequenza non è attiva, si possono usare i pulsanti + e - per scorrere e visualizzare i singoli step. 

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/Sequence.jpg" width="500" />

### Creare contenuti con la webcam
La modalità "Live Video" permette di registrare dei propri contenuti video. Premendo su "turn on webcam" il programam attiva la webcam selezionata. Se non compare nessuna immagine assicurarsi di aver collegato correttamente la webcam: dalla barra delle applicazioni in alto andare su o "Input"→ "Live Capture Settings" e selezionare la webcam corretta.
Per iniziare la registrazione è sufficiente cliccare sul pulsante "Record", per terminarla cliccare nuovamente sul pulsante. 
Tramite una serie di comandi è possibile modificare il video prima o durante la registrazione. Si può:
- capovolgere l'immagine video in diretta in orizzontale o in verticale.
- usare  il pulsante "Invert video" per invertire il colore del video.
- utilizzare i cursori di contrasto per modificare la luminosità/il contrasto del video.
- utilizzare i cursori zoom e pan per ritagliare  le immagini della webcam.
Il video verrà salvato in fondo alla sezione "Video Files".

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/Webcam.jpg" width="200" />

### Caricare immagini e video
Isadora permette di caricare ed utilizzare i propri contenuti (video e immagini); tuttavia se l'estenione viene usata partendo dalla versione gratuita di Isadora non è possibile salvare le modifiche e i file importati nel progetto.
Per importare un file selezionare alla voce " View" → "Media+Information". Dal pannello dei media a questo punto selezionare "File"→ "Import Media". Fare attenzione ed importare le immagini nella cartella "Pictures", i video nella sezione "Video Files" e le maschere nella raccolta "MASKS".

### Requisiti delle immagini
Per importare correttamente le immagini bisogna assicurarsi che queste abbiano i giusti requisiti  
- formati compatibili:  .png .jpg .gif .tiff and .bmp
- dimensione massima: 1920×1080 pixels (HD resolution)
Si consiglia di importare immagini con una dimensione massima di 960×540 e con una risoluzione di 72dpi.

### Requisiti dei video
Per importare correttamente le immagini bisogna assicurarsi che queste abbiano i giusti requisiti. 
Si consiglia di importare video con una dimensione massima di 960×540.

Video Codecs
- HAP (.mov and .avi)
- HAPQ (.mov and .avi)
- HAPA (.mov and .avi)
- Photo JPEG (.mov and .avi)
- Apple ProRes (.mov) — Mac OS only
- Windows Media (.wmv) — Windows only
- H264 (.mp4, .mov, and .wmv) — non supporta l'interactive playback modes


## MALFUNZIOMENTI
Per ogni errore o malfunzionamento durante l'utilizzo si invita a consultare il [manuale di istruzioniufficiale](https://troikatronix.com/files/isadora-manual.pdf) di Isadora - Video Mapping.
Di seguito sono riportati gli errori più comuni durante l'utilizzo della patch.

### Le figure non vengono proiettate correttamente
Nel caso in cui dal proiettore non dovessero comparire le figure o le immagini dell'estensione:
- assicurarsi che il proiettore sia collegato correttamente al computer
- dalla barra delle funzioni in alto selezionare "output" → "hide stages" e successivamente "output" → "show stages"

### I comandi dell'estensione non sono visibili
Se i comandi dell'estensione non fossero più visibili. Cliccare con il tasto destro del mouse in un punto qualsiasi dell'area di lavoro → selezionare "Show Controls"

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/ShowControls.jpg" width="400" />

### La webcam non funziona
Nel caso in cui il contenuto della webcam non fosse visibile:
- assicurarsi che la webcam sia collegata correttamente al computer
- selezionare la webcam dal menù delle impostazioni presente in "Input" → "Live Capture Settings"

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/WebcamSettings.jpg" width="400" />

# English version
# Videomapping #
Videomapping is a technique for projecting images, animations and videos onto surfaces other than the classic screen. Through the use of software, in fact, it is possible to adapt the video projection to the shape and size of the surface itself

The patch contained within the project is designed to make the technique of videomapping accessible to a non-expert audience, starting with the software Isadora - Projection Mapping.
The extension was developed for the Leonardo da Vinci National Museum of Science and Technology (MUST).

# Requirements.
- Program:
Isadora - Projection Mapping (Troikatronik offers a free version of the program, which is compatible with the GitHub extension but does not allow you to save content once the work is completed)
- Operating system:
- Windows 10
- Windows 11
- macOS 10.14 (Mojave)
- macOS 13 (Ventura)
- Computer with dedicated graphics card
- Projector
- Webcam

# Installation
## Isadora - Projection Mapping.
In order to use the extension you need to download the Isadora - Projection Mapping program from the [official site](https://troikatronix.com/get-it/). Once downloaded double click on the .exe file to install: to send the installation forward you just need to always click on “Next”, on the second screen you need to select “I accept the terms in the license Agreement”. The installation may take a few minutes.

## Extension
- Download the extension from the GitHub page.
- Extract the files from the folder.
- Double-click open the file “mappingClient_light_v3_0.izz” to access version 3 of the patch.

Should the warning “Located Missing Media File” appear, initially click on “skip all files.”
Images and videos can be imported at a later time.

## Projector
Connect a projector to the computer via HDMI or USB cable. Any type of projector is suitable for the activity. The use of a tripod or stabilization system is strongly recommended to avoid compromising the mapping work.

## Webcam
Connect a webcam to your computer via HDMI or USB cable. The webcam facilitates the creation of custom content, in case you cannot find it you can use the one on your computer.

## How to use the extension.
The patch interface has several areas and functions. Making a videomapping involves two steps:
1. Mapping: create a geometric figure and adapt it to the surface on which it is projected.
2. Customization: projecting images or videos within the previously created shape. You can choose from a range of elements in the extension, create your own content through a webcam, or upload images or videos from your own computer.

<img src=“https://github.com/futureinv/videomapping/blob/main/readmeImages/Interface.jpg” width=“500” />

# How to use the extension.
The patch interface has several areas and functions. Making a videomapping involves two steps:
1. Mapping: creating a geometric figure and adapting it to the surface on which it is projected.
2. Customization: projecting images or videos within the previously created shape. You can choose from a range of elements in the extension, create your own content through a webcam, or upload images or videos from your own computer.

<img src=“https://github.com/futureinv/videomapping/blob/main/readmeImages/Interface.jpg” width=“500” />

## MAPPING.

### Projecting a figure. 
To project a figure on the desired wall or surface, make sure the projector is connected to the PC. Then from the top function bar, select “output” →
“show stages.” 

### Select a figure.
In the upper left area of the interface is a list of figures. By pressing one of the buttons “Shape01 ... Shape12” you can select a shape to edit. On their right side there is also an “on/off” button to show or hide individual figures. The “set” button on the left, on the other hand, allows three figures to be grouped together; thus when content is added all three figures in the set will have the same content as the first shape in the trio. 

<img src=“https://github.com/futureinv/videomapping/blob/main/readmeImages/ShapeList.jpg” width=“100” />

## CUSTOMIZATION

### Importing default images and videos.
Along with the patch, pictures, videos and masks have been made available.
If the files do not appear at the bottom in the “Pictures” and “Video Files” sections, simply import them into the extension manually.
To do this from the function bar select the option “File” →“Import Media”. While holding down the SHIFT tassto select all the videos in the “Videos” folder and click on “import.”
Repeat the same process to import images and masks.

### Projecting images and videdos.
To replace the solid color of the figure with images or videos you need to click on the blue “show solid color” button under the color panel.
Then you can choose a range of content (pictures or videos) from those below in the “Pictures” and “Video Files” sections.

### Add effects.
You can flip the content of the horizontal or vertical shape. You can also apply effects to pictures and videos. To turn the effect on or off, simply click on the button with its name in the “Video Effects” panel; via the slider you can also change its intensity.

<img src=“https://github.com/futureinv/videomapping/blob/main/readmeImages/Effect.jpg” width=“200” />

### Adding Masks.
Masks, contained in the “Masks” section, are filters that you can add to videos and static images. In order to apply them, you must click on the “Enable Alpha Mask” button and select the desired filter.

<img src=“https://github.com/futureinv/videomapping/blob/main/readmeImages/Mask.jpg” width=“400” />

### The “Animate” mode.
If the chosen content is a picture, you can use the “Animate” button to set the picture in motion by choosing the speed and offset.

<img src=“https://github.com/futureinv/videomapping/blob/main/readmeImages/AnimatePicture.jpg” width=“100” />

<img src=“https://github.com/futureinv/videomapping/blob/main/readmeImages/Sequence.jpg” width=“500” />

### Create content with the webcam.
The “Live Video” mode allows you to record your own video content. By pressing on “turn on webcam” the programam activates the selected webcam. If no image appears make sure you have connected the webcam correctly: from the top taskbar go to or “Input”→ “Live Capture Settings” and select the correct webcam.
To start recording simply click on the “Record” button, to end it click on the button again. 
Through a series of commands you can edit the video before or during recording. One can:
- flip the live video image horizontally or vertically.
- use the “Invert video” button to invert the color of the video.
- use the contrast sliders to change the brightness/contrast of the video.
- use the zoom and pan sliders to crop the webcam images.
The video will be saved at the bottom of the “Video Files” section.

<img src=“https://github.com/futureinv/videomapping/blob/main/readmeImages/Webcam.jpg” width=“200” />

### The “Sequence” mode.
When working with the different shapes you have the option of setting up a sequence of content to play in sequence automatically. To do this you must match each “step” in the sequence with an image or video. Through the drop-down menu you can select “step01...step08” and then choose the video or image to be played in that step. Using the “time image” wheel, the display time in seconds of the image can be adjusted. The step can be repeated up to a maximum number of 8 times. Then pressing on the “on/off” button starts playback of the sequence. With the “loop” button you can turn the sequence loop on/off. When the sequence is not active, you can use the + and - buttons to scroll and view the individual steps.

### Uploading images and videos
Isadora allows you to upload and use your own content (videos and images); however, if the extension is used starting from the free version of Isadora you cannot save the changes and imported files in the project.
To import a file select under “ View” → “Media+Information”. From the media panel at this point select “File”→ “Import Media”. Be careful and import pictures in the “Pictures” folder, videos in the “Video Files” section, and masks in the “MASKS” collection.

### Picture Requirements.
To import images correctly, you must make sure that they have the right requirements 
- compatible formats: .png .jpg .gif .tiff and .bmp
- maximum size: 1920×1080 pixels (HD resolution)
We recommend importing images with a maximum size of 960×540 and a resolution of 72dpi.

### Video requirements.
In order to import images correctly, you need to make sure that they have the right requirements. 
We recommend importing videos with a maximum size of 960×540.

Video Codecs
- HAP (.mov and .avi)
- HAPQ (.mov and .avi)
- HAPA (.mov and .avi)
- Photo JPEG (.mov and .avi)
- Apple ProRes (.mov) - Mac OS only
- Windows Media (.wmv) - Windows only
- H264 (.mp4, .mov, and .wmv) - does not support interactive playback modes

## MALFUNCTIONS
Please refer to the [Official Instruction Manual](https://troikatronix.com/files/isadora-manual.pdf) of Isadora - Video Mapping for any errors or malfunctions during use.
The following are the most common errors while using the patch.

### Figures are not projected correctly.
In case figures or extension images do not appear from the projector:
- make sure the projector is properly connected to the computer
- from the top function bar select “output” → “hide stages” and then “output” → “show stages”

### The extension commands are not visible.
If the extension commands were no longer visible. Right-click anywhere in the workspace → select “Show Controls”

<img src=“https://github.com/futureinv/videomapping/blob/main/readmeImages/ShowControls.jpg” width=“400” />

### The webcam is not working
In case the webcam content was not visible:
- make sure the webcam is properly connected to the computer
- select the webcam from the settings menu present in “Input” → “Live Capture Settings”

<img src=“https://github.com/futureinv/videomapping/blob/main/readmeImages/WebcamSettings.jpg” width=“400” />
