---
{"dg-publish":true,"permalink":"/3-resources/music-production/ableton/ableton-configurazione-audio/","tags":["note"]}
---

Links:: [[3. Resources/Music Production/Ableton/Ableton\|Ableton]], [[3. Resources/General Knowledge/Audio\|Audio]]

---
## 1. Dispositivo Audio


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/3-resources/music-production/driver-audio/#tipo-di-driver" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Tipo di Driver

### Windows

**MME/DirectX**
MME sta per MultiMedia Extension e fa parte di Windows, questo driver stabilisce le regole per la registrazione e la riproduzione audio. In genere viene utilizzato di default dai sistemi Windows 1 3.0. È più lento perché è controllato dal sistema operativo.


**WASAPI**
WASAPI (Windows Audio Session API)è una tecnologia più recente di Microsoft che impiega metodi per inviare direttamente l'audio all'output dell'hardware chiamato Modalità esclusiva. La maggior parte dei software di riproduzione Blu Ray e DVD utilizza questo, perché consente la riproduzione di audio surround codificato Dolby e DTS attraverso le uscite audio digitali. Questa modalità inoltre non consentirà ad altre applicazioni di utilizzare l'hardware contemporaneamente.


**WDM**
WDM (Windows Driver Model) è stato rilasciato con Windows 98. Non è tecnicamente un driver audio; piuttosto è una piattaforma per i driver audio per diventare parte del kernel di Windows; un componente principale del sistema operativo. Questo è noto come kernel streaming. È lo standard per l'audio nella maggior parte delle applicazioni come l'audio dal browser Web, iTunes e altri software di riproduzione multimediale. Anche molti videogiochi utilizzeranno questo protocollo.


**[[3. Resources/Music Production/ASIO4ALL\|ASIO4ALL]]**




</div></div>




### Quale Driver Scegliere?

Il drivers ASIO è decisamente migliore per quanto riguarda soprattutto il rapporto di latenza tra l'input e l'output. Inoltre è supportato dalla maggior parte delle schede audio. Presente anche dei svantaggi, come ad esempio di non poter utilizzare più programmi che sfruttano l'audio.


### Dispositivo Audio d'Ingresso

- Se è presente, qui è possibile selezionare i propri ingressi come: Microfono, Chitarra, Basso ecc...
- È possibile abilitare più ingressi per utilizzarli sulle varie tracce audio.

### Dispositivo Audio di Uscita

- Selezionare un'uscita audio hardware per ascoltare tutto quello che esce nella Traccia Master di Ableton.
- Anche qui puoi selezionare più uscire e utilizzarle per diversi scopi, come l'ascolto in cuffia o su altri monitor.

### Configurazione dei Canali

- Input 
- Output

## 2. Frequenza di Campionamento


## 3. Latenza

**Cos'è la Latenza**

l'intervallo di tempo che intercorre fra il momento in cui viene inviato l'input/segnale al sistema e il momento in cui è disponibile il suo output.

**Dimensione Buffer d'ingresso**


**Latenza d'ingresso**


**Dimensione Buffer di uscita**

- Latenza di uscita

**Latenza Complessiva**

## 4. Test

- Impostazione Buffer con Test
- ATTENZIONE, con il test puoi regolarti solo la dimensione buffer di uscita


## Related Notes

- [[3. Resources/Music Production/Ableton/Latenza su Ableton\|Latenza su Ableton]]


## Notes

Modalità esclusiva.
