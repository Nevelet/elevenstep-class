---
{"dg-publish":true,"permalink":"/3-resources/music-production/audio/frequenza-di-campionamento/"}
---

Links:: [[3. Resources/Music Production/Teoria del Suono\|Teoria del Suono]]

---
## Cos'è

La frequenza di campionamento è la misura espressa in hertz, che indica il numero di volte al secondo in cui un segnale analogico viene misurato e memorizzato in forma digitale (da "digit" che in inglese significa "cifra"; in questo caso, nel mondo informatico e elettronico, il significato varia in "cifra binaria").

Dunque, il campionamento è la conversione di un segnale analogico in digitale, effettuando tante "fotografie" al secondo, in base al sample rate impostato.

![Campionamento.png](/img/user/3.%20Resources/Images/Campionamento.png)

La qualità del file da riprodurre è dato da due fattori: risoluzione e frequenza di campionamento. La risoluzione è espressa in Bit, mentre il valore di campionamento è espresso in Kilohertz (kHz).

Come puoi vedere dall'immagine sopra, il Bit, indica risoluzione di ampiezza, mentre la freq. di campionamento, la risoluzione in frequenza.

- 44.100 
- 48.000
- 88.200
- 96.000

## Quale Frequenza di Campionamento scegliere

Le frequenze di campionamento più utilizzate sono:
- 44.100 hz
- 48.000 hz (usata per il video perché divisibili per frame)

Inoltre, la frequenza di campionamento di un file audio deve essere uguale a quella del progetto, per evitare cambi di pitch.

Alcune DAW effettuano la conversione (downsampling o upsampling) in automatico o tramite un'opzione, per adattare il file audio al progetto.

Più si alza la frequenza di campionamento e più consumo delle risorse avremmo, soprattutto per la CPU e l'hard disk

## Perché lavorare a frequenze di campionamento alte, se il prodotto finale sarà quasi sempre a 44.100 hz?

Lavorare a frequenze di campionamento alte, permette specialmente nella post produzione, di avere più campioni e quindi più risoluzione, soprattutto quando si effettuano alcuni interventi di questo tipo:

**Stretching**
- più un file audio viene stretchato, meno campioni ci saranno e di conseguenza il programma dovrà interpolare quelli rimanenti. Questo in alcuni casi porta un degrado dell'audio.

**Saturazione**
- Le armoniche superiori generate in saturazione sbattendo contro la frequenza di Nyquist tornano indietro come rumore

**Altri processi**
- Ovviamente questo vale anche per processi di equalizzazione, compressione, limiting ecc...

**Plug-in**
- I plug-in lavorano meglio con freq. di campionamento alta, soprattutto gli oscillatori, riescono ad avere più definizione sulle armoniche.

==Quindi una freq. di campionamento alta è più adatta quando si effettuano processi molto pesanti nell'audio.==

## Alte Frequenze e Filtro

Quando viene effettuato il campionamento, per alcuni problemi di elettronica, ad es. problemi di [[3. Resources/Music Production/Aliasing\|Aliasing]], viene applicato un filtro, quest'ultimo ha una pendenza diversa in base alla frequenza di campionamento scelta, più alta sarà la frequenza, più morbido sarà l'intervento di filtering. Considerando pure che Il filtro, di suo, andrà a rovinare un po' il segnale per i suoi problemi più noti, come la fase.

## [[3. Resources/Music Production/Resampling Audio\|Resampling]] 

Sul ricampionamento bisogna stare attenti con quale software/DAW viene effettuato. Alcuni permettono di scendere da 96khz a 44.1 khz senza problemi, con un buon rapporto di qualità, altri invece fanno dei pasticci.


## Notes

**Dati tecnici**
- 1000 millisecondi = 1 secondo.
- 50 Hz = 50 cicli al secondo
- 1000 ms / 50 hz = 20 ms ogni ciclo — 20 x 50 = 1000 ms (1 secondo)

## Related Notes

- [[3. Resources/Music Production/Teoria del Suono\|Teoria del Suono]]
- [[3. Resources/Music Production/Aliasing\|Aliasing]]
- [[3. Resources/Music Production/Teorema del Campionamento (Nyquist Shannon)\|Teorema del Campionamento (Nyquist Shannon)]]
- [[3. Resources/Music Production/Bit Rate & Bit Depth\|Bit Rate & Bit Depth]]
- [[3. Resources/Music Production/Oversampling\|Oversampling]]
- [[3. Resources/Music Production/Resampling Audio\|Resampling Audio]]

## References

**Video**

- [SampleRate e Bit 44 48 96kHz e 16 o 24bit? Quale frequenza ](https://youtu.be/jJEm10Hj1sQ)
- [Cos'è il Campionatore e qual è la sua storia nell'Hip Hop?](https://www.youtube.com/watch?v=7JXu6DFhprs)
- [Stai distorcendo / saturando sbagliato](https://youtu.be/NaHVqEpZFQc)
- [Why MANY ANALOG EMULATIONS are SNAKE OIL!](https://youtu.be/4taroKS_N6Q)

**Articoli**

- [Il campionamento digitale (itimarconinocera.org)](https://www.itimarconinocera.org/sito/menu/dipartimenti/tecnico_scientifico_informatica/corso_musica_elettronica/7.htm)
- [Frequenza di campionamento](https://it.wikipedia.org/wiki/Frequenza_di_campionamento)
- [Audio in alta risoluzione: come ascoltare la musica alla massima qualità](https://hifidagostini.it/audio-alta-risoluzione/)
- [La Guida all’Audio Digitale per le Registrazioni Musicali](https://it.ehomerecordingstudio.com/audio-digitale/)
- [Ascoltare musica in altissima qualità](http://www.2l.no/hires/index.html)
- [Downsampling Wikipedia](https://en.wikipedia.org/wiki/Downsampling_(signal_processing))