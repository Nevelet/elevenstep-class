---
{"dg-publish":true,"permalink":"/3-resources/music-production/materiale-lezione/slide-live-set-in-ableton/"}
---



## Attrezzatura per Live Set

--
### Computer (MAC o WIN)
- Portatile
- CPU, RAM & Hard-Disk (meglio SSD)

--
### [[3. Resources/Music Production/Controller MIDI\|Controller MIDI]]
- Cos'è
	- **È un dispositivo elettronico che genera e trasmette messaggi MIDI invece di produrre suoni direttamente.**

--
- Tipi di Controller MIDI
	- **Tastiere MIDI:** Simili a tastiere tradizionali, ma inviano segnali MIDI.
	- **Pad controller:** Griglie di pad sensibili al tocco per triggerare suoni o effetti.
	- **Wind controller:** Simili a strumenti a fiato, ma generano segnali MIDI soffiandoci dentro.
	- **Knob controller:** Manopole rotanti per controllare parametri come volume o filtri.

--
### [[3. Resources/Music Production/Launchpad\|Launchpad]]
- Pensa a un Launchpad come a una **griglia di pulsanti o pad** sensibili al tocco, disposti in modo ordinato. Ogni pad può essere **assegnato a un suono diverso**, come un sample di batteria, un synth o una voce.

--
- Oltre ai pad, i Launchpad spesso includono **altri controlli** come:
	- **Knob:** Per regolare parametri come volume, filtro e pitch.
	- **Fader:** Per controllare il volume di diverse tracce o effetti.
	- **Pulsanti:** Per attivare funzioni come registrazione, loop e quantizzazione.

--
- **Ci sono molte opzioni disponibili sul mercato.** Alcuni modelli popolari includono:
	- **[Ableton Live Launchpad](https://www.ableton.com/en/products/controllers/launchpad/):** Un Launchpad versatile con una stretta integrazione con il software Ableton Live.
	- **Novation Launchpad Mini:** Un Launchpad compatto ed economico, ideale per principianti.
	- **[Akai Professional APC Mini](https://www.strumentimusicali.net/product_info.php/products_id/172055/akai-apc-mini-mkii.html):** Un Launchpad progettato specificamente per l'utilizzo con il software Ableton Live.
	- [Ricerca su Amazon.it](https://www.amazon.it/launchpad/s?k=launchpad)

--
### Tastiere MIDI
- Una **tastiera MIDI**, o **tastiera controller MIDI (In inglese: MIDI keyboard)**, è una periferica musicale che simula una tastiera di pianoforte

--
- Principali caratteristiche
	- **Tasti:** Solitamente sensibili alla dinamica (velocità di pressione) e alla aftertouch (pressione continuata dopo la pressione iniziale), per un controllo espressivo del suono.
	- **Controlli MIDI:** Manopole, pulsanti, fader e altri controlli per modulare parametri sonori come volume, timbro, effetti e altro ancora.
	- **Connettività:** USB, MIDI Out/In/Thru per collegarsi a computer, dispositivi hardware e reti MIDI.
	- **Alimentazione:** Tramite USB o alimentatore esterno a seconda del modello.

--
- Categorie
	- **Controller MIDI:** Progettate unicamente per inviare segnali MIDI e mancano di suoni integrati. Sono spesso più compatte e economiche.
	- **Tastiere Workstation:** Integrano sintetizzatori, suoni campionati e sequencer, offrendo una soluzione completa per la produzione musicale autonoma.

--
<!-- .element: style="font-size: 35px" -->
- Scegliere la tastiera MIDI
	- **Numero di tasti:** Da 25 a 88, a seconda del tipo di musica e dello stile di esecuzione.
	- **Sensibilità alla dinamica e aftertouch:** Per un controllo espressivo del suono.
	- **Controlli MIDI:** Quantità e tipologia di controlli per modulare parametri sonori.
	- **Suoni integrati:** Solo per tastiere workstation, valutare la qualità e la varietà dei suoni.
	- **Connettività:** USB, MIDI Out/In/Thru per la compatibilità con i dispositivi in uso.
	- **Software incluso:** Alcuni modelli includono software di produzione musicale o librerie di suoni.
	- **Prezzo:** Da modelli economici a soluzioni professionali più costose.

--
- Tastiere MIDI consigliate
	- [Tastiere MIDI 25 e 37 Tasti | Strumenti Musicali .net - I migliori prezzi ed offerte nel primo negozio di strumenti musicali online](https://www.strumentimusicali.net/default.php/cPath/50_144_456/tastiere-midi/tastiere-midi-25-e-37-tasti.html)
	- [ARTURIA MicroLab Black | Strumenti Musicali .net](https://www.strumentimusicali.net/product_info.php/products_id/98332/arturia-microlab-black.html)
	- [M-AUDIO Keystation Mini 32 MK3 | Strumenti Musicali .net](https://www.strumentimusicali.net/product_info.php/products_id/79271/m-audio-keystation-mini-32-mk3.html)
	- [AKAI MPK Mini Mk3 | Strumenti Musicali .net](https://www.strumentimusicali.net/product_info.php/products_id/121234/akai-mpk-mini-mk3.html?keywords=mpk+mini)

--
### Synths & Drum Machine
- [[3. Resources/Music Production/Componenti per Home Studio#Sintetizzatori\|Sintetizzatori]]
- [[3. Resources/Music Production/Componenti per Home Studio#Beat Machine\|Drum Machine]]

---
## Panoramica e Configurazione

--
### Le sezioni di Ableton  
- Vista Sessione  
- Vista Arrangiamento  
- Browser  
- Vista dettaglio delle tracce  
- Barra di controllo  

--
### Configurazione Audio  
- Scheda Audio  

--
### Configurazione MIDI  

--
#### Superficie di Controllo

- Cos'è
	- Le superfici di controllo sono script appositamente scritti che consentono il controllo tattile di Live attraverso parametri predefiniti.
- Superficie di controllo supportate: [Integrated hardware | Ableton](https://www.ableton.com/en/live/integrated-hardware/)
- Ingresso (Porta d'ingresso)
- Uscita (Porta di uscita)
- Modalità di Subentro

--
#### Sync & Link → MIDI Sync

- Cos'è
	- È il segnale che controlla il timing delle funzioni in un sintetizzatore. Il clock può essere fornito tramite MIDI o voltaggio di controllo.
- Il MIDI Sync include:
	- MIDI Clock (Tempo)
	- Start, Stop, Continue (continua da dove ti trovavi)
	- Song Position Pointer (SPP) (Puntatore della posizione del brano) (hr:MM;SS) or Measure: Beat

--
- Tipi di MIDI Sync
	- [MIDI beat clock o MIDI Clock](https://en.wikipedia.org/wiki/MIDI_beat_clock)
	- [MIDI timecode o MTC](https://en.wikipedia.org/wiki/MIDI_timecode)
		- ha una migliore risoluzione, ma non trasmette le informazione del tempo
		- MTC è effettivamente un codice temporale SMPTE trasmesso tramite un cavo MIDI

--
<!-- .element: style="font-size: 35px" -->
- Setting
	- Alcuni controller hanno delle impostazioni per decidere se ascoltare il MIDI Clock interno o quello esterno ad es. di Ableton. Ogni controller/tastiera, ha impostazioni diverse. 
		- dovrebbe trovarsi in generale, nella impostazioni globali (Global Settings) o MIDI Setting, poi MIDI clock e poi da lì indicare se external o internal
	- è possibile impostare il controller/tastiera in diverse modalità:
		- MIDI In (Slave)
		- Internal (Master)
		- MIDI IN/OUT (riceve e invia il clock ricevuto)
			- Auto (utilizza quello interno se non ci sono input di clock)

--
- MIDI Clock esterni
	- [midiclock⁺ – precision reference clock - E-RM](https://www.e-rm.de/midiclock/)

--
- Setting Controller & Tastiera MIDI


---
## Preparare le Tracce

--
### Le Tracce  
- Cos'è l'Audio e il MIDI  
- Cosa sono le tracce  
- Tipi di tracce  
- Differenza tra Traccia Audio, Midi e Tracce di Ritorno  
- Creare nuove tracce  
- Mixer delle tracce  

--
### Routing MIDI  
- Cos’è il Routing  
- Da MIDI a AUDIO  
- Routing nella vista dettaglio delle tracce  
- Routing Tracce
	- Input Tracce  
		- Tipo di ingresso   
		- Canale d’ingresso  
	- Output Tracce  
		- Tipo di uscita  

--
### Routing Audio  
- Input Tracce  
	- Tipo di ingresso   
	- Canale d’ingresso  
- Output Tracce  
	- Tipo di uscita  
	- Canale di uscita  

--
### Creare Tracce MIDI Instruments
- Aggiungere Plugin Instrument
- External Instrument per dispositivi hardware esterni (synth, campionatori, drum machine ecc.)
- Usare gli strumenti virtuali di Ableton (Drum Rack, Simpler, Operator, etc.).

--
### Creare Tracce Audio External
- MIC
- Guitar
- Altro

--
### Creare Tracce Internal
- Backing Tracks

--
### Traccia Session
- Pulsante stop clip
- Rimuovere Pulsante Stop
- Pulsante di Registrazione
- Inserire o Registrare Clip

---
## Warp

- Cos’è il WARP  
- Cosa attiva il WARP e le preferenze di auto-warp  
- BPM del Segmento vs BPM del progetto  
- Modalità di WARP  
- Impostazioni di WARP  
- Preferenze di WARP  
- Tasti Rapidi  
- Warping Multi-Clip

---

## Aggiungere Effetti (Audio & MIDI)

- Effetti su traccia (Insert)
	- Beat repeat
	- Auto-filter Bypass
	- Phaser-Flanger
	- Presets Audio Effect Rack
- Effetti con traccia di ritorno (Parallelo)

---
## Come avere un Pre-ascolto su Ableton

--
### Cue Out 
- Controllare le preferenze per abilitare e configurare le entrate audio
- PRO & CONTRO
	- solo un'uscita
	- solo per tutte le tracce
	- più immediato
	- preascolto del browser

--
### External Audio
 - PRO & CONTRO
	- tracce separate, ==quindi un'uscita diversa per ogni traccia==
	- effetti sull'uscita
	- più uscite
	- L'inconveniente è che introdurrà un po' di latenza

--
### Metodo con i Sends


---

## Preparare le Scene

- Preferenze "Record Warp Launch" 
- Assegnare i nomi giusti
- Dividere le scene (es. intro, verse, chorus ecc.)
- Tempo e Divisione Metrica della Scena

--
- Altre funzioni
	- Menù contestuale  
	- Inserisci Scena  
	- Cattura e Inserisci Scena  
	- Seleziona tutti gli Slot della Scena  
	- Annulla Lancio della Scena  
	- Al Lancio Seleziona Scena Successiva (Pref)  
	- Innesca Registrazione al Lancio (Pref)  

---
## Registrazione e Lancio Clip per Live Set

--
### Registrare nella Vista Sessione
- Tutte le tracce o solo quelle Armate
	- Innesca Registrazione al Lancio (Click destro su una scena) (sulle Preferenze si chiama Avvia Registrazione al Lancio Scena)
- Prepara Scena per Nuova Registrazione (tasto New. Visibile solo in modalità mappatura MIDI o Key)
- Quantizzazione in Registrazione

--
- Registrare le Automazioni
	- Arma Automazione
	- Solo su tracce armate (pref.)
	- Su tutte le tracce (pref.)
- Registrare dei Loop perfetti
- Registrare nella Vista Arrangiamento

--
- Tasti Rapidi con tastiera PC


---
## Clip

--
### Menu di Quantizzazione (Globale)
- Questo è **l'opzione più importante per la Vista Session** Perché aiuta ad **evitare errori ritmici durante la riproduzione delle Clip.**
	- Aspetta che finisca una misura stabilita
	- è possibile la quantizzazione di default per ogni clip nelle preferenze "Record, Warp, Launch"

--
<!-- .element: style="font-size: 35px" -->
### Follow Action (Azione seguente)  
- Cos’è il Follow Action  
- Azione A / B  
- Change dell'azione seguente (0-100%)  
- Azione seguente collegata (Linked e Unlinked)  
- Tempo dell'azione seguente o Moltiplicatore (in base a quale opzione si sceglie tra Linked e Unlinked)  
- Aggiustamenti avanti e indietro  
- Modalità di Lancio di default  
- Quantize (Quantizzazione della Clip)  
- Velocity  
- Fallow Action su scene  


---
## Mapping con Ableton

- Mapping Vista Sessione
	- Tasto arma automazione
	- Tasto registrazione sessione

--
- Mapping Effetti
	- Parametri filtri con controller MIDI

--
- Mapping Marcatori

---

## Mixing

- Mixing Volumi
- Limiter su Master

---
## Creare Rack avanzati per live set

--
<!-- .element: style="font-size: 35px" -->
- Automatismo effetti o/e strumenti
	- [How to use Ableton for live performaning (like Anomalie) | Part 1 - Setting up the basics - YouTube](https://youtu.be/0kGvSJiizTM)
	- è possibile creare delle automazioni del Chain Selector per attivare le catene con gli strumenti/effetti desiderati. È possibile farlo sia per effetti e sia per strumenti o entrambi.
	- se non si vuole preoccuparsi di cambiare gli effetti o/e gli strumenti in dal vivo, è possibile automatizzare questo passaggio.

--
<!-- .element: style="font-size: 35px" -->
- Automatismo effetti o/e strumenti
	- **Procedimento:** Creare una traccia MIDI per solo il segnale MIDI con il rack e le catene con la quale poi fare l'automazione del chain selector. Dopodiché, con l'External Instrument, inviare il MIDI nelle tracce con gli strumenti (plugin tipo Kontakt). Poi fare le automazioni nell'arrangiamento (è possibile anche mappare il chain selector). Se si vuole una cosa più ordinata, è possibile usare delle clip vuote con il nome "Intro", "Verse" ecc.

--
- Split Chain, Keys e Velocity


---
## Sessione di Live Set

- Fare pratica e prendere familiarità con Ableton


---
<!-- .element: style="font-size: 35px" -->
## Extra

- Salvataggio Template
- Crea Catena di Azioni Seguenti  
- Impatto sulle Prestazioni su ogni traccia  
- Alternare le due viste (Riprodurre in entrambe le viste)  
- Mappatura Vista Sessione  
- Display di stato della Traccia (cerchio nella tracce che indicano la durata della clip)  
- Torna all'Arrangiamento (tasto presente nell'arrangiamento per attivare le clip su quest'ultima vista.)  
- Abilita le Azioni seguenti Globalmente (tasto presente nella traccia master)
- Fade (nella vista clip)  
- I controlli di Preascolto (o Cueing) (Slider per passare da A a B)

---
