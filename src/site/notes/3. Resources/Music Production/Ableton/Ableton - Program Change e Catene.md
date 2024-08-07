---
{"dg-publish":true,"permalink":"/3-resources/music-production/ableton/ableton-program-change-e-catene/"}
---

Links:: [[3. Resources/Music Production/Ableton/Ableton\|Ableton]]

---
## In cosa consiste

Cambiare preset di qualsiasi plugin/dispositivo durante un'esibizione dal vivo o in fase di produzione.

**Dal vivo**
cambiare più suoni o/e effetti con un controller

**Produzione**
rendere più articolato un suono, cambiandolo nel corso del tempo.


## Metodi

### 1. Program Change (SOLO INSTRUMENTS)
	  
- _Program Change, Bank Select e Sub-Bank Select_
- _Permette di cambiare non solo il preset ma anche i vari bank (se presenti)_

**Dove si trova**
- nella Vista Clip

**Plug-in Instruments**

- Sylenth
- Serum
	- Posizione del bank +1
	- Cambiare preset tramite un controller
		- Trovare e modificare il file: Serum.cfg
			- OS X: ~/Library/Preferences/
			- Windows: %APPDATA%\Roaming\Xfer\Serum
				- C:\Users\T-Eleven\AppData\Roaming\Xfer\Serum
	- Bug
		- Se il Serum è chiuso, il cambio dei preset non avviene e quando poi viene aperto da un errore, obbligandoti a ricaricarlo.
		- Lag se si sta utilizzando il Program Change.
- Massive
	- Il Massive ha (non ho avuto modo di provare gli altri) un sistema di program change integrato, con la quale è possibile trascinare solo i preset che si vogliono utilizzare. Oltre a questo, permette anche di salvare un Program Change per riutilizzarlo ovunque.
	- Quasi tutti i plug-in della Native Instruments hanno il Program Change al suo interno.
	- Su Ableton ad es. è possibile vedere i preset nella Vista Dispositivo sul plug-in stesso (come nell'immagine qui sotto).

- **Come utilizzarlo**
	- **Vista Arrangiamento**
		- è possibile avere un Program Change diverso per ogni clip, in questo modo quando Ableton andrà ad eseguire una di queste Clip, andrà a riprodurre un preset diverso.
		- per usare il Program Change dal vivo, lasciare le Clip vuote senza note nel punto esatto dove si vogliono effettuare i cambiamenti.
	- **Vista Session**
		- è possibile avere un Program Change diverso per ogni clip, in questo modo quando Ableton andrà ad eseguire una di queste Clip, andrà a riprodurre un preset diverso.
		- Il Program Change sulla Vista Session, è ottimo soprattutto per l'esibizione dal vivo. Ecco perché:
			- mettere in play una clip o/e lanciare una scena nel momento desiderato
			- le Clip o le scene lanciate, andranno a tempo in base al "Menu di Quantizzazione" Globale
- **Nota**
	- Su alcuni plug-in il Program Change potrebbe non funzionare o dare problemi
		- Cercare in rete il nome del plug-in accompagnato da "Program Change"

### 2. Utilizzare le catene di Ableton

- **Nota**
	- Questo metodo è più complesso e con un consumo maggiore sulle risorse (varia in base alle caratteristiche del PC e da quanti plug-in sono in uso).
- Questo metodo consiste nel duplicare il plug-in o/e dispositivo sulle Catene di un Rack. A differenza del primo metodo, qui possiamo utilizzare anche i plug-in/dispositivi audio, andando ad ottenere delle modulazioni articolate sul suono nel corso del progetto.
- **Rack**
	- Raggruppando un plugin/dispositivo è possibile creare velocemente un rack su quella selezione.
	- Oppure è possibile utilizzare i dispositivi "Audio Effect Rack" e "Instrument Rack"
- **Catene**
	- **Come visualizzare le Catene**
		- Mostra/Nascondi Elenco delle Catene sul Rack
		- Le Catene possono essere visualizzate anche nella Vista Session
	- **Nota**
		- Le catene in parole povere, sono delle tracce all'interno della traccia stessa.
		- Le catene permettono di utilizzare più plugin o/e dispositivi in parallelo o solo in un determinato momento.
		- Inoltre è possibile creare o duplicare una catena.
	- **Come procedere**
		- Se volessimo 3 suoni diversi durante un'esibizione dal vivo o in fase di produzione, dovremmo creare 3 catene con 3 impostazioni diverse.
		- Editor di Selezione di Catena
			- _Definire le zone di riproduzione delle Catene._
			  1. Spostare le zone dove nell'intervallo desiderato.
				- dopo aver spostato le zone è possibile utilizzare la funzione: "Distribuisci intervalli uniformemente"
			  2. Mappare il Selettore
				- Tramite un controller
				- Tramite automazione
			  3. Utilizzare le dissolvenze
				- Le dissolvenze permettono di effettuare una sfumatura tra una catena e l'altra più dolcemente.
			  4. Far suonare contemporaneamente più suoni
			- Nota
				- Se si nasconde l'Editor di Selezione di Catena, le modifiche fatte su quest'ultimo, verranno comunque eseguite.
		- Editor di Zone di Velocity
			- Tramite il valore della Velocity nella Vista Editor Clip, è possibile assegnare una catena diversa per una o più note
			- Trick
				- Utilizzando la nuove funzioni di Ableton 11 "Velocity Range" e "Randomize" è possibile randomizzare le catene sulle varie note.
		- Editor di Zone di Tasti
			- In questa vista, possiamo far suonare una catena solo su alcune note. Utile soprattutto se voglio distringere i vari strumenti su un determinato range di note, ad es. il basso su un'ottava, il lead su un'altra e cosi via.
	- **Tricks**
		Immagine di combinare tutti questi cambiamenti con gli editor anche con gli Audio Effects, ad es. mettere il riverbero solo su alcune note, mettere il saturator solo un certo valore di velocity ecc...



