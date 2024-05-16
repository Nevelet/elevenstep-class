---
{"dg-publish":true,"permalink":"/notes/ableton/ableton-routing-midi-tracce-input-and-output/","tags":["type/note"]}
---

Links:: [[Notes/Ableton/Ableton - Routing\|Ableton - Routing]] [[Notes/Routing\|Routing]], [[Tracce\|Tracce]]

---

instradamento, percorso
## Input (ingresso)

Input è solo MIDI

### Tipo di ingresso

- External Input
	- All Ins
	- Computer Keyboard
	- [[Notes/Controller MIDI\|Controller MIDI]] specifico
	- Configure
- Internal Input
	- Output di una nuova traccia MIDI

**External Input:** Utilizzare una tastiere midi in particolare piuttosto di All Ins ci permette di mandare il segnale MIDI solo di una determinata tastiera. 


### Canale d'ingresso

- External MIDI (Controller MIDI)
	- [[Notes/Canali MIDI\|Canali MIDI]]
- Internal MIDI (Tracce MIDI Ableton)
	- Pre FX
	- Post FX
	- Post Mixer (sezione mixer: ON/OFF traccia)
- Internal MIDI (Plugin)
	- Pre FX
	- Post FX
	- "Nome plugin"

## Output (uscita)

Abbiamo sia un'uscita MIDI e sia un'uscita AUDIO. Per avere un'uscita MIDI, non ci deve essere nessun instrument e effect audio. 
### Tipo di Uscita

- External Output
	- Ext. Out (AUDIO)
- Internal Output
	- Master (AUDIO)
	- Send only (AUDIO)
	- MIDI
		- Input MIDI su Traccia Audio (Sidechain plug-in o dispositivo) (Solo se nella traccia MIDI è presente un dispositivo Instrument o/e effetto audio)
		- Input MIDI su Traccia MIDI (Solo se nella traccia MIDI NON è presente un dispositivo Instrument o/e effetto audio)
			- Track In: Input traccia (per ascoltare, dobbiamo attivare il monitoraggio)
			- Input Plugin con i suoi corrispettivi canali MIDI

