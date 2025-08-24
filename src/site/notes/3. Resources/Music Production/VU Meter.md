---
{"dg-publish":true,"permalink":"/3-resources/music-production/vu-meter/"}
---

Links:: [[3. Resources/Music Production/Mixing & Mastering/Analyzer Plugin for Mixing and Mastering\|Analyzer Plugin for Mixing and Mastering]], [[3. Resources/Music Production/Unità di misura\|Unità di misura]]

---
![image_1630096291908_0.png](/img/user/3.%20Resources/Attachments/image_1630096291908_0.png)

## Cos'è

==Il VU meter è uno strumento di misura dell'intensità del segnale negli apparecchi audio.== Esso mostra il valore in Volume Units.
La bassa velocità di risposta è tale da permettere di valutare la risposta dell'intensità del suono degli altoparlanti. — [Wikipedia](https://it.wikipedia.org/wiki/VU_meter)_

Il VU, o Volume Unit, è uno strumento di misurazione del livello audio utilizzato per rappresentare in modo visivo l'intensità del suono su un display analogico. Misura in modo simile al dBVU, ma con una risposta più lenta che riflette meglio il modo in cui l'orecchio umano percepisce il volume. È spesso utilizzato nei mixer e nei dispositivi di registrazione analogici per monitorare e regolare i livelli audio in modo più naturale.

## Descrizione

È stato originalmente sviluppato nel 1939 dagli sforzi combinati dei laboratori Bell e dalle emittenti CBS e NBC per misurare e standardizzare i livelli delle linee telefoniche.
La scala tipica VU è da -20 a +3 decibel in scala logaritmica. I tempi di salita e di discesa sono entrambi di 300 millisecondi. Ciò significa che se viene applicata una onda sinusoidale di 0 VU, lo strumento impiegherà 300 millisecondi per raggiungere lo 0 nella scala. Esso quindi si comporta come uno strumento di misura media dell'onda intera e pertanto non è ottimale per misurare i livelli di picco.
In genere negli amplificatori audio e nei registratori a nastro magnetico il valore 0 è il massimo livello d'intensità che è possibile riprodurre senza che l'apparato introduca distorsione. _fonte: [VU meter - Wikipedia](https://it.wikipedia.org/wiki/VU_meter)_

## Approfondimento

Il problema principale di questi sistemi è la corretta rappresentazione della dinamica in quanto sono costruiti con una massa meccanica composta da un ago che indica al tecnico il valore attuale dei dB inserito in una bobina mobile che a seconda della tensione circolante ha il compito di spostare l’ago indicatore.

Tutta questa massa ha un suo peso ed inerzia allo spostamento, le quali prestazioni calano durante il processo di invecchiamento oltre che all’insorgere di fenomeni come l’ossidazione dei componenti. Tutto questo non rende il sistema veloce ed efficace per l’utilizzo nella visualizzazione dei picchi di segnale che hanno la caratteristica di essere molto rapidi ( pochi millisecondi ), per questo il VU Meter veniva utilizzato molto spesso per visualizzare il valore medio del segnale, di fatti venivano spesso chiamati anche **RMS Meter**.

Lo strumento è stato originariamente costruito per rappresentare oltre che il valore della tensione ( molto spesso realizzato per la rilevazione del segnale RMS ) anche la sensibilità dell’orecchio con l’obbiettivo di muovere l’ago indicatore tale e quale alla risposta percettiva dell’orecchio, secondo dati scientifici di psicoacustica conosciuti all’epoca. Il perchè di questo è legato al semplice fatto per cui una volta non esistevano come ad oggi grafici RTA ed all’Impulso ed il VU Meter era l’unica soluzione per poter vedere la dinamica del segnale potendo cosi tarare al meglio processori outboard come compressori, expander e gate.

Il problema principale era riuscire a creare un circuito che potesse essere adatto e sensibile a trasmettere correttamente la risposta dinamica del segnale dello strumento musicale. Vista l’impossibilità di creare strumenti diversi per ogni strumento musicale da analizzare si decise di creare un circuito che rispondesse come media a tutto questo e si utilizzò la risposta dell’orecchio ai suoni con impulsi di breve durata.

n.b. Ad oggi tramite sistemi grafici RTA e Peak Meter si riesce facilmente a rappresentare la dinamica di un qualsiasi strumento musicale per poter agire correttamente con i vari processori di segnale.
Le specifiche del VU Meter richiedono un circuito con impedenza di 3.900 Ohm, ed i primi erano costruiti con una scala che al suo valore massimo poneva lo 0 dB ( il valore di riferimento ). Come molto spesso si vede ancora oggi, vedendo la figura 4 si nota come la scala in prossimità dello 0 dB sia più fine con step di 1 dB fino a – 7 dB, mentre più in basso si vede invece come sia più approssimativa da – 10 dB a – 20 dB con un step di 10 dB, questo perchè più ci si avvicina al valore massimo sopportabile prima della distorsione e più bisognerà essere attenti e precisi in modo da inviare il segnale più corretto possibile. Il tempo di reazione dell’ago per la salita dal minimo a 0 dB era di circa 300 ms ( tarato secondo la teoria del tempo di risposta dell’orecchio umano ).

Come detto era impossibile rappresentare la dinamica di uno strumento musicale in modo preciso, consci di questo fatto però era possibile sapere quali erano i margini di errore, per esempio considerando strumenti percussivi come batteria e tamburi poteva esserci un’errore rappresentativo da 10 dB a 20 dB per cui se l’ago del VU Meter indicava – 20 dB per un segnale di uno strumento percussivo, era molto probabile che nella realtà il suo valore di picco fosse a 0 dB (in quanto è il picco che ha valori alti di tensione mentre l’RMS come visto è solo una sua media, ed è il picco che manda in distorsione e danneggia le apparecchiature).

Per la voce l’errore era generalmente di 6 – 9 dB. Conoscendo questo i successivi VU Meter vennero costruiti con una scala che andava anche oltre allo 0 dB, a volte fino a + 6 dB + 9 dB ed oltre dipendente dalla qualità e costo del VU Meter.

I VU meter erano più che altro presenti in apparecchiature audio come mixer e processori per rilevare il livello dei segnali di input ed output, generalmente ( i più moderni ) erano accompagnati da una spia rossa vicino allo 0 dB che si illuminava quando il segnale superava lo 0 dB. Sopra allo 0 dB le tacche di numerazione sono generalmente di colore rosso mentre sotto lo 0 dB sono di colore nero. Era comunque uno strumento difficile e richiedeva competenze per il suo utilizzo.

fonte: [VU Meter – Davide Ruiba – Technical Audio Blog –](https://davideruiba.com/vu-meter/)

--- 

## Related Notes

- [[3. Resources/Music Production/dbVU\|dbVU]]
- [[3. Resources/Music Production/Mixing & Mastering/Gain Staging\|Gain Staging]]
- [[3. Resources/Music Production/Mixing & Mastering/Analyzer Plugin for Mixing and Mastering\|Analyzer Plugin for Mixing and Mastering]]