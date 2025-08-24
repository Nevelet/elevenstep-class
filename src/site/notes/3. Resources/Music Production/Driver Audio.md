---
{"dg-publish":true,"permalink":"/3-resources/music-production/driver-audio/"}
---

Links:: [[3. Resources/General Knowledge/Audio\|Audio]]

---

## Tipo di Driver

### Windows

**MME/DirectX**
MME sta per MultiMedia Extension e fa parte di Windows, questo driver stabilisce le regole per la registrazione e la riproduzione audio. In genere viene utilizzato di default dai sistemi Windows 1 3.0. È più lento perché è controllato dal sistema operativo.


**WASAPI**
WASAPI (Windows Audio Session API)è una tecnologia più recente di Microsoft che impiega metodi per inviare direttamente l'audio all'output dell'hardware chiamato Modalità esclusiva. La maggior parte dei software di riproduzione Blu Ray e DVD utilizza questo, perché consente la riproduzione di audio surround codificato Dolby e DTS attraverso le uscite audio digitali. Questa modalità inoltre non consentirà ad altre applicazioni di utilizzare l'hardware contemporaneamente.


**WDM**
WDM (Windows Driver Model) è stato rilasciato con Windows 98. Non è tecnicamente un driver audio; piuttosto è una piattaforma per i driver audio per diventare parte del kernel di Windows; un componente principale del sistema operativo. Questo è noto come kernel streaming. È lo standard per l'audio nella maggior parte delle applicazioni come l'audio dal browser Web, iTunes e altri software di riproduzione multimediale. Anche molti videogiochi utilizzeranno questo protocollo.


**[[3. Resources/Music Production/ASIO4ALL\|ASIO4ALL]]**



## Quale Driver Scegliere?

Il drivers ASIO è decisamente migliore per quanto riguarda soprattutto il rapporto di latenza tra l'input e l'output. Inoltre è supportato dalla maggior parte delle schede audio. Presente anche dei svantaggi, come ad esempio di non poter utilizzare più programmi che sfruttano l'audio.

In alcuni casi, soprattutto su computer un po' datati, il driver nativo del sistema operativo, può creare dei problemi, ad es. l'audio gracchiante. Questo perché il PC deve fare più elaborazioni. Mentre se il flusso audio viene affidato ad altri sistemi, driver e hardware esterni, si ha maggiore stabilità e minora latenza.



## 🔗 Related Notes

- [[3. Resources/Music Production/Ableton/Ableton - Configurazione Audio\|Ableton - Configurazione Audio]]
- [[3. Resources/Music Production/Audio/ASIO\|ASIO]]