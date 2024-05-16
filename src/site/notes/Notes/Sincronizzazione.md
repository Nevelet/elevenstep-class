---
{"dg-publish":true,"permalink":"/notes/sincronizzazione/","tags":["type/note"]}
---

Links:: [[Audio\|Audio]], [[Notes/MIDI\|MIDI]]

---

## Diverse modalità

- **Slave:** prendono il tempo esternamente (riceve il clock external)
- **Master:** quello che comanda e decide il tempo (decidere qual è il click master, se deve essere quello presente dalla macchina o quello esterno, in quest'ultimo caso, la macchina diventare slave.) (internal clock)
- [Jam Sync](https://en.wikipedia.org/wiki/Jam_sync), significa seguire il tempo ad orecchio e sperare che tutto resti sincronizzato, ma il più delle volte non è cosi, perché le macchine non rimarranno sempre a tempo.  

## Tipi di Sync

- [[Notes/MIDI Sync\|MIDI Sync]]
- [[Notes/CV Trigger Sync\|CV Trigger Sync]]
- [DIN sync](https://en.wikipedia.org/wiki/DIN_sync)

## Informazioni necessarie per il Sync

**Per sincronizzare bene, è necessario avere:**
- Speed info (seconds, frames, BPM)
- Start, Stop, Continue (continua da dove ti trovavi)
- Song Position Pointer (SPP) (Puntatore della posizione del brano) (hr:MM;SS) or Measure: Beat

_[[Notes/CV Trigger Sync\|CV Trigger Sync]], è sprovvisto di queste informazioni, il che può portare a problemi di sincronizzazione tra dispositivi_


## 🔗 Related Notes

- [[Sincronizzare più Computer e Strumenti\|Sincronizzare più Computer e Strumenti]]
- [[Notes/Timecode\|Timecode]]


## 📚 References

- 

**Video che mostrano le differenza della sincronizzazione**
- [How to sync using MIDI Sync or Trigger Sync? - YouTube](https://youtu.be/0_TxXDjn5wY)
- [CLOCKstep:MULTI - Synchronize (MIDI Clock, CV Trigger Sync, DAW Sync, Sample Accurate Clock) - YouTube](https://www.youtube.com/watch?v=mZt7jjksR1g)