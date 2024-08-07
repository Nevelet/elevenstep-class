---
{"dg-publish":true,"permalink":"/3-resources/music-production/ableton/ableton-warp/","tags":["type/note"]}
---

Links:: [[3. Resources/Music Production/Ableton/Ableton\|Ableton]], [[3. Resources/Music Production/Music Production\|Music Production]] 

---
## Cos'è il Warp

_Modifiche temporali al campione_
Il WARP permette di adattare il campione con il suo tempo originale, nel tempo da te scelto, senza alterarne il tono. In base ad alcuni algoritmi poi, è possibile mantenere alcune caratteristiche del campione scelto, come ad esempio: i transienti e il pitch.

Il WARP quindi andrà a stretchare il campione grazie ai suoni marcatori, che potrai cambiare, spostare o aggiungere. Se i cambiamenti di tempo sono esagerati, il campione verrà allungato troppo e di conseguenza, il risultato in base all'algoritmo selezionato, sarà metallico e con uno spettro di frequenze diverso.
- Marcatore Transiente
- Marcatori di Warp

Il WARP è una parte indispensabile soprattutto per i loop, brani completi e tracce vocali
Disattiva il WARP soprattutto su campioni ritmici corti: kick, percussioni, effetti sonori ecc...

L'algoritmo di [[Warp Ableton\|Warp]] presente su Ableton è probabilmente ciò che lo rende superiore rispetto agli software, permettendo di allungare, accorciare l'audio in diversi modi e con un compromesso più che accettabile. —  [Ableton Live - Wikipedia](https://it.wikipedia.org/wiki/Ableton_Live) 

---

## Attivare il Warp

Il WARP si attiva nella Vista Clip della Traccia Audio, riquadro: "Scheda del Campione".

Senza Warp attivo, non è possibile eseguire alcune operazioni:
- Envelopes
- Stretch tempo

---

## BPM del Segmento

- Ableton di solito effettua un Auto-Warp, restituendo un presunto tempo del del campione caricato. Ovviamente se si conosce il BPM del file, è possibile digitarlo in questo riquadro o aggiustare quello che viene identificato.

---

## Modalità di Warp

algoritmi di timestretching

_Queste modalità possono essere impostate di default nelle preferenze (Record, Warp e Launch)._
Live offre diverse modalità di time-stretching (adattamento del tempo) per trattare ogni tipo di materiale audio.
Con queste modalità oltre ad ottenere un compromesso accettabile mantenendo bene o male la stessa qualità, è possibile abusarne per ottenere artefatti interessanti.

### Beats
Beats è più adatto per i campioni ritmici, ad esempio: loop di percussioni, loop di batteria ecc...
Il processo di granulazione è ottimizzato per preservare i transienti nel materiale audio.
Noterai inoltre che a differenze delle altre modalità, ==il segnale non viene stretchato, ma verrà ripetuto== in base alla modalità di loop scelta.

**Preserve (Risoluzione della Granularità)**
Per mantenere specifiche divisioni di beat è possibile selezionare quelle che trovi nell'elenco.
Per risultati più precisi, è consigliabile utilizzare "Transients" questo andrà a stretchare tra un transiente e l'altro, sfruttando appunto i Marcatori di Transienti, che vengono generati in automatico, ovviamente puoi anche eliminarli, aggiungerli o modificarli.

**Modalità di Loop dei Transienti**
No Loop:
![Warp_-_Beats_(No_Loop)_1630682700429_0.jpg](/img/user/3.%20Resources/Images/Warp_-_Beats_(No_Loop)_1630682700429_0.jpg)
Viene stretchato ad ogni segmento senza andare in Loop tra i vari Marcatori
Il campione viene tagliuzzato in base soprattutto ai Marcatori, tra l'inizio e la fine di ogni segmento, il campione non andrà il Loop, ma verrà soltanto stretchato.
Se non ci sono Marcatori di Transienti, il campione suonerà con la sua durata originale fino al prossimo Marcatore.

🌀 Loop Avanti:
![Warp_-_Beats_(Loop_Avanti)_1630682667706_0.jpg](/img/user/3.%20Resources/Images/Warp_-_Beats_(Loop_Avanti)_1630682667706_0.jpg)

Ogni segmento audio fra i transienti suona fino alla propria fine. Poi il
playback torna a un punto di zero-crossing vicino al centro del segmento e continua in loop fino al tempo del transiente successivo.

🌀 Loop Avanti-Indietro:
![Warp_-_Beats_(Loop_Avanti_e_Indietro)_1630682562961_0.jpg](/img/user/3.%20Resources/Images/Warp_-_Beats_(Loop_Avanti_e_Indietro)_1630682562961_0.jpg)
Ogni segmento audio fra i transienti suona fino alla propria fine.
Quindi il playback si inverte fino a quando non raggiunge un punto di zero-crossing vicino al centro del segmento e poi procede di nuovo in avanti verso la fine del segmento. Questo comportamento continua fino al tempo del transiente successivo. Questa modalità, in combinazione con la scelta "Preserva Transienti", può spesso produrre un'ottima qualità nei tempi più lenti.

**Inviluppo dei Transienti**
Se si lascia il valore di default (10) non ci sarà nessun decadimento del volume a ciascun segmento. Abbassandolo invece, si possono ottenere effetti ritmici più accentuati.

### Tones
Questa modalità di Warp è ottima per lo stretching di materiale composto da toni ben definiti e chiari, ad esempio: voci, strumenti monofonici e linee di basso.

**Grain Size**
Questo determina la dimensione dei granuli. Effettua un controllo approssimativo sulla dimensione dei granuli usati.
La dimensione effettiva è definita dal segnale

È più indicato un Grain Size (Dimensione dei Granuli) più basso, se il segnale ha una definizione chiara del pitch.
Invece dimensioni più alte, contribuiscono ad evitare artefatti quando il segnale ha un pitch poco chiaro, ma ci possono essere ripetizioni udibili.


### Texture
- Texture è ottimo quando il segnale ha una sonorità dal profilo di pitch indefinibile (ad es. musica orchestrale polifonica, rumore, pad di atmosfera, etc.).
- Inoltre è più orientato per ottenere effetti particolari, manipolando i vari controlli di questa modalità.
- **Grain Size**
	- Come per la modalità Tones, il Grain Size (o Dimensione dei Granuli) stabilisce la dimensione dei granuli usati, con l'unica differenza Ableton non considera le caratteristiche del segnale originale.
- **Flux**
	- Flux introduce casualità nel processamento del campione. A valori maggiori corrisponde una casualità maggiore.



### Re-Pitch
- La modalità Re-Pitch non va ad ampliare o a ridurre il tempo del campione, quindi invece di stretchare, Ableton interverrà sulla velocità del playback, con la conseguenza di un cambio di pitch. Questo è ciò che accade con i giradischi, dato che hanno una velocità variabile, danno la possibilità al DJ di mettere a tempo due brani. Stessa cosa con i campionatori tradizionali.
- I controlli Transpose e Detune non ha effetto nella modalità Re-Pitch.



### Complex
- La modalità Complex è progettato per i segnali complessi che uniscono le proprietà delle altre modalità di Warp.
- Complex è adatto quindi per intere composizioni, che comprendono, appunto: beats (battiti), tones (timbri sonori) e textures (trame indefinite).
- Questa modalità a differenze delle altre, richiede un consumo della CPU maggiore, soprattutto se viene utilizzata su più campioni.


### Complex Pro
- Complex Pro è una variante dell'algoritmo Complex, dando però risultati migliori (anche se con un maggior uso della CPU).
- Come la modalità Complex, la Complex Pro funziona particolarmente bene con trame polifoniche o con intere composizioni.
- Il cursore Formanti regola il grado di compensazione delle formanti del campione durante le trasposizioni. Al 100% le formanti originali vengono preservate, permettendo grandi cambiamenti di trasposizione pur mantenendo la qualità tonale originale del campione.
- Nota: questo cursore non ha alcun effetto se il campione viene riprodotto "non trasposto".

---
## Impostazioni Warp

### Inserisci/Elimina

- Marcatore/i di Warp
- Marcatore/i di Transienti
- Resetta Transienti


### Auto-Warp (Warp da qui...)

_Ovviamente queste opzioni in certe situazioni possono non essere ottime, per un warp più accurato, è necessario intervenire manualmente, aggiungendo o/e spostando i marcatori._

**Warp da qui**
- Warp da qui applica l'algoritmo di Auto-Warp sul materiale posto alla destra del marcatore selezionato.

**Warp da qui (avvia a BPM del progetto)**
- Warp da qui (avvia a ...) induce l'Auto-Warp a usare il tempo del Live Set corrente come punto di partenza per il tracciamento del tempo. In questo caso, la "strategia" è come segue: 
	- 1. Disattivate l'interruttore Warp della clip, in modo che suoni senza warping;
	- 2. Utilizzate il pulsante Tap Tempo (batti tempo) della Barra di Controllo per scandire il tempo, facendo così in modo che il tempo del Live Set combaci con quello della clip;
	- Attivate di nuovo il warping e usate il comando Warp da qui (avvia a ...) per dire all’Auto-Warp di usare come riferimento il tempo da voi scandito.

**Warp da qui diretto** 
- Warp da qui (diretto) dice all'Auto-Warp che questa è una clip senza variazioni di tempo (comuni nelle composizioni prodotte elettronicamente). In questo caso, l'Auto-Warp imposta un singolo Marcatore Warp, derivato dalla sua interpretazione del tempo originale del file.
{ #odzvsb}

 
**Warp (BPM del progetto) da qui**
- Warp ... BPM da qui imposta anch'esso un singolo Marcatore Warp, ma, in questo caso, l'Auto-Warp viene forzato a interpretare la clip come esattamente combaciante con il tempo del Live Set. Ciò è utile nei casi in cui conoscete l'esatto valore di BPM di un lavoro prodotto elettronicamente e siete in grado di digitarlo nella Barra di Controllo prima di applicare il warping.

**Warp campione come loop di ... Misure/Beat**
- Funziona molto bene per i loop percussivi, sul resto è un po' scomodo.
- È possibile utilizzare questa funzione anche soltanto su parte selezionata



### Dimezza-Raddoppia
- Permette di Raddoppiare il tempo

---

## Preferenze Warp
### Warp/Fades
- Loop/Warp dei Campioni Corti
- Loop/Warp dei Campioni Lunghi
- Modalità Warp di default
- Dissolvenze agli estremi delle Clip

### File di Analisi

---

## Tasti Rapidi

---

## Extra

- Warping Multi-Clip


## Notes

Complex e Complex Pro sono fondamentalmente algoritmi di timestretching [[3. Resources/Music Production/zplane\|zplane]] Elastique con licenza (Complex è Elastique 2, Complex Pro è Elastique 3) - molte altre DAW usano gli stessi. Questi non sono stati realizzati dall'equipaggio di Ableton. Le vecchie modalità di timestretching utilizzano fondamentalmente solo la sintesi granulare (tipo di algoritmo PSOLA) che viene utilizzata anche in molti prodotti diversi con diversi tipi di implementazione.


## Related Notes

- [[3. Resources/Music Production/Ableton/Mettere a tempo su Ableton\|Mettere a tempo su Ableton]]
- [[3. Resources/General Knowledge/Time Stretching\|Timestretching]]

