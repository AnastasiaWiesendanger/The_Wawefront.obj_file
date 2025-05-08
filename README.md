SUPSI 2025  
Corso d’interaction design, CV429 
Docenti: A. Gysin, G. Profeta  uuu

Elaborato 1: Me, Myself & AI  

# Wawefront Obj File
Autore: Anastasia Wiesendanger 
[Wawefront Obj File](https://anastasiawiesendanger.github.io/The_Wawefront.obj_file/)


## Introduzione e tema
Per questo lavoro, tutti gli studenti che frequentano il corso di "Interaction Design" e che appartengono al corso di laurea del Bachelor in Comunicazione visiva, hanno dovuto realizzare un sito internet che descrivesse un "oggetto" digitale specifivo. Nel mio caso l'bj file, più specifico "Wawefront obj file". Il modo in cui dovevamo rappresentare il sito, era alquanto libero. Avevamo pochi punti principali da rispettare, ovverro: il sito deve rappresentare un singolo articolo riguardo l'argomento che ci è stato assegnato, all'interno di una singola pagina e con presententi alcune animazioni interattive


## Riferimenti progettuali
Dolor sit amet consectetur adipiscing elit duis tristique. Sociis natoque penatibus et magnis dis parturient montes nascetur. Est sit amet facilisis magna. Tellus rutrum tellus pellentesque eu. Dictum sit amet justo donec enim. Aliquam malesuada bibendum arcu vitae elementum curabitur vitae. Sed faucibus turpis in eu mi bibendum neque egestas congue. Tellus in metus vulputate eu scelerisque felis imperdiet proin. Dolor magna eget est lorem ipsum dolor. Sit amet mattis vulputate enim nulla. Elit pellentesque habitant morbi tristique senectus et. Vestibulum mattis ullamcorper velit sed ullamcorper morbi tincidunt ornare massa.




https://github.com/user-attachments/assets/3ca10ae4-5bdb-4daa-bd36-88e29415e1f0




## Design dell’interfraccia e modalià di interazione
L'interfaccia in se è stata elaborata affinché tu possa trovare tutto (sia informazioni che le animazioni) all'interno di una singola pagina. Lo sfondo nero è stato scelto affinché il modello 3D possa risultare più evidente sul background, stesa cosa vale per il testo. l'oggetto tridimensionale inoltre lo puoi muovere all'interno dello spazio semplicemente cliccandolo. Lo si può ruotare a 360 gradi ed ingrandire e rimpicciole. Per far si che tu possa giocarci come vuoi, l'oggetto lo si può vedere anche sotto il testo, oppure puoi semplicemnte nascondere la parte scritta tramite l'iconcina in alto a sinistra.

[<img src="doc/cards.gif" width="500" alt="Magic trick">]()


## Tecnologia usata
Per questo lavoro, non essendo esperta in codice, specialmente per quanto riguarda la creazione di animazioni interattive, mi sono fatta aiutare da Chat GPT (e un pochino da BLACKBOX.AI). Mentre un sito che è stato di grande aiuto per la creazione dei file obj e mtl è stata la libreria del congresso, ovvero "Library of congress". Oltre che ad esserci una spiegazione dettaglia riguardo l'Obj file ci sono anche presenti dei codici d'esempio al riguardo che ho utilizzato per la creazione di alcune cose presenti nell'articolo:


```g Object001

v -1.000000 1.000000 1.000000
v -1.000000 -1.000000 1.000000
v 1.000000 -1.000000 1.000000
v 1.000000 1.000000 1.000000
v -1.000000 1.000000 -1.000000
v -1.000000 -1.000000 -1.000000
v 1.000000 -1.000000 -1.000000
v 1.000000 1.000000 -1.000000

f 1 2 3 4
f 8 7 6 5
f 4 3 7 8
f 5 1 4 8
f 5 6 2 1
f 2 6 7 3
```

Questo codice rappreseta un modello 3D, più precisamente un cubo

```mtl file
newmtl shinyred
Ka  0.1985  0.0000  0.0000
Kd  0.5921  0.0167  0.0000
Ks  0.5973  0.2083  0.2083
illum 2
Ns 100.2235
```

Questo invece è il codice presente all'interno di un file mtl e con esso si dovrebbe visualizzare una superficie di tipo metallica

## Target e contesto d’uso
Questo articolo è stato principalmente crearto con l'intenzione di essere mostrato/visto agli studenti che frequentano il Bachelor di Comunicazione Visiva, più specificamente per chi frequenta o vorrà frequentare la classe di Interaction Design. L'articolo in sè ha lo scopo principale di essere una fonte di informazione, di incuriosire, oltre che ha mostrare le varie interazioni che si possono creare al'interno di un file html tramite il codice ed invogliare la gente a restare un po' più a lungo sulla pagina. 

[<img src="doc/munari.jpg" width="300" alt="Supplemento al dizionario italiano">]()
