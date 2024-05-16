---
{"dg-publish":true,"permalink":"/notes/computer-per-l-audio/","tags":["type/note"]}
---

Links:: [[Computer\|Computer]], [[Notes/Componenti per Home Studio\|Componenti per Home Studio]]

---

## 📝 Notes

- serve tanto single core
- latenze più basse possibili
- l'audio digitale richiede molto refresh continuamente
- quindi tutti la maggior parte dei processi, andranno su un singolo core. 
- addirittura più core ci sono, più latenze si creeranno perché il flusso dati seguirà più strade
- per l'audio meglio mantenersi semplici, sarebbe meglio senza scheda video
- la scheda audio integrata, sarebbe anche disattivarla completamente, sempre per evitare di creare conflitti o problemi con driver. Quindi restare minimal.
- sarà un pc simile ad un pc da gaming, ma senza scheda video. Ovviamente si può anche installare successivamente una scheda video dedicata, e può diventare una macchina multiuso 
- CPU
	- [Intel® Core™ i5-12600, processore desktop, per sistemi desktop cache 18M, fino a 4,80 GHz : Amazon.it: Informatica](https://www.amazon.it/Intel-Core-i5-12600-Processore-BX8071512600/dp/B09MDD882B)
	- l'elaborazione audio non richiede processori multi thread (Processore multicore) 
	- i5 serie 12, sono molto buoni. Tranne la serie K, perché la connessione tra i vari core è più corta e quindi va a ridurre il passaggio dei dati tra i cori, per via del ring basso 
		- i5 12400 o se vogliamo il massimo il 12600. 
		- per il gaming non è ottimo
	- AMD Ryzen con scheda video integrata.
		- per alcuni usi non sono il massimo, ma per l'audio si, perché hanno una struttura unica
	- è meglio avere una CPU a 6 core con single core veloci, piuttosto che a 8 core ma lente.
	- Ci sono core di efficienza (E-core) e core di prestazioni (P-core)
	- [CPU UserBenchmarks - 1440 Processors Compared](https://cpu.userbenchmark.com/)
- RAM
	- [Corsair Vengeance LPX16GB DDR4 3600 Memoria Desktop, ‎Nero : Amazon.it: Informatica](https://www.amazon.it/Corsair-VENGEANCELPX16GB-Pc4-28800-C181-35V-Desktop/dp/B07RM39V5F/)
	- RAM a bassa latenza
	- bisogna assicurarsi che la RAM sia stabile in Gear 1 e che non si setti in Gear 2. Inoltre che sia in command rate 1
	- non ci interessa la banda passante
	- il processore i5 12600, non reggeva il 3600 MHz della ram, e allora è possibile scendere a 3400 MHz in Gear 1, Command Rate 1N e latenze più basse possibili.
	- Timing della RAM
		- Command Rate
		- tCL, tRCD, tRP, tRAS, tRFC
- Scheda Madre
	- [MSI PRO B660M-A DDR4, Scheda Madre Micro-ATX - Supporta i processori Intel 12th Gen Core, LGA 1700 - DDR4, 2x PCIe x16 slots x M.2 Gen4, 2.5G LAN : Amazon.it: Informatica](https://www.amazon.it/MSI-B660M-Scheda-Madre-Micro-ATX/dp/B09NTMRRTL/)
- Alimentatore
	- l'alimentatore è uno dei più importanti, e bisogna sceglierne uno che riesca a filtrare bene l'elettricità. 
	- deve efficiente 
	- con la configurazione sopra, va bene anche un alimentatore da 400W
- Dischi di memoria
	- meglio SSD e NVMe 
	- separare il disco di sistema con quello delle librerie 

editing video invece, fa molto affidamento all'elaborazione parallela, multi core

![[Serial vs parallel processing CPU.png\|Serial vs parallel processing CPU.png]]



---
## 📚 References

- [UNA CONFIGURAZIONE PC PER PROFESSIONISTI AUDIO CON 500 EURO? - YouTube](https://www.youtube.com/watch?v=paOHtccICyg)
- [The Best Computer for Music Production - What's Needed and Why! - YouTube](https://www.youtube.com/watch?v=ayt8-s77cQs)


## Resources

- [Home - UserBenchmark](https://www.userbenchmark.com/)