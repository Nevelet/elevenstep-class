---
{"dg-publish":true,"permalink":"/notes/convertitore-di-progetti/"}
---

Links:: [[Utility (Music Production)\|Utility (Music Production)]]

---
[Jukeblocks](https://convert.jukeblocks.io/)

## General Info

Il convertitore FLP/ALS è ancora in lavorazione! Non è perfetto e manca ancora delle funzionalità che vorrei includere. Di seguito è riportato un elenco di limitazioni note che si spera vengano risolte in futuro.

Esiste un limite di dimensione del file di 6 MB per gli utenti gratuiti.

Il convertitore creerà un file di progetto Ableton Live 9.7/10.1 o FL Studio 12.5.

L'opzione "Percorso relativo" cercherà i campioni nella stessa cartella in cui si trova, invece di utilizzare i percorsi dei file esistenti. Comodo per la collaborazione, se raccogli tutti i campioni in un'unica cartella.

L'automazione è attualmente supportata per i plug-in di terze parti e il fader del volume del mixer, ma la funzione è molto nuova, quindi potrebbero esserci dei bug.

Al momento non è disponibile alcun supporto per: traccia di ritorno/invio, rack di strumenti/effetti o Patcher. Se hai un synth nativo (come Operator o Harmor) nel tuo progetto, verrà impostato automaticamente su un synth Operator/3xOsc.

Ironia della sorte, attualmente non è possibile convertire da un file jukeblock/convertito, perché sono versioni ridotte a icona del file di progetto completo. Se salvi il progetto almeno una volta nella DAW, in seguito verrà convertito correttamente.


## ALS -> FLP

Se si dispone di audio con più marker di warp, il convertitore utilizzerà solo il tempo del primo marker di warp. (FL non ha warpmarker.)

Questo convertitore è stato realizzato pensando ad Ableton 10 e 11 e non funziona convertendo da Live 8 o versioni precedenti.
  

## FLP -> ALS

Gli FLP non memorizzano i bpm dei campioni nel file, quindi se hai campioni timestretched puoi scrivere "120bpm" o qualunque sia il tempo nel nome del canale.

I percorsi di esempio potrebbero non essere convertiti correttamente nelle versioni di FL Studio precedenti alla 20.7.2

Alcuni dei campioni FL stock/predefiniti non funzionano in Ableton.

È supportato solo FL Studio 12 e versioni successive. FL 11 potrebbe funzionare ma non l'ho testato a fondo.
  
## ALS -> ALS

Puoi eseguire il downgrade dei file di Ableton Live 11 a una versione precedente di Ableton come 10.1 o anche 9.7.

I plugin e le funzionalità esclusive di Ableton 11 non saranno ovviamente disponibili in 10 o 9. Nella maggior parte dei casi verranno ignorati nel file declassato.

Ableton 9 ha più limitazioni, come nessun supporto per plug-in VST3 o gruppi in gruppi, quindi verranno mantenuti solo i gruppi di livello superiore e tutte le tracce audio/midi all'interno diventeranno parte di quel gruppo.

Stranamente, Kontakt ripristinerà il plug-in in quanto può rilevare che viene aperto in una versione precedente di Ableton e non gli piace. Questo è l'unico plugin che ho trovato per farlo, ma potrebbero essercene altri. Alcuni parametri verranno ripristinati anche in Ableton 9.

