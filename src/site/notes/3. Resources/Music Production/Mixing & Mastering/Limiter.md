---
{"dg-publish":true,"permalink":"/3-resources/music-production/mixing-and-mastering/limiter/"}
---

Links:: [[3. Resources/Music Production/Processori di Dinamica\|Processori di Dinamica]], [[3. Resources/Music Production/Effetti Audio\|Effetti Audio]]

---
## Descrizione

Un limiter audio è un dispositivo o un software che viene utilizzato per controllare il livello di volume massimo di un segnale audio. Il suo scopo principale è quello di prevenire distorsioni o danni ai diffusori e agli amplificatori, limitando il livello massimo del segnale audio ad un valore sicuro senza compromettere troppo la qualità del suono. Il limiter audio viene spesso utilizzato in applicazioni professionali come la registrazione, la produzione musicale e il [[3. Resources/Music Production/Mixing\|Mixing]], ma anche in ambito domestico per proteggere l'impianto stereo o gli altoparlanti.


**Brickwall Limiter**
- infinita:1
- oggigiorno il brickwall limiter viene chiamato direttamente limiter che permette di svolgere questo ruolo e altro
- una volta si diceva un limiter è un compressore con un ratio alta 10:1 o 20:1, oggi invece un limiter viene definito come un brickwall limiter o compressore con un'attacco rapido e un rapporto inf:1 
- [L1 Ultramaximizer Peak (Waves)](https://www.waves.com/plugins/l1-ultramaximizer)


## Parametri 

![Schema Compressore e Limiter.png](/img/user/3.%20Resources/Images/Schema%20Compressore%20e%20Limiter.png)
1. **Input Gain** - Questo parametro regola il volume di ingresso del segnale prima che questo venga limitato.
2. **Threshold** (soglia) - il livello massimo di input a cui il limiter inizia ad agire.
3. **Attack** (attacco) - il tempo che il limiter impiega per entrare in funzione, ovvero per ridurre il volume del segnale.
4. **Release** (rilascio) - il tempo che il limiter impiega per tornare alla sua posizione normale dopo aver ridotto il volume del segnale.
5. **Ratio** - la quantità di riduzione del volume del segnale quando supera la soglia impostata.
6. **Output gain** (guadagno di uscita) - la regolazione del livello di uscita, che permette di compensare eventuali perdite di volume dovute all'azione del limiter.
7. **Soft-knee** (ginocchio morbido) - una funzione che consente al limiter di agire gradualmente sulla dinamica del segnale, invece che in modo repentino e drastico.
8. **True peak limiting** (limitazione a picco vero) - una funzione che permette al limiter di evitare la distorsione degli effetti armonici e dei picchi indesiderati causati dalla limitazione dei picchi audio.
9. **Ceiling** - Questo parametro è il più importante all’interno del Limiter. Determina il valore massimo di uscita del Limiter stesso. Aumentando l’Input Gain e regolando il Ceiling potrai ottenere un aumento del livello RMS tenendo comunque il livello di picco limitato (appunto dal Ceiling)
10. **Lockahead** - Si tratta di un parametro che regola la velocità di risposta del Limiter ai picchi. Tempi più brevi permettono di ottenere una maggiore compressione, quindi un’amalgama generale del mix, tuttavia aumenta il rischio di ottenere anche distorsioni indesiderate.


## Extra Parametri

- [[3. Resources/Music Production/Oversampling\|Oversampling]]
- [[3. Resources/Music Production/True Peak\|True Peak]]


## I Migliori Plugins

- [[3. Resources/Music Production/Plugins/FabFilter Pro-L2\|FabFilter Pro-L2]]
- [Sonnox Oxford Limiter V3](https://www.thomann.de/it/sonnox_oxford_limiter_native.htm?partner_id=31594)
- [Waves L1 Ultramaximizer](https://www.thomann.de/it/waves_l1_ultramaximizer.htm?partner_id=31594)
- [Brainworx bx_XL V2](https://www.plugin-alliance.com/en/products/bx_xl_v2.html)
- [Nugen Audio ISL](https://nugenaudio.com/isl/)
- Maximizer Ozone
- Master Plan
- Lace (Acustica Audio)


## Notes

Il Limiter non permette di regolare l'attack, ma ha il lookhead e l'auto release che non sono da sottovalutare


## Related Notes

- [[3. Resources/Music Production/Maximizer\|Maximizer]]
- [[3. Resources/Music Production/Mixing & Mastering/Clipper\|Clipper]]