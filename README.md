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

Se dovesse comparire l'avviso "Located Missing Media File" cliccare inizialmente su "skip all file"
Le immagini e i video potranno essere importati in un secondo momento.

## Proiettore
Collegare un proiettore al computer tramite cavo HDMI o USB. Qualsiasi tipo di proiettore è adatto all'attività. È fortemente consigliato l'utilizzo di un cavalletto o di un sistema di stabilizzazione per evitare di compromettere il lavoro del mapping.

## Webcam
Collegare una webcam al computer tramite cavo HDMI o USB. La webcam facilita la creazione di contenuti personalizzati, in caso non fosse possibile reperirla è possibile utilizzare quella del porprio computer.

# Come usare l'estensione
L'interfaccia della patch presenta diversa aree e funzioni. Realizzare un videomapping prevede due fasi:
1. Mapping: creare una figura geometrica e adattarla alla superficie su cui viene proiettata.
2. Personalizzazione: proiettare delle immagini o dei video all'interno della forma precedentemente creata. È possibile scegliere tra una serie di elementi presenti nell'estensione, crearne di propri contenuti attraverso una webcam oppure caricare immagini o video dal prorpio computer.
   
<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/Interface.jpg" width="500" />

## MAPPING

### proiettare una figura 
   Per proiettare una figura sulla parete o sulla superficie desiderata, assicurarsi che il proiettore sia collegato al PC. In seguito dalla barra delle funzioni in alto selezionare "output" →
   "show stages". 

###  selezionare una figura
Nell'area in alto a sinistra dell'interfaccia è presente una lista di figure. Premendo uno dei pulsanti "Shape01 ... Shape12" è possibile selezionare una forma da modificare.Sulla loro destra è anche presente un pulsante "on/off" per visualizzare o nascondere le singole figure. Il pulsante "set" sulla sinsitra invece consente di raggruppare tre figure; in questo modo quando vengono aggiunti dei contenuti tutte le tre figure del set avranno lo stesso contenuto della prima forma del trio. 

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/ShapeList.jpg" width="100" />

###  modificare la figura selezionata 
In questa parte dell'interfaccia è possibile modificare la forma della figura selezionata. Una volta selezionata una forma tramite il pulsante "Shape01 ... Shape12" , è possibile spostare la forma
utilizzando il cursore del rettangolo grigio oppure spostare i singoli vertici con i cursore dei quadrati rossi. Nel menù a tendina in alto a sinistra è possibile anche cambiare il tipo di figura (quadrato,cerchio o triangolo). Infine è possibile cambiare la tinta della figura tramite il pannello rettangolare dei colori.

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/SelectShape.jpg" width="300" />

## PERSONALIZZAZIONE

### importare immagini e video predefiniti
Assieme alla patch sono stati messi a disposizione delle immagini, dei video e delle maschere.
Se i file non compaiono in basso nelle sezioni "Pictures" e "Video Files", basterà importarli nell'estensione manualmente.
Per farlo dalla barra delle funzioni selezionare l'opzione "File" →"Import Media". Tenendo premuto il tassto SHIFT, selezionare tutti i video nella cartella "Videos" e claccare su "importa".
Ripetere lo stesso procedimento per importare le immagini e le maschere.

### proiettare immagini e videdo
Per sostituire la tinta unita della figra con delle immagini o dei video bisogna cliccare sul pulsante blu "show solid color" sotto il pannello dei colori.
A questo punto è possibile scegliere una serie di contenuti (immagini o video) tra quelli presenti in basso nelle sezioni "Pictures" e "Video Files".

### aggiungere gli effetti
È possibile capovolgere il contenuto della forma orizzontale o verticale. Inoltre è possibile applicare alle immagini e ai video degli effetti. Per attivare o disattivare l'effetto è sufficiente cliccare sul pulsante con il suo nome nel pannello "Video Effects"; tramite lo slider è anche possibile modificarne l'intensità.

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/Effect.jpg" width="200" />

### aggiungere le maschere
Le maschere, contenute nella sezione "Masks", sono dei filtri che è possibile aggiungere ai video e alle immaginis statiche. Per poterli applicare è necessario cliccare sul pulsante "Enable Alfa Mask" e selezionare il filtro desiderato.

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/Mask.jpg" width="400" />

### la modalità "Animate"
Se il contenuto  scelto è un'immagine, si può usare il pulsante "Animate" per mettere in movimento la foto scegliendo la velocità e l'offset.

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/AnimatePicture.jpg" width="100" />

### la modalità "Sequence"
Quando si lavora con le diverse forme si ha la possibilità di impostare una sequenza di contenuti da riprodurre in sequenza automaticamente. Per farlo  bisogna abbinare a ciascuno "step" della sequenza un'immagine o un video. Tramite il menù a tendina è possibile selezionare lo "step01...step08" e poi scegliere il video o l'immagine da riprodurre in quello step. Tramite la rotella "time image" si può regolare il tempo di visualizzazione in secondi dell'immagine. Il passagio può essere ripetuto fino a un numero massimo di 8 volte. Premendo poi sul tasto "on/off" si avvia la riproduzione della sequenza. Con il pulsante "loop" è possibile attivare/disattivare il loop della sequenza. Quando la sequenza non è attiva, si possono usare i pulsanti + e - per scorrere e visualizzare i singoli step. 

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/Sequence.jpg" width="500" />

### creare contenuti con la webcam
La modalità "Live Video" permette di registrare dei propri contenuti video. Premendo su "turn on webcam" il programam attiva la webcam selezionata. Se non compare nessuna immagine assicurarsi di aver collegato correttamente la webcam: dalla barra delle applicazioni in alto andare su o "Input"→ "Live Capture Settings" e selezionare la webcam corretta.
Per iniziare la registrazione è sufficiente cliccare sul pulsante "Record", per termirla cliccare nuovamente sul pulsante. 
Tramite una serie di comandi è possibile modificare il video prima o durante la registrazione. Si può:
- capovolgere l'immagine video in diretta in orizzontale o in verticale
- usare  il pulsante "Invert video" per invertire il colore del video.
- utilizzare i cursori di contrasto per modificare la luminosità/il contrasto del video.
- utilizzare i cursori zoom e pan per ritagliare  le immagini della webcam.
Il video verrà salvato in fondo alla sezione "Video Files".

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/Webcam.jpg" width="200" />

### caricare immagini e video
Isadora permette di caricare ed utilizzare i propri contenuti (video e immagini); tuttavia se l'estenione viene usata partendo dalla versione gratuita di Isadora non è possibile salvare le modifiche e i file importati nel progetto.
Per importare un file selezionare alla voce " View"→ "Media+Information". Dal pannello dei media a questo punto selezionare "File"→ "Import Media". Fare attenzione ed importare le immagini nella cartella "Pictures", i video nella sezione "Video Files" e le maschere nella raccolta "MASKS".

### requisiti delle immagini

Per importare correttamente le immagini bisogna assicurarsi che queste abbiamo i giusti requisiti  
- formati compatibili:  .png .jpg .gif .tiff and .bmp
- dimensione massima: 1920×1080 pixels (HD resolution)
Si consiglia di importare imamgini con una dimensione massima di 960×540 e con una risoluzione di 72dpi.

### requisiti dei video
Per importare correttamente le immagini bisogna assicurarsi che queste abbiamo i giusti requisiti  
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

### le figure non vengono proiettate correttamente
Nel caso in cui dal proiettore non dovessero comparire le figure o le immagini dell'estensione:
- assicurarsi che il poriettoer sia colelgato correttamente al computer
- dalla barra delle funzioni in alto selezionare "output" → "hide stages" e successivamente "output" → "show stages"

### i comandi dell'estensione non sono visibili
Se i comandi dell'estensionsione non fossero pi+ visibili. Cliccare  con il tasto destro del mouse in un punto qualsiasi dell'area di lavoro → selezionare "show controls"

<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/ShowControls.jpg" width="400" />

### la webcam non funziona
Nel caso in cui il contenuto della webcam non fosse visibile:
- assicurarsi che la webcam sia colelgata correttamente al computer
- selezionare la webcam dal menù delle impostazioni presente in "Input" → "Live Capture settings"
- 
<img src="https://github.com/futureinv/videomapping/blob/main/readmeImages/WebcamSettings.jpg" width="400" />



