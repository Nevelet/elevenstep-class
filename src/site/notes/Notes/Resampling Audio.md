---
{"dg-publish":true,"permalink":"/notes/resampling-audio/"}
---

Links:: [[Notes/Music Production\|Music Production]], [[Audio\|Audio]]

---
## Descrizione

Il **resampling audio** è il processo di **modificare la frequenza di campionamento** di un file audio. La frequenza di campionamento, misurata in **hertz (Hz)** o **kilohertz (kHz)**, indica quante volte al secondo il segnale audio viene campionato e convertito in dati digitali.

Esistono due tipi principali di resampling:

1. **Upsampling:** Aumento della frequenza di campionamento.
2. **Downsampling:** Riduzione della frequenza di campionamento.

## Upsampling

l'upsampling è interpolazione quindi aggiunta di campioni "calcolati".
Nel caso dell'upsampling viene aumentato ma non significa che aumenta la definizione o qualità (anzi). I campioni che vengono aggiunti infatti sono "calcolati" e non sono effettivi. E' come se avessi mezzo litro di vino e aggiungessi mezzo litro d'acqua dicendo che ora hai un litro di vino...

- Aumentare la frequenza di campionamento significa acquisire più campioni del segnale audio al secondo.
- Teoricamente, questo può migliorare la qualità del suono perché teoricamente riduce l'aliasing (distorsione introdotta durante la conversione analogico-digitale).
- Tuttavia, l'upsampling non può effettivamente "aggiungere" informazioni che non erano presenti nel segnale audio originale registrato a una frequenza di campionamento inferiore.
- L'upsampling può essere utile in alcuni casi, come ad esempio quando si prepara un file audio per la masterizzazione a una frequenza di campionamento più alta.

## Downsampling

Il sotto-campionamento o decimazione (downsampling in inglese) è nella teoria dei segnali l'operazione di riduzione della frequenza di campionamento del segnale elettrico.

Tale tecnica viene impiegata solitamente per comprimere la velocità di trasmissione o la dimensione dei dati in formato digitale. Se i dati sono di tipo grafico (ad esempio, immagini digitali), l'operazione prende il nome di subsampling, e in quel caso consiste nella riduzione dei pixel che compongono l'immagine.

- Ridurre la frequenza di campionamento significa acquisire meno campioni del segnale audio al secondo.
- Questo riduce la dimensione del file audio, ma può anche introdurre distorsione chiamata aliasing se non eseguito correttamente.
- L'aliasing si verifica quando le frequenze del segnale audio originale sono troppo alte per essere rappresentate accuratamente dalla nuova frequenza di campionamento più bassa.
- Il downsampling è spesso utilizzato per ridurre le dimensioni dei file audio per lo streaming o per la compatibilità con dispositivi mobili con risorse limitate. È importante utilizzare algoritmi di resampling di alta qualità per minimizzare l'aliasing.

## Quando usare il Resampling Audio

- **Compatibilità:** Potresti aver bisogno di modificare la frequenza di campionamento di un file audio per renderlo compatibile con un dispositivo o software specifico che richiede una frequenza di campionamento particolare.
- **Masterizzazione:** In alcuni casi, l'upsampling può essere utilizzato durante la masterizzazione per preparare il file audio per l'uscita finale a una frequenza di campionamento più alta.
- **Ridurre le dimensioni del file:** Il downsampling può essere utile per ridurre le dimensioni dei file audio per lo streaming o per la condivisione online.

**È importante notare che il resampling audio non è sempre un processo lossless (senza perdita).** A seconda della qualità dell'algoritmo di resampling utilizzato, potrebbe introdurre una leggera perdita di qualità del suono, soprattutto nel caso del downsampling.

Quando si esegue il resampling audio, è fondamentale scegliere un algoritmo di alta qualità per minimizzare la perdita di qualità e l'introduzione di distorsione.



## Tecniche

- Resampling Reverb
	- Registrando il midi in audio è possibile creare atmosfere particolari e interessanti.
- Cambiare il pitch senza warp
	- Permette di allungare il suono cambiano pure tono e timbro.
- Reverse
	- Per creare delle suspense e transizioni
- Creare effetti particolari
- Per il [[Notes/Layering\|Layering]]


## 🔗 Related Notes

- [[Notes/Ableton/Resampling Audio su Ableton\|Resampling Audio su Ableton]]
- [[Notes/Differenza tra Resampling e Oversampling\|Differenza tra Resampling e Oversampling]]
- [[Notes/Oversampling\|Oversampling]]


## Resources

- [Musica & Memoria - Tecnologia & Mercato: Upsampling fai da te](https://musicaememoria-tecno.blogspot.com/2017/10/upsampling-fai-da-te.html)
- [Upsampling e downsampling](https://it.hobby.hi-fi.narkive.com/63BARHLY/upsampling-e-downsampling)
