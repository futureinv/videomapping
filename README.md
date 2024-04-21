# Videomapping #
Il videomapping è una tecnica che consente di proiettare immagini, animazioni e video su superfici diverse dal classico schermo. Tramite l'utilizzo di un software, infatti, è possibile adattare la proiezione video alla forma e alla dimensione della superficie stessa.

La patch contenuta all'interno del progetto è progettata per rendere accessibile ad un pubblico non esperto la tecnica del videomapping, partendo dal software Isadora - Projection Mapping.
L'estensione è stata sviluppata per il Museo Nazionale della Scienza e della Tecnologia Leonardo da Vinci (MUST).

# Requisiti
  - Programma:
    Isadora 3 
  - Sistema operativo:
    - Windows 10
    - Windows 11
    - macOS 10.14 (Mojave)
    - macOS 13 (Ventura)
  - Computer con scheda grafica dedicata
  - Proiettore
  - Webcam

# Installazione

## Isadora
Per poter utilizzare l'estenzione è necessario scaricare il programma Isadora - Projection Mappingdal [sito ufficiale](https://troikatronix.com/get-it/). Una volta scaricato fare doppio click sul file .exe per installare: per mandare avanti l'installazione è sufficiente cliccare sempre su Next, nella seconda schermata è necessario selezionare "I accept the terms in the license Agreement". L'installazione può richiedere qualche minuto.

## Estensione
- Scaricare l'estensione dalla pagina Github.
- Estrarre i file dalla cartella.
- Aprire con doppio click il file "mappingClient_light_v3_0.izz" per accedere alla versione 3 della patch.

## Proiettore
Collegare un proiettore al PC tramite cavo HDMI o USB. Qualsiasi tipo di proiettore è adatto all'attività. È fortemente consigliato l'utilizzo di un cavalletto o di un sistema di stabilizzazione per evitare di compromettere il lavoro del mapping.

## Webcam
Collegare una webcam al PC tramite cavo HDMI o USB. La webcam facilita la creazione di contenuti presonalizzati, in caso non fosse possibile reperirla è possibile utilizzare quella del porprio computer.

# Come usare l'estensione
L'interfaccia della patch presenta diversa aree e funzioni. Realizzare un videomapping prevede due fasi:
1. Mapping: creare una figura geometrica e adattarla alla superficie su cui viene proiettata.
2. Personalizzazione: proiettare delle immagini o dei video all'interno della forma precedentemente creata. È possibile scegliere tra una serie di elementi presenti nell'estensione, crearne di propri contenuti attraverso una webcam oppure caricare immagini o video dal prorpio pc.
   

## MAPPING

### proiettare una figura 
   Per proiettare una figura sulla parete o sulla superficie desiderata, assicurarsi che il proiettore sia collegato al PC. In seguito dalla barra delle funzioni in alto selezionare "output" >
   "show stages". 
###  selezionare una figura
Nell'area in alto a sinistra dell'interfaccia è presente una lista di figure. Premendo uno dei pulsanti "Shape01 ... Shape12" è possibile selezionare una forma da modificare.Sulla loro destra è anche presente un pulsante "on/off" per visualizzare o nascondere le singole figure. Il pulsante "set" sulla sinsitra invece consente di raggruppare tre figure; in questo modo quando vengono aggiunti dei contenuti tutte le tre figure del set avranno lo stesso contenuto della prima forma del trio. 
###  modificare la figura selezionata 
In questa parte dell'interfaccia è possibile modificare la forma della figura selezionata. Una volta selezionata una forma tramite il pulsante "Shape01 ... Shape12" , è possibile spostare la forma
utilizzando il cursore del rettangolo grigio oppure spostare i singoli vertici con i cursore dei quadrati rossi. Nel menù a tendina in alto a sinistra è possibile anche cambiare il tipo di figura (quadrato,cerchio o triangolo). Infine è possibile cambiare la tinta della figura tramite il pannello rettangolare dei colori.

## PERSONALIZZAZIONE

### aggiungere immagini e video
Per sostituire la tinta unita della figra con delle immagini o dei video bisogna cliccare sul pulsante blu "show solid color" sotto il pannello dei colori.
A questo punto è possibile scegliere una serie di contenuti (immagini o video) tra quelli presenti in basso nella sezioni "Pictures" e "Video Files".
### aggiungere gli effetti
È possibile capovolgere il contenuto della forma orizzontale o verticale. Inoltre è possibile applicare alle immagini e ai video degli effetti. Per attivare o disattivare l'effetto è sufficiente cliccare sul pulsante con il suo nome nel pannello "Video Effects"; tramite lo slider è anche possibile modificarne l'intensità.
### aggiungere le maschere
Le maschere, contenute nella sezione "Masks", sono dei filtri che è possibile aggiungere ai video e alle immaginis statiche. Per poterli applicare è necessario cliccare sul pulsante "Enable Alfa Mask" e selezionare il filtro desiderato.
### la modalità "Animate"
Se il contenuto  scelto è un'immagine, si può usare il pulsante "Animate" per mettere in movimento la foto scegliendo la velocità e l'offset.
### la modalità "Sequence"
Quando si lavora con le diverse forme si ha la possibilità di impostare una sequenza di contenuti da riprodurre in sequenza automaticamente. Per farlo  bisogna abbinare a ciascuno "step" della sequenza un'immagine o un video. Tramite il menù a tendina è possibile selezionare lo "step01...step08" e poi scegliere il video o l'immagine da riprodurre in quello step. Tramite la rotella "time image" si può regolare il tempo di visualizzazione in secondi dell'immagine. Il passagio può essere ripetuto fino a un numero massimo di 8 volte. Premendo poi sul tasto "on/off" si avvia la riproduzione della sequenza. Con il pulsante "loop" è possibile attivare/disattivare il loop della sequenza. Quando la sequenza non è attiva, si possono usare i pulsanti + e - per scorrere e visualizzare i singoli step. 
### creare contenuti con la webcam
La modalità "Live Video" permette di registrare dei propri contenuti video. Premendo su "turn on webcam" il programam attiva la webcam selezionata. Se non compare nessuna immagine assicurarsi di aver collegato correttamente la webcam: dalla barra delle applicazioni in alto andare su o "Input"→ "Live Capture Settings" e selezionare la webcam corretta.
Per iniziare la registrazione è sufficiente cliccare sul pulsante "Record", per termirla cliccare nuovamente sul pulsante. 
Tramite una serie di comandi è possibile modificare il video prima o durante la registrazione. Si può:
- capovolgere l'immagine video in diretta in orizzontale o in verticale
- usare  il pulsante "Invert video" per invertire il colore del video.
- utilizzare i cursori di contrasto per modificare la luminosità/il contrasto del video.
- utilizzare i cursori zoom e pan per ritagliare  le immagini della webcam.
Il video verrà salvato in fondo alla sezione "Video Files".



<!--
### caricare immagini e video

## errori nell'utilizzo
manueale: (https://troikatronix.com/files/isadora-manual.pdf)
   - se scompare la patch 
   - webcam non funziona
-->  
