---
{"dg-publish":true,"permalink":"/3-resources/music-production/sincronizzazione/","tags":["type/note"]}
---

Links:: [[3. Resources/General Knowledge/Audio\|Audio]], [[3. Resources/Music Production/MIDI\|MIDI]]

---

## Diverse modalità

- **Slave:** prendono il tempo esternamente (riceve il clock external)
- **Master:** quello che comanda e decide il tempo (decidere qual è il click master, se deve essere quello presente dalla macchina o quello esterno, in quest'ultimo caso, la macchina diventare slave.) (internal clock)
- [Jam Sync](https://en.wikipedia.org/wiki/Jam_sync), significa seguire il tempo ad orecchio e sperare che tutto resti sincronizzato, ma il più delle volte non è cosi, perché le macchine non rimarranno sempre a tempo.  

## Tipi di Sync

- [[3. Resources/Music Production/MIDI Sync\|MIDI Sync]]
- [[3. Resources/Music Production/CV Trigger Sync\|CV Trigger Sync]]
- [DIN sync](https://en.wikipedia.org/wiki/DIN_sync)

## Informazioni necessarie per il Sync

**Per sincronizzare bene, è necessario avere:**
- Speed info (seconds, frames, BPM)
- Start, Stop, Continue (continua da dove ti trovavi)
- Song Position Pointer (SPP) (Puntatore della posizione del brano) (hr:MM;SS) or Measure: Beat

_[[3. Resources/Music Production/CV Trigger Sync\|CV Trigger Sync]], è sprovvisto di queste informazioni, il che può portare a problemi di sincronizzazione tra dispositivi_


## 🔗 Related Notes

- [[3. Resources/Tech/Sincronizzare più Computer e Strumenti\|Sincronizzare più Computer e Strumenti]]
- [[3. Resources/Music Production/Timecode\|Timecode]]


## 📚 References

- 

**Video che mostrano le differenza della sincronizzazione**
- [How to sync using MIDI Sync or Trigger Sync? - YouTube](https://youtu.be/0_TxXDjn5wY)
- [CLOCKstep:MULTI - Synchronize (MIDI Clock, CV Trigger Sync, DAW Sync, Sample Accurate Clock) - YouTube](https://www.youtube.com/watch?v=mZt7jjksR1g)
