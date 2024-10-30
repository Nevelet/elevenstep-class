---
{"dg-publish":true,"permalink":"/3-resources/music-production/computer-per-l-audio/","tags":["type/note"]}
---

Links:: [[3. Resources/General Knowledge/Computer\|Computer]], [[3. Resources/Music Production/Componenti per Home Studio\|Componenti per Home Studio]]

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

![Serial vs parallel processing CPU.png](/img/user/3.%20Resources/Images/Serial%20vs%20parallel%20processing%20CPU.png)


## Portatili per l'audio

Un buon portatile per la produzione audio dovrebbe avere caratteristiche come:

1. **Processore potente**: meglio un Intel i7/i9 o AMD Ryzen 7/9, poiché i software audio (come Ableton) possono richiedere molta potenza di calcolo.
2. **RAM**: almeno 16 GB, ma 32 GB è l'ideale per progetti con molti plugin.
3. **Archiviazione SSD**: per una velocità di caricamento rapida; un SSD da almeno 512 GB è una buona base.
4. **Schermo di qualità**: non è necessario l’alta risoluzione, ma un display chiaro e di buone dimensioni aiuta nel lavoro di mixaggio.
5. **Connettività**: porte USB-C e Thunderbolt sono preferibili per collegare facilmente interfacce audio esterne.

### Fascia alta

- **MacBook Pro (14" o 16", con chip M2 Pro o M2 Max)**: i chip M2 Pro e Max gestiscono ottimamente carichi pesanti, e i MacBook Pro sono molto silenziosi e ben ventilati. Ableton è ottimizzato per macOS, e i tempi di risposta sono eccellenti anche con progetti complessi.
- **Dell XPS 15 (con processore Intel i7/i9 e almeno 32 GB di RAM)**: questa serie offre una grande potenza e flessibilità, uno schermo ben bilanciato e un buon sistema di raffreddamento. Scegli una configurazione con GPU dedicata (come NVIDIA) se usi anche plugin visivi o video.
- **Razer Blade 15 (con processore Intel i7/i9 e 32 GB di RAM)**: benché sia noto come laptop da gaming, il Blade 15 è ottimo per audio grazie alla potenza e alla qualità costruttiva, oltre alla disponibilità di porte Thunderbolt e USB per l’integrazione delle periferiche.
- **ASUS ProArt StudioBook 16**: progettato per creativi, ha un sistema di raffreddamento eccellente, processori AMD Ryzen 9 o Intel i9 e GPU NVIDIA, ideale se lavori anche con video. Supporta storage fino a 1-2 TB SSD, che è ottimo per progetti con tracce audio di grandi dimensioni.

### Prezzi più contenuti

- **Apple MacBook Air M1 (13")**: la versione con chip M1 è ancora molto valida per l'audio e gestisce Ableton bene, anche se non come i modelli Pro. Con 16 GB di RAM, regge più tracce audio rispetto alla configurazione base. È anche molto silenzioso e ha una batteria ottima.
- **Acer Swift X 14 (con AMD Ryzen 7 e 16 GB di RAM)**: economico e potente, grazie al Ryzen 7 e alla GPU NVIDIA, offre buone performance per il prezzo. Supporta molti plugin, anche se potrebbe avere qualche limite con progetti molto grandi.
- **HP Pavilion 15 (con Intel i5/i7 e 16 GB di RAM)**: un'opzione affidabile a costo moderato. L'i7 è preferibile per maggior potenza e velocità con Ableton, ma anche la versione con i5 va bene se il budget è ridotto.
- **Lenovo IdeaPad 5 (con AMD Ryzen 5/7 e 16 GB di RAM)**: un’ottima opzione economica, grazie al Ryzen 5 o 7. È sorprendentemente potente e abbastanza versatile da reggere Ableton, anche se potresti dover evitare progetti audio estremamente complessi.


### References: 

- [Top Picks for the Best Laptop for Music Production | Slate Digital](https://slatedigital.com/best-laptop-for-music-production/)
- [Acer Swift X 14 music ableton - Cerca con Google](https://www.google.com/search?q=Acer+Swift+X+14+music+ableton)

## PC fisso



### References:

- [The best desktop PC ingredients for Ableton? - Ableton Forum](https://forum.ableton.com/viewtopic.php?t=247206)
- [What pc is good enough for Ableton? : r/ableton](https://www.reddit.com/r/ableton/comments/15kq946/what_pc_is_good_enough_for_ableton/)


---
## 📚 References

- [UNA CONFIGURAZIONE PC PER PROFESSIONISTI AUDIO CON 500 EURO? - YouTube](https://www.youtube.com/watch?v=paOHtccICyg)
- [The Best Computer for Music Production - What's Needed and Why! - YouTube](https://www.youtube.com/watch?v=ayt8-s77cQs)


## Resources

- [Home - UserBenchmark](https://www.userbenchmark.com/)