---
{"dg-publish":true,"permalink":"/3-resources/music-production/midi-sync/","tags":["type/note"]}
---

Links:: [[3. Resources/Music Production/MIDI\|MIDI]], [[3. Resources/Music Production/Sincronizzazione\|Sincronizzazione]]

---

## Descrizione

- **Clock** – Clock è il segnale che controlla il timing delle funzioni in un sintetizzatore. Il clock può essere fornito tramite [MIDI](https://blog.landr.com/synth-terms/#MIDI) o [voltaggio di controllo](https://blog.landr.com/synth-terms/#control-voltage).
- il MIDI Clock non è quella cosa che dice ai vari controller, ehi guarda che io suono a 120 BPM e tutto voi dovete seguire me con questo tempo. Ma è un impulso periodico che viene inviato tramite cavo MIDI al master o alla DAW
- Quindi il MIDI clock non invia il BPM, ma le macchine indovinano il tempo seguendo questi impulsi, questi tick e da li ricostruiscono il BPM giusto. 
- i vecchi controller MIDI, non avevano il proprio clock, ma si affidano a uno esterno. Altrimenti non funzionavano. 
- la maggior parte dei sintetizzatore hardware, hanno un sistema che riescono a passare tra clock midi interno quando non ricevano uno esterno.
- Clock In/Out: Alcuni strumenti, possono inviare e ricevere quel tempo su altre macchine, un po' come fa il [[3. Resources/Music Production/MIDI IN, OUT e Thru\|MIDI Thru]]




## Messaggi di Sync 

**Il MIDI Sync include:**
- MIDI Clock (Tempo)
- Start, Stop, Continue (continua da dove ti trovavi)
- Song Position Pointer (SPP) (Puntatore della posizione del brano) (hr:MM;SS) or Measure: Beat

## Tipi di MIDI Sync

- [MIDI beat clock o MIDI Clock](https://en.wikipedia.org/wiki/MIDI_beat_clock)
- [MIDI timecode o MTC](https://en.wikipedia.org/wiki/MIDI_timecode)
	- ha una migliore risoluzione, ma non trasmette le informazione del tempo
	- MTC è effettivamente un codice temporale SMPTE trasmesso tramite un cavo MIDI


## Setting

- Alcuni controller hanno delle impostazioni per decidere se ascoltare il MIDI Clock interno o quello esterno ad es. di Ableton. Ogni controller/tastiera, ha impostazioni diverse. 
	- dovrebbe trovarsi in generale, nella impostazioni globali (Global Settings) o MIDI Setting, poi MIDI clock e poi da lì indicare se external o internal
- è possibile impostare il controller/tastiera in diverse modalità:
	- MIDI In (Slave)
	- Internal (Master)
	- MIDI IN/OUT (riceve e invia il clock ricevuto)
	- Auto (utilizza quello interno se non ci sono input di clock)


## MIDI Clock esterni

- MIDI Clock
	- [midiclock⁺ – precision reference clock - E-RM](https://www.e-rm.de/midiclock/)
	- [This is How I Do MIDI Sync in the Studio (E-RM Midiclock) - YouTube](https://www.youtube.com/watch?v=c9SPRVWVShM)




## Related Notes

- [[3. Resources/General Knowledge/Ableton - Sincronizzazione tramite MIDI\|Ableton - Sincronizzazione tramite MIDI]]



## References

- [MIDI Clock and your DAW: How To Sync Your Synths - YouTube](https://www.youtube.com/watch?v=EjrvApZgMZo)
- [How to Sync your Synthesizer Setup using MIDI - YouTube](https://www.youtube.com/watch?v=v4ZeXXpRC0Q)
- [Using MIDI Clock to Sync Synths, DAWs, & Devices – Daniel Fisher + Jacob Dupre - YouTube](https://www.youtube.com/watch?v=kurOg6Fij-s)
- [How to sync using MIDI Sync or Trigger Sync? - YouTube](https://www.youtube.com/watch?v=0_TxXDjn5wY)
- [Midi Sync - Songstuff](https://www.songstuff.com/recording/article/midi_sync/)



