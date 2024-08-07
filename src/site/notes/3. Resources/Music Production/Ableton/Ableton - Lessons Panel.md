---
{"dg-publish":true,"permalink":"/3-resources/music-production/ableton/ableton-lessons-panel/","tags":["type/note"]}
---

Links:: [[3. Resources/Music Production/Ableton/Ableton\|Ableton]]

---
## Cos'è

Pannello delle lezioni come dice il nome stesso, permette di visualizzare alla propria destra, un pannello/finestra con una serie di lezioni, per l'utilizzo ad esempio Ableton. 

Ableton ci permette con una serie di operazioni, di creare il nostro "Pannello/Finestra Aiuto" per aggiungere quello che vogliamo: alcune info sul progetto, un tutorial su un dispositivo etc...

## Utilità

- Per aggiungere delle Info su un progetto che condividiamo
- Tutorial sull'utilizzo ad esempio di un Rack
- Aggiungere i nostri contatti


## Come procedere

### Mostrare il Pannello/Finestra

- Visualizza - Finestra Aiuto

### Creare una cartella

- Creare una cartella con esattamente il nome del progetto, ma aggiungendo alla fine il nome: Lessons

NomeProgetto Lessons

### Formato e risoluzione Immagini

- JPEG e PNG
- è consigliabile utilizzare una larghezza di **260 px** perché la dimensione minima della finestra è bene o male questa.


### Posizione dell'immagine

Per semplificare il percorso da inserire nel file di testo, puoi mettere tutte le immagine nella stessa cartella, cosi nel file di testo puoi mettere solo il nome dell'immagine, cosi: nome-immagine.png

Altrimenti se vuoi inserire delle immagini che si trovano su un'altra cartella, devi specificare anche il percorso, ad esempio: NOMEPERCORSO/nome-immagine.png

**ATTENZIONE**

Il nome dell'immagine deve essere senza spazi perché altrimenti non verrà visualizzata. È possibile utilizzare un trattino, ad es: Nome-Immagine.png

### Impostazione dello script

**programma per lo script**

puoi utilizzare anche il Blocco Note di Windows, altrimenti se vuoi un programma più adatto, puoi utilizzare ad es. Notepad++

**Nome script**

==Il nome dello script è importante, deve essere: **LessonsIT**, scritto esattamente cosi.==

**IT** (scritto in maiuscolo) è il codice per la lingua Italiano, nel caso vuoi inserire altre lingue. 
==Se ad esempio Ableton è impostato con lingua Italiano, utilizzarà il file LessonsIT.==
==Se ovviamente cambi la lingua in Inglese e il file LessonsEN non è presente, utilizzerà ugualmente un altro file Lessons==


**Percorso dello script**

Lo script deve essere salvato nella cartella **NomeProgetto-Lessons**


### Scripting

- **$Page** – Definisce il nome della Pagina
- **$TargetName** – Definisce il nome in codice della pagina. ==Deve stare sotto $Page==
- ***grassetto*** – Mettere un asterisco prima e dopo una parola o una frase lo rende in grassetto
- **Immagine** se l'immagine è nella stessa cartello dello script, basta scrivere solo il nome dell'immagine: nome-immagine.png
	- Altrimenti se vuoi inserire delle immagini che si trovano su un'altra cartella, devi specificare anche il percorso, ad esempio: NOMEPERCORSO/nome-immagine.png
- **$Link** www.JoshuaCasper.com `<http://www.joshuacasper.com>` – Qui il $Link creerà l'ipertesto (collegamento a qualcosa su Internet). Le parole o la frase subito dopo saranno il testo che sarà cliccabile. Il sito web tra il < > sarà la destinazione.
- **$Link** questa pagina. <**GotoPage**: Informazioni sull'EQ 8> - Questo imposta il collegamento interno tra le pagine della lezione. * ci saranno anche pulsanti di pagina avanti e pagina indietro nella parte inferiore del pannello, ma in caso di lezioni più grandi il collegamento interno è il migliore.
	- **IMPORTANTE!**
		- ==Per utilizzare GotoPage, devi utilizzare anche **$TargetName** che deve stare a sua volta, sotto $Page==


_nota: se all'interno del testo scrivi più di una volta: **$Page** andrà a creare sotto dei pulsanti, con Pagina succ./prec. senza mettere **GotoPage**_

## References

- Blog Joshua Casper
- [Ableton Tutorial: Codifica di un pannello di lezioni personalizzate - Joshua Casper](http://www.joshuacasper.com/ableton-tutorials/custom-lessons-panel/)
- [Ableton Tutorial: Coding a Custom Lessons Panel - YouTube](https://www.youtube.com/embed/0r9XG8GZKcs)



