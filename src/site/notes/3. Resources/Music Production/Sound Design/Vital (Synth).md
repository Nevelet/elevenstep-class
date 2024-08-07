---
{"dg-publish":true,"permalink":"/3-resources/music-production/sound-design/vital-synth/"}
---

Links:: [[3. Resources/Music Production/Plugins/Plugin Audio Instrument\|Plugin Audio Instrument]], [[3. Resources/Music Production/Synth\|Synth]], [[3. Resources/Music Production/Plugins/Plugin\|Plugin]]
 
---
Spectral warping wavetable synth
Synth wavetable con distorsione spettrale

## 0. Info Generali
### Dove scaricarlo
- [Vital - Spectral Warping Wavetable Synth](https://vital.audio/)

### Sizing
- Cliccando sul logo
-   Trascinando l'estremità in basso a destra

### Navigazione generale
Nella parte superiore del synth, ci sono 4 schede: Voice, Effects, Matrix e Advanced. 
Qui sotto puoi vedere cosa contiene ogni scheda.

- Voice: Oscillatori, Campionatore, e filtri
- Effects: 9 Effetti, tra cui: Reverb, Delay etc...
- Matrix: Contiene tutta la lista delle varie modulazioni effettuate, andando pure ad intervenire più nel dettaglio su quest'ultime.
- Advanced: Opzioni avanzate per gli oscillatori e molto altro.

---



## 1. Presets

### Opzioni preset

**Preset Precedente/Successivo**
ai lati sul nome del preset, hai la possibilità di passare nel preset precedente e in quello successivo.

**Come entrare nel browse**
Per entrare nel browse dei preset, si può fare in due modi: 
- cliccando sul nome del preset
- menù di fianco al selettore dei preset


### Preset Browser

**Search**
qui è possibile cercare tra tutti i preset presenti.

**Categorie**
possiamo anche cercare in base alle categorie

**All, Folder e Favorites**
le cartelle possono essere utilizzate come categorie e autori. 
Insieme alle cartelle che trovi già presenti su Vital, trovi anche: All (per visualizzare tutti i preset) Favorites (per mostrare i preset preferiti) e User Preset (i preset dell'utente una volta salvati).


**Info Preset**
Ad ogni preset possiamo attribuire un nome e un autore

**Sezione Preset (Posizione, rinominare e cancellare)**
con il Click destro si può:
- aprire la posizione del preset
- rinominare 
- cancellare

**Ordinare i preset**
di fianco ai preset possiamo cliccare sulla stellina per metterli tra i preferiti

In alto sopra ai preset, c'è la possibilità di ordinare per nome, stile, autore e data

### Import & Export

Percorso preset WIN & MAC
- **Windows:** “[NOME UTENTE]/Documents/Vital/User/Presets”
- **Mac:** “Library/Audio/Presets/Vital”


- **Initialize Preset**

- **Save Preset**
	salva il preset nella cartella "User"
	Nota: quando viene salvato un preset o sovrascritto, a volte è necessario chiudere o riavviare il plug-in. 

- **Aprire la posizione del preset**

- **Export preset**
con questo hai la possibilità di decidere tu in quale posizione salvare il preset

- **Export Bank**
permette di esportare più preset in un unico file dal formato "bank"

- **Import Preset Bank**

- **Load Tuning Files**
==Importando ad es. un file dal formato .tun, puoi cambiare il comportamento, il rapporto che c'è tra le note.==
Pitagorica è l'antica accordatura standard originale basata interamente sulle quinte perfette.
Prova l'accordatura ==pitagorica per brani orchestrali o brani sperimentali.==
Questo sistema di messa a punto contiene alcune stranezze e alcune regole lasciate aperte all'interpretazione.
==Alcuni strumenti più vecchi avevano persino due toni per la stessa nota.==
Questo si riferisce alla serie armonica e al modo in cui alcune delle armoniche di ordine superiore sono "stonate".

---

## 2. Voice
### Pitch
- **Transpose**
permette di cambiare i semitoni

Per ==cambiare il transpose del pitch ad ottave==, premere SHIFT+Scroll del mouse

- **Tune**
spostamento fine/cent del pitch

- **Transpose Snap**
	permette di cambiare il pitch seguendo solo alcune note, utilissimo per creare arpeggi.
	- Global Snap 
		- aggancia le uscite della tastiera midi alla nota più vicina mappata nello snap globale


### Level e Pan
### Routing
È possibile mandare il segnale di un OSC/Sample in uscite diverse. 
Le uscite disponibili sono:
- Filter 1
- Filter 2
- Filter 1+2
- Effects
- Direct Out

è possibile cambiare il routing anche sul filtro stesso.

### Wavetable
**Browse Wavetable**
==Come per i preset, qui troviamo sulla sinistra le forme d'onde di fabbrica e nella cartella User, quelli che abbiamo creato/salvato noi.==
Ovviamente anche qui possiamo visualizzare tutte le wavetable o quelli che abbiamo messo nei preferiti. 

- Search
	- Possibilità di cercare tra le wavetable
- Preferiti e posizione

---
- Cartelle
	- All
	- Favorites
	- Factory
	- User
	- Add Folder
---
**Visualizzazione Waveform**
- 2D
- 3D
- SP

### Unison & Phase
**Unison Voices**
È possibile aggiungere fino a 16 voci
**Unison Detune**
per detunare le verie voci, fino al 100%

**Phase**
è possibile cambiare la fase da 0 a 360°
**Phase Randomization**
al 100% la fase verrà randomizzata ogni volta. 

### Spectral & Wave Morph 
==Il parametro di sinistra modifica la forma d'onda, utilizzando diversi algoritmi.== 
==Il parametro di destra, invece ha alcuni algoritmi aggiuntivi per modificare anch'esso la forma d'onda, ma include anche l'opzione per eseguire la Frequency modulation or ring modulation,== usando un altro oscillatore o il campionatore come input.{ #4zewv1}


**Spectral Morph** 
- Vocode
	- spostamento formante del vocoder (meno estremo del Formant Scale)
- Formant Scale
	- spostamento formante (più estremo del vocoder)
- Harmonic Stretch
	- ==mantiene in posizione l'armonica fondamentale mentre si spostano tutte le altre armoniche su e giù.== (Non consente alle armoniche di andare al di sotto dell'armonica fondamentale)
- Inharmonic Stretch
	- ==mantiene in posizione l'armonica fondamentale mentre sposta tutte le altre armoniche verso l'alto o verso il basso non in linea con la serie armonica.== (Non consente alle armoniche di andare al di sotto dell'armonica fondamentale)
- Smear 
	- rimuove le armoniche di ordine basso modificando la forma d'onda.
- Random Aplitudes
	- rende casuale l'ampiezza di ciascuna parte della forma d'onda mantenendone alcune continuità.
- Low Pass
	- ==Applica un filtro passa basso alla forma d'onda.== Questo rimuove efficacemente le armoniche di ordine superiore. ==Se il parametro viene abbassato completamente a sinistra, il risultato sarà simile ad un sinusoide.==
- High Pass
	- ==Applica un filtro passa alto alla forma d'onda.== Rimuove efficacemente tutte le armoniche di ordine inferiore fino a quando tutte le armoniche nella gamma dell'udito umano. Il parametro girato completamente a destra, si tradurrà in silenzio.
- Phase Disperse
	- Disperde la fase della forma d'onda. Pensalo come una diffusione casuale della forma d'onda orizzontalmente.
- Shepard Tone
	- Il tono di un pastore ==è un suono che sembra aumentare continuamente di tono.== Questa illusione uditiva si verifica quando un suono aumenta di tono e svanisce lentamente, come un altro tono e l'ottava sotto di essa, che si dissolve lentamente. ==Il parametro quando viene trascinata lentamente da sinistra a destra eseguirà questa illusione uditiva.==
- Spectral Time Skew
	- modifica le armoniche tra le posizioni/frame del wavetable.
{ #xkodt8}


**Wave Morph** 
- Sync
	- ==Ripete la forma d'onda e la schiaccia.== Ciò si traduce nell'aumento del tono in ottave in modo relativamente fluido, senza suonare altre note.
- Formant 
	- È simile alla sincronizzazione, ma evita di introdurre l'offset dc
- Quantize 
	- Quantizza la forma d'onda in una griglia. La griglia diventa meno raffinata quanto più si gira il parametro verso destra. ==Questa è essenzialmente una riduzione di bit/campione.==
- Bend 
	- ==Pizzica la forma d'onda a 180 gradi e trasforma il resto della forma d'onda a destra o a sinistra,== a seconda di come si gira il parametro.
- Squeeze
	- ==Pizzica la forma d'onda a 0, 180 e 360 gradi e trasforma il resto della forma d'onda a destra o rispettivamente a sinistra,== a seconda di come si gira il parametro.
- Pulse
	- ==Allontana la forma d'onda all'estremità,== fino a schiacciarla completamente se il parametro viene girato del tutto a destra.
- FM (Frequency Modulation)
	- ==Riproduce l'oscillatore corrente alla frequenza di un altro oscillatore o campionatore. Questo produce suoni complessi con caratteri armonici distinti. È ampiamente utilizzato nel sound design moderno.==
- RM
	- ==Riproduce l'oscillatore corrente con l'ampiezza modulata da un altro oscillatore o campionatore.==
{ #bcjgme}


### Sampler
**Opzioni di Playback**
- Keytracking
	==Attivandolo, il campione verrà riprodotto con l'intonazione corrispondente alla nota midi suonata.==
	==Notare che i campioni verranno accelerati o rallentati per aumentare o diminuire il tono.==
	Se il keytracking è disattivato (come per impostazione predefinita), il campione verrà riprodotto alla sua altezza e velocità originali.
- Shuffle
	Shuffle sono le frecce incrociate nell'angolo in alto a destra.
	L'attivazione della riproduzione casuale ==avvierà il campione da un punto casuale== all'interno del campione ogni volta che viene suonata una nota midi.
- Loop
	Loop è la freccia circolare nell'angolo in basso a sinistra.
	L'attivazione del loop ==eseguirà il loop del campione all'infinito==
- Bounce Back
	L'attivazione di Bounce Back ==riprodurrà il campione all'indietro non appena il campione finisce di essere riprodotto in avanti.==



### Filters
- **Attivatore (bypass)**
- **Scelta del tipo di filtro**
{ #4tl7jf}

	- Analog, Dirty e Ladder
		- Il Ladder è un Filtro Dinamico a Transistor basato sul design del filtro Ladder originale di Bob Moog.
		- Tipo di filtro
			- Notch Blend: un misto tra un filtro passa-basso, notch e passa-alto da 24 dB
			- Notch Spread: unisce un filtro passa-banda e un filtro notch 24 dB. Nota che nel mezzo di questi, c'è un doppio notch filter.
			- B/P/N: Notch di picco della banda. Un misto tra un filtro passa-banda, peak e notch
	- Diode
		- Il diodo dovrebbe imitare il filtro ladder a diodi di Roland, che ha dato vita al suono Acid House Bass.
	- Formant
		- Un filtro formante dovrebbe imitare il modo in cui la voce umana produce suoni vocalici. La forma di questo filtro, sembrano delle montagne. 
		![[Pasted image 20211003202002.png\|Pasted image 20211003202002.png]]
	- Comb Filter
		- ==I filtri a pettine sono una serie di filtri notch.== Tipicamente posti in modo esponenziale a parte o come parte della serie armonica. Il filtraggio a pettine può ottenere lo stesso suono di un flanger grazie al modo in cui un flanger funziona con la cancellazione di fase. Tuttavia, non dovresti pensare a un filtro a pettine come a un flanger, perché fanno due cose diverse. Sono due strumenti e approcci separati che possono essere utilizzati per ottenere lo stesso risultato.
	- Phaser
		- ==Un filtro a pettine con meno tacche.== Il filtraggio a pettine può ottenere lo stesso suono di un phaser grazie al modo in cui un phaser funziona con la cancellazione di fase. Tuttavia, non dovresti pensare a un filtro a pettine come a un phaser, perché fanno due cose diverse. Sono due strumenti e approcci separati che possono essere utilizzati per ottenere lo stesso risultato.
		- Ovviamente ==l'effetto Phaser situato nella scheda Effects, ha diverse parametri che permettono di ottenere un effetto Phaser o Flanger, più articolato. ==
- **Curva di risposta in frequenza filtrata**
- **Frequenza di taglio**
- **Risonanza**
- **Miscela tipo di filtro**
- **Routing dell'ingresso del filtro**
- **Parametro Drive, Mix e Keytracking**



## 3. Modulation
Basta trascinare la modulazione scelta sul parametro desiderato.

**Opzioni modulazioni**
- Remove
- Bypass
- Make Bipolar
- Make Stereo
	- Make Stereo: modula i parametri sinistro e destro in direzioni opposte per i canali sinistro e destro
- Lean MIDI
- Enter Value

**Tricks**
- Ascoltare l'enteprima della modulazione
- Il tasto ALT permette di fare una modulazione inversa
- Doppio Click per rimuovere una modulazione
- Passare il mouse per vedere quali parametri sono stati modulati.

### Envelope
Il primo envelope, controlla di default il volume globale

- Delay
- Attack
- Hold
- Decay
- Sustain
- Release

### LFO
**Controlli**
- Pennello
- Grid
- Selettore forma LFO
- Smooth (morbido)
- Delay
- Stereo

**Riquadro Envelope**
- Copia
- Salvare forma LFO
- Capovolgi orizzontalmente
- Capovolgi in verticale
- Import/Export LFO

**Opzioni Punto Inviluppo**
- Imposta il punto iniziale
- Rimuovi punto
- Inserisci Punto Fase/Valore

**Modalità**
- Trigger
- Sync
- Envelope
- Sustain Envelope
- Loop Point 
- Loop Hold

**Frequency**
- Seconds 
- Tempo
- Tempo Dotted
- Tempo Triplets
- Keytrack

**Tricks**
- ALT per spostamenti fini
- SHIFT per modificare più curve
- CTRL per utilizzare il pennello

### Random
**Controlli**
- Sync
- Stereo

**Style**
- Perlin
- Sample & Hold
- Sine Interpolate
- Lorenz Attractor


**Frequency**
- Seconds 
- Tempo
- Tempo Dotted
- Tempo Triplets
- Keytrack

### MPE
- Note
- Velocity
- Lift
- Oct Note
- Pressure
- Slide
- Stereo
- Random

### Macro

## 4. Matrix

## 5. Effects
- Chorus
- Compressor
- Delay
- Distortion
- Eq
- Filter
- Flanger
- Phaser
- Reverb


## 6. Controlli Generali
### Voice e Spread
- Voice
	- Determina la quantità di nota midi che può essere suonata contemporaneamente. Nota che questo è diverso da Voci all'unisono dell'oscillatore
- Bend
	- Determina il range in semitoni del Pitch Bend
- Vel Trk
	- Velocity Tracking
- Spread
	- l'impostazione di questo parametro completamente a destra, non avrà alcun impatto sull'uscita del synth. ==Ruotandolo invece verso sinistra, sommerà i segnali stereo in mono.==
	- Click Destro del mouse per cambiare da Spread (diffusione) a Rotate (ruotare).

### Glide
- Glide
	- Determina la quantità di tempo in secondi impiegata da una nota midi per passare alla nota midi successiva
- Slope
	- Determina la curva del pitch glide tra due note midi.
- Always Glide
	- Quando attivato, ogni nota midi eseguirà il pitch glide a partire dalla precedente nota midi suonata. Quando è disattivata, ogni nota midi esegue il pitch glide solo quando due note midi si sovrappongono.
- Octave Scale
	- Quando attivato, il tempo di Glide dipenderà dalla distanza delle due note midi. Per esempio un Glide di 3 ottave impiegherà 3 volte il tempo necessario per un Glide di 1 ottava.
- Legato
	- Quando le voci sono impostate su 1 e il legato è attivo, le modulazioni come gli inviluppi o gli LFO non saranno attive, quando viene suonata una nuova nota midi sovrapposta


## 7. Wavetable Editor
consente di modificare la forma d'onda o le singole armoniche di qualsiasi frame in una wavetable.

## 8. Impostazioni avanzate

### OSC Options
- Note Track
- Hi-Res Wavetable
	- Wavetables utilizzerà un'alta risoluzione. Questo probabilmente non è necessario nella maggior parte delle circostanze, ma potrebbe avere un impatto positivo per le wavetable con molte frequenze alte.

### OSC Unison
Attivo soltando se c'è più di una voce nell'OSC

- Stack
	- Determina come verranno impilate le voci all'unisono in termini di intonazione

- Detune Range
	- Determina il limite di quanto l'intonazione di una voce può essere scordata in semitoni
- Unison Blend
	- Regola il volume delle voci detunate.
- Stereo Unison
	- Somma il segnale stereo in mono quando ruotato completamente a sinistra.
- Table Spread
	- Diffonde le voci in diverse posizioni della wavetable. La gamma di posizioni wavetable è mostrato visivamente sopra.
- Spect Spread
	- Diffonde le voci in diverse posizioni del parametro Spectral Morph, situato nell'OSC.
- Dist Spread
	- Stessa cosa di "Spect Spread" solo che diffonde le voci sul parametro "Wave Morph"

### Voice
Priorità nota: quando vengono suonate più note midi rispetto alle voci globali, questa opzione deciderà quali note devono suonare e quali no. 
Nota che una nota midi appena aggiunta suonerà sempre. La priorità è presa dal pool di note midi esistenti.

- Newest: 
	- le note midi più recenti hanno la priorità rispetto alle note midi più vecchie
- Oldest: 
	- le note midi più vecchie hanno la priorità sulle note midi più recenti
- Highest: 
	- le note midi con tono più alto hanno la priorità rispetto alle note midi con tono più basso
- Lowest: 
	- le note midi più basse hanno la priorità sulle note midi più alte
- Round Robin: 
	- simile a "Highest"
---

- Tuning: 
	- Carica un file di accordatura per determinare la spaziatura delle note midi.

- MPE Enabled
	- Per attivare l'MPE (MIDI Polyphonic Expression)

- Tune e Transpose

### Oversampling
Imposta la quantità di sovracampionamento per il synth.
Secondo il teorema di Nyquist il sovracampionamento 2x dovrebbe essere sufficiente per praticamente tutti i suoni che un essere umano poter sentire. Tuttavia, su alcuni suoni con molta enfasi sulle frequenze alte, potrebbe essere necessario un sovracampionamento un po' utile a scapito dell'utilizzo della CPU

Il sovracampionamento 1x probabilmente risulterà in qualche aliasing per le frequenze di fascia alta. I sintetizzatori senza frequenze di fascia alta non subiranno alcun impatto se impostati su sovracampionamento 1x e faranno risparmiare un po' di CPU utilizzo. Inoltre, l'aliasing potrebbe essere utilizzato come tecnica sperimentale di sound design.

### Analysis

### Mappatura Parametri






## 9. Skin

- https://forum.vital.audio/t/skin-sharing-thread/5631
- [Cartella - Google Drive](https://drive.google.com/drive/folders/1nXSzKaboSVDDiRTnpZARfY48nnsKHymG)
- [How to make Vital skins「FREE Downloads」 - YouTube](https://www.youtube.com/watch?v=1vlGB5DCHug)