---
{"dg-publish":true,"permalink":"/3-resources/music-production/sidechain/"}
---

Links:: [[3. Resources/Music Production/Mixing & Mastering/Processi Basilari di Mixing\|Processi Basilari di Mixing]], [[3. Resources/Music Production/Tecniche avanzate di Mixing\|Tecniche avanzate di Mixing]]

---
_Il sidechain **è una delle tecniche più importanti per il mix e consente di abbassare un suono quando un altro sta suonando.**_

Il sidechain audio **è una tecnica di produzione musicale che consiste nell'utilizzare un segnale audio esterno come fonte di controllo per modificare il livello o l'effetto di un'altra traccia audio.** Ad esempio, è possibile utilizzare il segnale di un kick di una traccia di batteria per controllare il volume della traccia del basso o l'intensità dell'effetto di riverbero su una voce. Questa tecnica viene spesso utilizzata in generi musicali come la musica dance, l'elettronica e il pop per creare un effetto di pompare i bassi, in cui il volume dei bassi viene automaticamente ridotto ogni volta che entra in gioco la batteria o un altro elemento ritmico.

## Lato tecnico

Tecnicamente, il sidechain è un modo di gestire il segnale di un compressore. Nella compressione tradizionale, il compressore reagisce al volume del segnale su cui è applicato. Con il sidechain, invece, il compressore utilizza un **segnale esterno** come trigger per determinare quando e quanto comprimere il segnale audio principale.

### Ecco come funziona:

1. **Impostazione del segnale di sidechain**: si prende un segnale esterno, ad esempio una cassa, e lo si collega all'ingresso sidechain del compressore che sta agendo su un altro suono, come un basso o un pad. In questo caso, il compressore applicato al basso si attiverà ogni volta che rileva un "picco" dal segnale della cassa, abbassando temporaneamente il volume del basso.

2. **Parametro di Soglia (Threshold)**: come nella compressione standard, il parametro di soglia (threshold) determina il livello minimo di volume del segnale di sidechain per far scattare la compressione. Quando la cassa supera il livello di soglia impostato, il compressore abbassa il volume del segnale principale.

3. **Controllo della Riduzione del Guadagno (Gain Reduction)**: questo controllo definisce quanto il volume del segnale principale viene abbassato ogni volta che il sidechain si attiva. Maggiore è la riduzione, più il suono principale si "abbasserà" sotto il trigger del sidechain.

4. **Attacco e Rilascio (Attack e Release)**: l'attacco (attack) regola quanto velocemente la compressione si attiva quando il segnale di sidechain supera la soglia. Il rilascio (release) controlla quanto tempo impiega il compressore a rilasciare la compressione quando il segnale di sidechain scende sotto la soglia. Questi parametri sono cruciali per ottenere un effetto fluido e naturale.

### Utilizzo Pratico

In un contesto elettronico o di dance music, ad esempio, la cassa è usata come segnale di sidechain per comprimere elementi più stabili come il basso o i synth, creando quel tipico effetto di "pompaggio" (pumping), che dà ritmo e dinamica al brano. 

Il sidechain è quindi una configurazione di compressione "collegata" a un segnale esterno: è come dire al compressore di reagire non al suono su cui è applicato, ma a un altro suono di riferimento.

## Sidechain interno vs Sidechain esterno

Ogni compressore ha un **sidechain interno**, che è il circuito che usa per analizzare il segnale audio su cui è applicato. In una compressione standard, il compressore utilizza il segnale audio stesso (quello che sta processando) come fonte per determinare quando attivarsi.

### Sidechain interno vs. Sidechain esterno

1. **Sidechain interno**: È il lato del compressore che monitora il volume del segnale a cui il compressore è applicato. Se il volume di questo segnale supera la soglia impostata, il compressore si attiva e riduce il volume, seguendo le impostazioni di attack, release e ratio. In pratica, il compressore "ascolta" sempre il segnale su cui sta lavorando per decidere quando intervenire.

2. **Sidechain esterno**: Qui il compressore può ricevere un segnale da una sorgente esterna (ad esempio, una traccia di cassa o un'altra fonte). In questo caso, il compressore applica la riduzione del guadagno sul segnale su cui è applicato, ma reagisce in base ai picchi di volume del segnale esterno. Questo è il sidechain di cui si parla più comunemente quando si vuole creare l'effetto di "pompaggio" o "ducking".

### Uso del filtro nel sidechain interno

Alcuni compressori hanno anche un'opzione per applicare un **filtro EQ** nel sidechain interno. Ad esempio, si può usare un filtro passa-alto per evitare che il compressore reagisca a frequenze basse, rendendo la compressione più sensibile ai suoni di frequenza media e alta. Questo può essere utile quando si vuole una compressione meno aggressiva sui bassi, come nella compressione di una voce o di un mix stereo.


### In Sintesi

- **Sidechain interno**: usa il segnale stesso per attivare la compressione. È il modo in cui un compressore funziona di base.
- **Sidechain esterno**: utilizza un segnale separato per controllare il compressore, aprendo possibilità creative come il classico "pompaggio" in musica elettronica.

Quindi sì, tecnicamente ogni compressore ha un sidechain interno, ed è quello che utilizza per il suo funzionamento "normale".

Il sidechain è quindi semplicemente la "fonte di trigger", ovvero il segnale che il compressore ascolta per attivarsi.

## [[3. Resources/Music Production/Routing\|Routing]]

- Sidechain indipendente (per intervenire più pesantemente rispetto agli altri suoni)
- Sidechain generale
- Sidechain multibanda (splitting tracks)

## Tipi di Sidechain

_Alcuni compressori, tipo quello di Ableton permette di filtrare il suono sorgente, ad esempio il kick, così da prendere solo il transiente._

- **Compressore (dinamico)**
- **Volume shaping (statico)**
- **Automazione Volume (più preciso)**
	- Facendo l'automazione del volume tramite qualsiasi dispositivo, tipo l'utility di Ableton
- **Multibanda (più controllo)** (ad es. [[4. Archived/Projects Completed/ES - Content Creation (Elevenstep)/TRACKSPACER - Un Plugin Intelligente per DARE SPAZIO AI SUONI\|TRACKSPACER - Un Plugin Intelligente per DARE SPAZIO AI SUONI]])
	- Agire in modo diverso su ogni banda: High, Mid e Low


## Plug-in consigliati

- [[3. Resources/Music Production/Plugins/Duck\|Duck]]
- Volume shaper
- [[4. Archived/Projects Completed/ES - Content Creation (Elevenstep)/TRACKSPACER - Un Plugin Intelligente per DARE SPAZIO AI SUONI\|TRACKSPACER - Un Plugin Intelligente per DARE SPAZIO AI SUONI]]
- LFOTool (Xfer)
- Kickstart (Nicky Romero)
- Multiband Sidechain (Vengeance)
- OneKnob Pumper (Waves)

### Ableton

- Compressor
- Auto Pan
- Chain Shaper

## Strumenti utili per il Sidechain

- Oscilloscopio
- Analizzatore di frequenze 

## Related Notes

- [[3. Resources/Music Production/Processori di Dinamica\|Processori di Dinamica]]
- [[3. Resources/Music Production/Tecniche avanzate di Mixing\|Tecniche avanzate di Mixing]]
- [[3. Resources/Music Production/Sidechain vs Ducking\|Sidechain vs Ducking]]
