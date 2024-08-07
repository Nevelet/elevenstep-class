---
{"dg-publish":true,"permalink":"/3-resources/music-production/slides/mixing-and-mastering/00-m-and-m-slides-vl/"}
---




## Organizzare la Sessione per il Mixing

--

### Dare un Nome alle tracce

- _Battezzare le tracce dando un nome_
- Ogni traccia deve obbligatoriamente avere un nuovo identificativo, altrimenti in fase di produzione e di mix, ci si perde tra tutti i suoni che ci sono

--

### Eliminare se necessario...

- A volte ci sono tante ==tracce inutili== nel nostro progetto che ci fanno solo confondere: "questa era attivata?" "Questa è utile?" "Questa dove suona?"
- Meglio sbarazzarsi subito di queste tracce, magari se non sei sicuro di eliminarle completamente, allora puoi ==salvare il progetto con un'altra versione== (consiglio di farlo sempre) cosi almeno puoi ritornare indietro.

--

### Evitare un Routing complicato

Non complicarti la vita facendo un routing complicato, ad esempio: gruppo dentro un altro gruppo con l'output su un bus mix o master bus (mi sono confuso pure a scriverlo).

--

### Raggruppare le tracce

_Quello che faccio è catalogare tutti i suoni in base anche al proprio ruolo_

- **Drums:** Kick, Snare, Tops, Percs
- **Synth:** Low end, Mid Synths, Atmos, Melody
- **MidBass**
- **Sub**
- **Vocals:** Lead, BG, Vocals Drop, Fx Vocals
- **Sample:** FX, Altro

--

### Dare un Colore

Ogni gruppo ha anche un colore diverso, che uso su quasi tutti i progetti, cosi da avere fin da subito familiarità con tutto.

--

### Nascondere le tracce
- Alcune DAW come Studio one e Logic, permettono di nascondere delle tracce dalla vista su cui si sta lavorando, questo ti permette di focalizzarti meglio su ciò che vedi, senza mandare i tuoi occhi in confusione alla ricerca delle tracce.
- Alcune di queste DAW, permettono pure di creare dei preset per un gruppo di tracce da visulizzare, ad es. puoi fare un preset dove ci sono solo le tracce di batteria, dove ci sono solo i synth e cosi via.

--

### Blocco Note
- Potrebbe sembrare stupido, ma scrivere tutto quello che c'è da fare o quello che vorresti migliorare, è invece importante! La nostra mente non è fatta per ricordare tutto e per mantenere a lungo le informazioni, quindi scrivere ti aiuta a non dimenticare niente e soprattutto a liberare la mente.

--

### Creare un Template

--

### Salvare diverse versioni

- Ci sono diversi modi per dare un nome al progetto, ma indipendentemente da quale scegli, salvare il progetto in base al giorno o alla versione è importante.
- Alcuni salvano i progetti per data, in questo modo: 20210806_[nome progetto] cosi facendo, se ordini per nome, troverai l'ultimo o il primo progetto che hai utilizzato.
- Perché ordinare per data? Beh perché sarà più facile ascoltare ad esempio il mix di una determinata data.
- Oltre ad applicare la data, è importante pure indicare la versione, tipo: 20210806_[nome progetto] (v2) questo perché duranta la giornata potresti aver fatto tante modifiche al progetto e quindi potresti tornare indietro facilmente. Potresti anche non mettere la data, e indicare soltanto la versione corrente.


---

## Avere un Rough Mix

Avere un mix grezzo ti aiuta a capire cosa deve essere migliorato e cosa non va toccato. A volte puoi anche notare che c'è qualche suono in più o che magari stai andando fuori strada e il mix finale è troppo acceso.

---

## Frequenza di Campionamento e Bit Rate & Bit Depth

--

### Cos'è

La frequenza di campionamento è la misura espressa in hertz, che indica il numero di volte al secondo in cui un segnale analogico viene misurato e memorizzato in forma digitale (da "digit" che in inglese significa "cifra"; in questo caso, nel mondo informatico e elettronico, il significato varia in "cifra binaria").

--

Dunque, il campionamento è la conversione di un segnale analogico in digitale, effettuando tante "fotografie" al secondo, in base al sample rate impostato.

--

![Campionamento.png|600](/img/user/3.%20Resources/Images/Campionamento.png)

--

La qualità del file da riprodurre è dato da due fattori: risoluzione e frequenza di campionamento. La risoluzione è espressa in Bit, mentre il valore di campionamento è espresso in Kilohertz (kHz).

Come puoi vedere dall'immagine sopra, il Bit, indica risoluzione di ampiezza, mentre la freq. di campionamento, la risoluzione in frequenza.

--

### Quale Frequenza di Campionamento scegliere

Le frequenze di campionamento più utilizzate sono:
- 44.100 hz
- 48.000 hz

--

Inoltre, la frequenza di campionamento di un file audio deve essere uguale a quella del progetto, per evitare cambi di pitch.

--

Alcune DAW effettuano la conversione (downsampling o upsampling) in automatico o tramite un'opzione, per adattare il file audio al progetto.

--

### Perché lavorare a frequenze di campionamento alte, se il prodotto finale sarà quasi sempre a 44.100 hz?

--

Lavorare a frequenze di campionamento alte, permette specialmente nella post produzione, di avere più campioni e quindi più risoluzione, soprattutto quando si effettuano alcuni interventi di questo tipo:

--

- **Stretching**
più un file audio viene stretchato, meno campioni ci saranno e di conseguenza il programma dovrà interpolare quelli rimanenti. Questo in alcuni casi porta un degrado dell'audio.

+ **Saturazione**
Le armoniche superiori generate in saturazione sbattendo contro la frequenza di Nyquist tornano indietro come rumore

+ **Altri processi**
Ovviamente questo vale anche per processi di equalizzazione, compressione, limiting ecc...

+ **Plug-in**
I plug-in lavorano meglio con freq. di campionamento alta, soprattutto gli oscillatori, riescono ad avere più definizione sulle armoniche.

--

==Quindi una freq. di campionamento alta è più adatta quando si effettuano processi molto pesanti nell'audio.==

--

### Alte Frequenze e Filtro

Quando viene effettuato il campionamento, per alcuni problemi di elettronica, ad es. problemi di [[3. Resources/Music Production/Aliasing\|Aliasing]], viene applicato un filtro, quest'ultimo ha una pendenza diversa in base alla frequenza di campionamento scelta, più alta sarà la frequenza, più morbido sarà l'intervento di filtering. Considerando pure che Il filtro, di suo, andrà rovinare un po' il segnale per i suoi problema più noti, come la fase.

--

### Resampling 

Sul ricampionamento bisogna stare attenti con quale software/DAW viene effettuato. Alcuni permettono di scendere da 96khz a 44.1 khz senza problemi, con un buon rapporto di qualità, altri invece fanno dei pasticci.

--

### Upsampling

l'upsampling è interpolazione, quindi aggiunta di campioni "calcolati".
Nel caso dell'upsampling viene aumentato ma non significa che aumenta la definizione o qualità (anzi). I campioni che vengono aggiunti infatti sono "calcolati" e non sono effettivi. E' come se avessi mezzo litro di vino e aggiungessi mezzo litro d'acqua dicendo che ora hai un litro di vino...

--
### Downsampling

Il sotto-campionamento o decimazione (downsampling in inglese) è nella teoria dei segnali l'operazione di riduzione della frequenza di campionamento del segnale elettrico.

--

==Il downsampling il numero di campioni viene ridotto abbassando ovviamente la definizione e quindi la qualità.==


---

## Strumenti per il Mixing

  - [[3. Resources/Music Production/Mixing & Mastering/Analyzer Plugin for Mixing and Mastering\|Analyzer Plugin for Mixing and Mastering]]
  - [[3. Resources/Music Production/Traccia di Riferimento\|Traccia di Riferimento]]

--

### Plug-in Analyzer

--

#### Frequenze

--

#### **Voxengo SPAN**

Lo strumento per eccellenza è lo SPAN, questo ti permette di dare visione di tutti i suoni che stai utilizzando all'interno dello spettro. 

--
_SPAN è un analizzatore di spettro audio AAX, AudioUnit e VST gratuito_

--

Immagina gli strumenti come gli spettatori di un film al cinema, essi avranno un numero assegnato per i posti, quindi sapranno dove posizionarsi. Ecco, questo è quello che devi fare con i tuoi suoni, assegnare a loro un posto all'interno dello spettro.

--

### Dinamica (oscilloscopio)

--

#### **PSYSCOPE**
Psyscope è un plug-in gratuito per oscilloscopio sincronizzato

--

#### **Signalizer**
Signalizer è un pacchetto di visualizzazione del segnale all-in-one

--

#### **s(M)exoscope**
Plugin per la visualizzazione della forma d'onda

--

### Loudness

**YOULEAN LOUDNESS METER 2**
Youlean Loudness Meter ti aiuta a trovare il vero livello percepito (LUFS) del tuo audio

--

### Tools
**CheckMaster (Rack)**
Un mio rack per ascoltare ogni banda nel master e per il MID/SIDE

--

**ISOL8 (TBProAudio)**
ISOL8 divide la gamma di frequenza in 5 bande. Queste 5 bande possono essere messe in solo o in mute individualmente. Questo ti aiuterà a concentrarti su determinate gamme di frequenza durante il processo di missaggio e mastering.

--

**mvMeter2 (VU Meter)**
mvMeter è un misuratore multivariabile che include misurazioni RMS, EBUR128, VU e PPM.

---
