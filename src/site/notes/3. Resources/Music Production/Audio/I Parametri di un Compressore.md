---
{"dg-publish":true,"permalink":"/3-resources/music-production/audio/i-parametri-di-un-compressore/"}
---

Links:: [[3. Resources/Music Production/Audio/Compressore\|Compressore]]

---
**I parametri fondamentali di un compressore audio sono:**
1. **Threshold:** il livello di volume a cui il compressore inizia ad agire.
2. **Ratio:** la quantità di riduzione del volume applicata dal compressore quando il segnale supera la soglia.
3. **Attack time:** il tempo che il compressore impiega per agire sul segnale dopo che la soglia è stata superata.
4. **Release time:** il tempo che il compressore impiega per smettere di agire sul segnale dopo che la soglia non è più stata superata.
5. **Knee:** la forma in cui viene applicata la riduzione del volume dal compressore, cioè se avviene gradualmente o bruscamente.
6. **Make-up gain:** l'aumento del volume applicato al segnale dopo essere stato compresso, per riportarlo al livello originale.
7. **[[3. Resources/Music Production/Sidechain\|Sidechain]] input:** permette di controllare l'azione del compressore su un altro segnale audio, ad esempio per far risaltare una voce rispetto alla musica di sottofondo.


### Threshold (Soglia)
![image_1630097374952_0.png](/img/user/3.%20Resources/Attachments/image_1630097374952_0.png)



### La Ratio (Rapporto)
![image_1630097479969_0.png](/img/user/3.%20Resources/Attachments/image_1630097479969_0.png)

La ratio di un compressore audio indica la quantità di riduzione del livello di un segnale audio che verrà applicata dal compressore quando il segnale supera una certa soglia. Ad esempio, con una ratio di 4:1, ogni volta che il segnale supera la soglia impostata, il compressore ridurrà il livello del segnale a 1/4 della sua ampiezza originaria.

In altre parole, se la soglia è impostata a -20 dB e il segnale raggiunge -10 dB, la compressione verrà applicata e il livello del segnale verrà ridotto a -17,5 dB (oltre alla soglia impostata). 

La ratio è espressa come un rapporto tra l'ammontare di riduzione del livello del segnale e l'ammontare iniziale. Ad esempio, una ratio di 2:1 significa che per ogni 2 dB sopra la soglia, verranno ridotti a 1 dB.

In sintesi, più alta è la ratio, maggiore sarà la quantità di compressione applicata al segnale audio sopra la soglia impostata.

Pronuncia ˈrāSH(ē)ō in inglese o ràzzio in latino

### Attacchi e Rilasci
![image_1630097546724_0.png](/img/user/3.%20Resources/Attachments/image_1630097546724_0.png)

Gli attacchi e i rilasci di un compressore audio sono i parametri che regolano l'effetto del compressore sul segnale audio. 

**L'attacco** indica il tempo che il compressore impiega per agire sul segnale dopo che questo supera la soglia impostata. Un attacco rapido significa che il compressore interviene quasi immediatamente, mentre un attacco lento fa sì che il compressore intervenga gradualmente.

**Il rilascio** indica invece il tempo che il compressore impiega per tornare alla sua posizione iniziale dopo aver agito sul segnale. Un rilascio rapido significa che il compressore tornerà alla sua posizione iniziale rapidamente, mentre un rilascio lento farà sì che il compressore torni gradualmente alla sua posizione iniziale.

In generale, un attacco rapido e un rilascio lento sono utilizzati per mantenere le parti più forti del segnale sotto controllo, mentre un attacco lento e un rilascio rapido sono utilizzati per mantenere le parti più deboli del segnale sotto controllo.

La corretta regolazione degli attacchi e dei rilasci è importante per ottenere il suono desiderato e dipende dal tipo

di solito la release si esprime sempre in secondi, mentre l'attacco in ms
espressi in secondi:
.1 (0,1s) = 100 ms
30 ms = 0.03 s


#### Distorsione indesiderata
È possibile riscontrare una distorsione su un suono che si sta andando a comprimere, in particolare su un SUB, questo succede perché il periodo di un’onda a bassa frequenza è in realtà piuttosto lungo. Se il tempo di Release del compressore è impostato abbastanza veloce, la riduzione del guadagno può iniziare ad agire entro un ciclo dell’onda sonora. In questo modo la forma d’onda va in clip e produce una distorsione udibile.
Ci sono diversi modi per risolvere:
- Utilizzare un EQ su un [[3. Resources/Music Production/Sidechain\|Sidechain]] interno, in questo modo gli si va a dire di considerare i tempi delle alte frequenze.
- Utilizzare la funzione "Lookahead" che trovi ad esempio su un [[3. Resources/Music Production/Mixing & Mastering/Limiter\|Limiter]]

### Knee
![Knee Compressor.jpg](/img/user/3.%20Resources/Attachments/Knee%20Compressor.jpg)
Con un'impostazione di hard knee si ha una risposta più "meccanica" dal compressore, mentre il soft knee può garantire risultati più morbidi, con un senso più "musicale", in quanto la compressione inizia a lavorare in modo meno istantaneo e quindi, apparentemente, più naturale.

### Peak vs RMS
![Peak-vs.-RMS.png](/img/user/3.%20Resources/Attachments/Peak-vs.-RMS.png)
![Sound-Wave-RMS-and-Peak-652x199.jpg](/img/user/3.%20Resources/Attachments/Sound-Wave-RMS-and-Peak-652x199.jpg)
I processori di dinamica hanno in generale due possibili modalità di funzionamento: ci sono quelli basati sui valori di picco e quelli che si basano sul valore "RMS response". Ognuno dei due sistemi presenta i suoi vantaggi in differenti situazioni. Ad esempio, l'analisi basata sui picchi si rivela particolarmente efficace con le percussioni, mentre l'analisi [[3. Resources/Music Production/RMS\|RMS]] dà migliori risultati con programmi complessi.


