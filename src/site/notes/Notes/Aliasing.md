---
{"dg-publish":true,"permalink":"/notes/aliasing/"}
---

Links:: [[Notes/Campionamento audio\|Campionamento audio]]

---
==Un errore di rappresentazione del segnale originale, campionando con una frequenza più bassa di quella in entrata==

I segnali analogici vengono spesso convertiti in digitali per essere successivamente elaborati o archiviati. Durante questa conversione analogico-digitale il segnale viene sottoposto a due distinte discretizzazioni: la discretizzazione dei tempi, detta campionamento, e la discretizzazione delle ampiezze, detta quantizzazione.
Al contrario nella conversione digitale-analogica il segnale digitale viene trasformato nuovamente in un segnale analogico operando una interpolazione.
Se non viene rispettato il teorema di Nyquist, cioè si ha un sottocampionamento del segnale analogico nel dominio del tempo, nel dominio delle frequenze si ha la produzione di frequenze non proprie del segnale originario (alias) e viceversa dal dominio della frequenza al dominio del tempo si genera una distorsione del segnale originario, divenuto ora non più fedele. — [Aliasing - Wikipedia](https://it.wikipedia.org/wiki/Aliasing)

## Filtro anti-alias o filtro anti aliasing

È un filtro passa basso situato nell'ADC, e permette di limitare alcuni problemi in fase di campionamento, soprattutto i problemi di aliasing.

Nel dominio digitale, questo è diverso, perché sono numeri già elaborati, ed è per questo che entra in gioco l'oversampling, che sovracampiona ad un sample rate più alto, cosi che eventuali armoniche superiori generati ad es. da una saturazione, non vadano a sbattere nella frequenza di Nyquist, ritornando indietro nello spettro e producendo aliasing.

Il filtro anti-alias è un filtro analogico utilizzato prima del campionamento di un segnale, al fine di restringere la banda del segnale stesso per soddisfare approssimativamente il teorema del campionamento di Nyquist-Shannon. Dal momento che il teorema dice che un'interpretazione non ambigua del segnale, a partire dal campionamento, è possibile solo quando la potenza delle frequenze all'esterno della banda di Nyquist è zero, il filtro anti-aliasing potrebbe soddisfare il teorema. Ogni possibile filtro anti-alias permetterà la presenza di qualche alias; l'ammontare dell'alias presente nel risultato dipende dalla qualità del filtro.
I filtri anti-alias vengono solitamente usati nei sistemi di elaborazione numerica dei segnali, ad esempio in operazioni di audio digitale o fotografia digitale; filtri simili vengono utilizzati anche nella ricostruzione dell'output nei lettori musicali. Infine, il filtro evita l'alias durante la conversione di un campionamento in un segnale continuo, dove la stop-band rejection è richiesta per garantire l'azzeramento dell'alias. — [Filtro anti-alias - Wikipedia](https://it.wikipedia.org/wiki/Filtro_anti-alias)

### Mantenere l'integrità del segnale

Siccome l'operazione di sottocampionamento riduce la frequenza di campionamento, bisogna verificare che il teorema del campionamento di Nyquist-Shannon non venga infranto. Se invece il teorema non viene soddisfatto allora il significato risultante presenterà aliasing. Al fine di assicurare che il teorema sia soddisfatto, è usato un filtro passa basso assieme ad un filtro anti-aliasing per ridurre l'ampiezza di banda del segnale prima che esso venga compresso.


## 🔗 Related Notes

- [[Notes/Oversampling\|Oversampling]]

## Resources

- [Digital Audio 101: Aliasing Explained - YouTube](https://www.youtube.com/embed/XoVhNhi76Qk)
- [Sampling, Aliasing & Nyquist Theorem - YouTube](https://www.youtube.com/embed/yWqrx08UeUs)
- [[Notes/Teorema del Campionamento (Nyquist Shannon)\|Teorema del Campionamento (Nyquist Shannon)]]


