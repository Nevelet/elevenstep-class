---
{"dg-publish":true,"permalink":"/3-resources/music-production/slides/mixing-and-mastering/m-and-m-slides-vl/"}
---




<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/slides/mixing-and-mastering/00-m-and-m-slides-vl/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">







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


</div></div>



<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/slides/mixing-and-mastering/01-m-and-m-slides-vl/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





## 1 Modulo - Concetti/Teoria di Mixing
- 1.1 Darsi un obiettivo
- 1.2 Processi Basilari
- 1.3 Solo il Mixing non basta

---
## 1.1 [[3. Resources/Music Production/Darsi degli obiettivi di Mixing\|Darsi degli obiettivi di Mixing]]
--
### LUFS  

--
### [[3. Resources/Music Production/Tonal Balance\|Tonal Balance]]

--
### Immagine Stereo

--
### Gamma Dinamica


---

## 1.2 [[3. Resources/Music Production/Mixing & Mastering/Processi Basilari di Mixing\|Processi Basilari di Mixing]]
+ Volume
+ Equalizzatore
+ Compressore
+ Effects
+ Immagine Stereo
+ Automazioni
+ Sidechain

--

### Compressore

--

### Compressore ed Equalizzatore

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/mixing-and-mastering/compressore-ed-equalizzatore/#come-agiscono" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Come agiscono

**Enfatizzando alcune frequenze si può espandere ancora di più la dinamica o viceversa**, ed è per questo che alcune volte si mette un EQ prima e un [[3. Resources/Music Production/Audio/Compressore\|Compressore]] dopo o più processi di quest'ultimi.

Il compressore agisce sulla dinamica di un suono, ma anche sulle frequenze, infatti **se un suono ha un picco sui 500 Hz, il compressore abbassa quella zona (quindi già sta attenuando) ma in modo dinamico**, perché abbassa e alza solo quando viene colpito da queste frequenze. Infatti quando poi si recupera il volume perso dalla compressione, si alzano alcune frequenze che erano più basse...





</div></div>


---
## 1.3 [[3. Resources/Music Production/Solo il Mixing non basta\|Solo il Mixing non basta]]

--
### Scegliere il suono giusto


--
### Sound Design


--
### Scrittura e composizione


---



</div></div>



<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/slides/mixing-and-mastering/02-m-and-m-slides-vl/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">






## 2 Modulo - Fase Iniziale
- 2.1 Gain Staging
- 2.2 Routing Audio
- 2.3 Balance Mix

---
## 2.1 [[3. Resources/Music Production/Mixing & Mastering/Gain Staging\|Gain Staging]]

--
#### Cos'è il Gain Staging

--

#### [[3. Resources/Music Production/Unità di misura\|Unità di misura]]
- Peak db
- LUFS


--
#### Come regolare i livelli

--
#### [[3. Resources/Music Production/Clipping\|Clipping]]


---
## 2.2 Routing Audio

--
#### Bus Mix

--
#### Cos'è un Bus Mix


--
#### Routing Bus Mix


--
#### Lasciare Headroom
![Headroom](https://line6podhditalia.files.wordpress.com/2018/07/audio-mastering-headroom.jpg?w=800)

---
## 2.3 [[3. Resources/Music Production/Mixing & Mastering/Balance Mix\|Balance Mix]]

--
#### Cos'è il Balance e perché è fondamentale

--
#### Requisiti per aver un ottimo Balance

--
#### Come una squadra di calcio

--
#### Come Intervenire

--
#### Come bilanciare ogni elemento di un mix

--
#### Balance Mix con gli Strumenti di M&M

---

</div></div>


![[03 M&M (Slides VL)\|03 M&M (Slides VL)]]


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/slides/mixing-and-mastering/04-m-and-m-slides-vl/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




## 4 Modulo - Mixing Kick & SUB
- 4.1 Mixing Sub
- 4.2 Mixing Kick & Sub

---
## 4.1 Mixing Sub
--

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/synth-sub-bass-mixing/#equalizzazione" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Equalizzazione

C'è poco da equalizzare in un suono come il Sub. Ma qualora si abbia un sub con delle armoniche (vedi saturazione) allora con un EQ **si può intervenire sulla zona 150/200 hz e in aggiunta anche un filtro high cut per dare ancora più spazio al kick**


</div></div>


--

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/synth-sub-bass-mixing/#compressione" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Compressione

Anche qui, c'è poco da intervenire. Meglio non comprimerlo, in quanto il sub non ha tanta dinamica


</div></div>


--

## Dare più presenza
--
### [[3. Resources/Music Production/Saturation\|Saturation]]
Saturare il SUB permette di aggiungere delle armoniche e cosi facendo, risulterà più presente.

--
### [[3. Resources/Music Production/Layering\|Layering]]
In alcuni situazioni, il sub soltanto non basta, e quindi come sempre il [[3. Resources/Music Production/Layering\|Layering]] ci viene d'aiuto.

--
### [[3. Resources/Music Production/Transient Noise\|Transient Noise]]
Si può aggiungere ad esempio un rumore bianco, come ad esempio in questa tecnica

---
## 4.2 Mixing Kick & Sub
--


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/mixing-and-mastering/kick-and-sub-mixing/#balance-kick-e-sub" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Balance Kick e Sub

![image_1631828669292_0.png](/img/user/3.%20Resources/Images/image_1631828669292_0.png)
![image_1631828681254_0.png](/img/user/3.%20Resources/Images/image_1631828681254_0.png)


</div></div>


--

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/mixing-and-mastering/kick-and-sub-mixing/#quanto-basse-deve-avere-il-kick-e-quante-il-sub" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




Links:: [[3. Resources/Music Production/Mixing\|Mixing]], [[3. Resources/Music Production/Kick\|Kick]], [[3. Resources/Music Production/Synth Sub Bass\|Synth Sub Bass]]

---
## Balance Kick e Sub

![image_1631828669292_0.png](/img/user/3.%20Resources/Images/image_1631828669292_0.png)
![image_1631828681254_0.png](/img/user/3.%20Resources/Images/image_1631828681254_0.png)

## Livelli Audio

_Quanto basse deve avere il kick e quante il sub?_
- Grazie al [[3. Resources/Music Production/VU Meter\|VU Meter]] puoi bilanciare velocemente Kick e SUB
- Un ottimo valore per il Kick è stare all'incirca sui -3 dbvu, e insieme al SUB, dovrebbe stare attorno allo 0 dBVU.

## [[3. Resources/Music Production/Sidechain\|Sidechain]]

- **[[3. Resources/Music Production/Sidechain\|Sidechain]] indipendente per intervenire più pesantemente rispetto agli altri suoni.**
- l'utilizzo di un compressore va più che bene. Magari se ha la possibilità, **utilizzare la release automatica, cosi prende tutta la coda del kick.** 
- Altra cosa, **sul sidechain, usare l'eq per prendere solo il body del kick** 
- È possibile usare il Sidechain inverso, ossia abbassare le basse del kick quando c'è il sub con un EQ multibanda

### Plug-in/Dipositivi

- Duck
- [[2. Areas/ES - Content Creation/Content Video ES/Trackspacer plugin\|Trackspacer plugin]]
- Compressor (Ableton)


### Setting Sidechain con l'oscilloscopio

- Plug-in/Dipositivi
	- PSYSCOPE
	- Signalizer

### Evitare l'avvallamento

- Mettere in loop kick e sub con nota lunga
- Settare per bene la curva del Sidechain

### Editing Audio


## Gestione della Fase

### Controllare la fase del sub

- No random phase
- spostare la fase se necessario

### Tail kick

- Una coda troppo lunga rischia di far lavorare troppo il sidechain e di avere problemi di fase con il SUB. Con il **fade out** puoi eliminare la coda in eccesso più dolcemente.
- Accorciare la coda del kick con Duck
- Release Transient Shaper




</div></div>


--

### Sidechain

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/mixing-and-mastering/kick-and-sub-mixing/#plug-in-dipositivi" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



### Plug-in/Dipositivi

- Duck
- [[2. Areas/ES - Content Creation/Content Video ES/Trackspacer plugin\|Trackspacer plugin]]
- Compressor (Ableton)



</div></div>


--

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/mixing-and-mastering/kick-and-sub-mixing/#setting-sidechain-con-l-oscilloscopio" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



### Setting Sidechain con l'oscilloscopio

- Plug-in/Dipositivi
	- PSYSCOPE
	- Signalizer


</div></div>


--


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/mixing-and-mastering/kick-and-sub-mixing/#evitare-l-avvallamento" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



### Evitare l'avvallamento

- Mettere in loop kick e sub con nota lunga
- Settare per bene la curva del Sidechain


</div></div>


--

### Gestione della Fase


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/mixing-and-mastering/kick-and-sub-mixing/#controllare-la-fase-del-sub" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



### Controllare la fase del sub

- No random phase
- spostare la fase se necessario


</div></div>


--


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/mixing-and-mastering/kick-and-sub-mixing/#tail-kick" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



### Tail kick

- Una coda troppo lunga rischia di far lavorare troppo il sidechain e di avere problemi di fase con il SUB. Con il **fade out** puoi eliminare la coda in eccesso più dolcemente.
- Accorciare la coda del kick con Duck
- Release Transient Shaper




</div></div>


---



</div></div>



<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/slides/mixing-and-mastering/05-m-and-m-slides-vl/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




## 5 Modulo - Mixing Bass


---

# Mixing Bass
--


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/synth-generic-bass-mixing/#tipi-di-bassi-per-generi" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




Links:: [[3. Resources/Music Production/Synth (Mixing)\|Synth (Mixing)]], [[3. Resources/Music Production/Mixing\|Mixing]], [[3. Resources/Music Production/Synth Mid-Bass (Mixing)\|Synth Mid-Bass (Mixing)]]

---

## [[3. Resources/Music Production/Mixing & Mastering/Equalizzazione\|Equalizzazione]]

- Ripulire 
- Risonanze
- [[3. Resources/Music Production/Tonal Balance\|Tonal Balance]]

## [[3. Resources/Music Production/Mixing & Mastering/Compressione\|Compressione]]

- Compattezza
	- [[3. Resources/Music Production/Ableton/Ableton - OTT (Multibanda)\|OTT]]
	- [[3. Resources/Music Production/Compressione Upward\|Compressione Upward]]


## [[3. Resources/Music Production/Effetti Audio\|Effetti Audio]]

gestire gli effetti all'interno dei synth: routing e processing. 

- [[3. Resources/Music Production/Audio/Reverb\|Reverb]]
- Delay
- Distortion
- Chorus
- Flanger
- Phaser

### Plugins

- IVGI (Saturation)


## [[3. Resources/Music Production/Mixing & Mastering/Immagine Stereo\|Immagine Stereo]]

- Panning
- [[3. Resources/Music Production/Mixing & Mastering/Posizionamento dei suoni nell'Immagine Stereo\|Posizionamento dei suoni nell'Immagine Stereo]]
- Effetti e strumenti per dare/creare immagine stereo
	- Doubler
	- Chorus
	- [ElevenStereo](http://bit.ly/3ZfzELS)
- [[3. Resources/Music Production/Mixing & Mastering/Equalizzazione Mid-Side\|Equalizzazione Mid-Side]]

### Altre risorse

- [[4. Archived/1. Projects/Completed/ES - Content Creation (Elevenstep)/Come Gestire e Creare più Immagine Stereo/✍ Come Gestire e Creare più Immagine Stereo\|✍ Come Gestire e Creare più Immagine Stereo]]

## Mixing [[3. Resources/Music Production/Layering\|Layering]]

- Layers dei Bassi
- più stretta l'immagine stereo

## Bus Basses

- EQ
- Compressione Glue
- Stereo su bassi con [[3. Resources/Music Production/Stereo Doubler\|Stereo Doubler]] o [[3. Resources/Music Production/Stereo Widening\|Stereo Widening]]
- [[3. Resources/Music Production/Saturation\|Saturazione]] (IVGI)

## [[3. Resources/Music Production/Sidechain\|Sidechain]]


## Automazioni

- Automazione filtri, pitch, effetti 


## Rack

- ElevenRack MidBass




</div></div>

--


## Equalizzazione
- Eq Low-cut per dare spazio al sub e far lavorare bene il compressore 

--
## Compressore Multibanda
- Perché comprimere singolarmente le 3 o più bande?
- Gestire il Time
- Regolare per bene le varie bande: threshold, attack e release
- ascoltare singolarmente ogni banda


--
## Effects
- Riverbero


--
## Compressione
- Glue Compressor


--
## Eq (Tonal Balance)


--
## Saturation 


--
## Immagine Stereo
- Eq M/S


--
## Layers


--
## Compressione finale


--
## Volume

---

</div></div>



<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/slides/mixing-and-mastering/06-m-and-m-slides-vl/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




## 6 Modulo - Mixing Vocal


---
## Compressore ed Equalizzatore


---
## Equalizzazione


---
## Compressione


---
## Utilizzo del Dee-esser


---
## Utilizzo degli Effetti


---
## Immagine Stereo


---
## Tecniche avanzate
  - Equalizzazione Dinamica
  - Uso dell'ambiente con Sidechain



</div></div>







