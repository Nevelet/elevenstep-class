---
{"dg-publish":true,"permalink":"/notes/spleeter/"}
---

Links:: [[Notes/Plugins/Plugin Audio\|Plugin Audio]]

---
## Cos'è?

[Spleeter](http://github.com/deezer/spleeter) sfrutta la potenza di un algoritmo di separazione della sorgente. Si presenta sotto forma di una libreria Python basata su [Tensorflow](https://www.tensorflow.org/) , con modelli pre-addestrati per la separazione di 2, 4 e 5 Stems.

**Spleeter** è la libreria di separazione dei sorgenti di [Deezer](https://www.deezer.com/) con modelli pre-addestrati scritti in [Python](https://www.python.org/) e utilizza [Tensorflow](https://tensorflow.org/) . Semplifica l'addestramento del modello di separazione della sorgente (supponendo che tu abbia un set di dati di sorgenti isolate) e fornisce un modello all'avanguardia già addestrato per eseguire vari tipi di separazione:
-   Voce (voce che canta) / separazione dell'accompagnamento ( [2 gambi](https://github.com/deezer/spleeter/wiki/2.-Getting-started#using-2stems-model) )
-   Voce / batteria / basso / altra separazione ( [4 gambi](https://github.com/deezer/spleeter/wiki/2.-Getting-started#using-4stems-model) )
-   Voce / batteria / basso / piano / altra separazione ( [5 gambi](https://github.com/deezer/spleeter/wiki/2.-Getting-started#using-5stems-model) )

 ### Progetti e software che utilizzano **Spleeter**

Da quando è stato rilasciato, ci sono più fork che espongono **Spleeter** tramite un'interfaccia utente guidata (GUI) o un sito Web autonomo gratuito o a pagamento. Si prega di notare che non ospitiamo, manteniamo o sosteniamo direttamente nessuna di queste iniziative.

Detto questo, molti progetti interessanti sono stati costruiti sopra il nostro. In particolare il porting all'ecosistema _Ableton Live_ attraverso il progetto [Spleeter 4 Max](https://github.com/diracdeltas/spleeter4max#spleeter-for-max) .

**I modelli** pre-addestrati di **Spleeter** sono stati utilizzati anche da software audio professionali. Ecco un elenco non esaustivo:

- [iZotope](https://www.izotope.com/en/shop/rx-8-standard.html) nella sua funzione _Music Rebalance_ all'interno di **RX 8**
- [SpectralLayers](https://new.steinberg.net/spectralayers/) nella sua funzione _Unmix_ in **SpectralLayers 7**
- [Acon Digital](https://acondigital.com/products/acoustica-audio-editor/) all'interno di **Acoustica 7**
- [VirtualDJ](https://www.virtualdj.com/stems/) nella loro funzione di isolamento dello stelo
- [Algoriddim](https://www.algoriddim.com/apps) nella loro suite di app **NeuralMix** e **djayPRO**


## Come si installa?

- (Metodo Nerd) direttamente dalla riga di comando
	- https://github.com/deezer/spleeter/wiki/1.-Installation
	- Video Installazione Spleeter_1 https://www.youtube.com/watch?v=WmThLASBpMI
	- Video Installazione Spleeter_2 https://www.youtube.com/watch?v=3S943Rc3uJg
	- Installazione step https://ezstems.com/installing-spleeter-windows/
- (Metodo Nerd senza installare niente)
	- https://github.com/dvschultz/ml-art-colabs/blob/master/Demucs.ipynb
	- Video: https://www.youtube.com/watch?v=tHxsqFcx7gw
- Spleeter M4L (Bisogna smanettare)
- https://github.com/diracdeltas/spleeter4max#download-links
	- https://github.com/diracdeltas/spleeter4max/blob/feature/native-spleeter/README.md#spleeter-for-max-native-version 
- Spleeter Dj VST3 (Facile ma richiede alcuni componenti)
	- https://azuki.bandcamp.com/merch/experimental-spleeter-plugin-for-live-stem-separation
- https://github.com/diracdeltas/vstSpleeter/releases/tag/v0.2.1
- SpleeterGui (Facile e intuitivo)
	- https://github.com/boy1dr/SpleeterGui
	- https://makenweb.com/SpleeterGUI
	- Installazione video: https://www.youtube.com/watch?v=e0z6NTh7VY4

Abbiamo progettato **Spleeter in** modo che tu possa usarlo direttamente dalla [riga di comando](https://github.com/deezer/spleeter/wiki/2.-Getting-started#usage) e direttamente nella tua pipeline di sviluppo come [libreria Python](https://github.com/deezer/spleeter/wiki/4.-API-Reference#separator) . Può essere installato con [Conda](https://github.com/deezer/spleeter/wiki/1.-Installation#using-conda) , con [pip](https://github.com/deezer/spleeter/wiki/1.-Installation#using-pip) o essere utilizzato con [Docker](https://github.com/deezer/spleeter/wiki/2.-Getting-started#using-docker-image) .




 

## **Una breve panoramica della separazione alla fonte**

Sebbene non sia un argomento ampiamente noto, il problema della separazione della sorgente ha interessato una vasta comunità di ricercatori di segnali musicali da un paio di decenni a questa parte. Si parte da una semplice osservazione: le registrazioni musicali sono solitamente un mix di più tracce strumentali individuali (voce solista, batteria, basso, piano ecc ..). Il compito della separazione della sorgente musicale è: dato un mix possiamo recuperare queste tracce separate (a volte chiamate _gambi_ )? Ciò ha molte potenziali applicazioni: pensa a remix, upmix, ascolto attivo, scopi educativi, ma anche pre-elaborazione per altre attività come la trascrizione.

![Immagine per post](https://miro.medium.com/max/60/1*j1WakLQXuQkJCXlRk0xt5g.jpeg?q=20)

![Immagine per post](https://miro.medium.com/max/1150/1*j1WakLQXuQkJCXlRk0xt5g.jpeg)

Da un mix di molti strumenti, un motore di separazione della sorgente come **Spleeter** emette un set di singole tracce o gambi.

È interessante notare che il nostro cervello è molto bravo a isolare gli strumenti. Concentrati solo su uno degli strumenti di [questa traccia](https://www.deezer.com/track/2124880) (ad esempio la voce principale) e sarai in grado di _ascoltarlo in_ modo abbastanza distinto dagli altri. Eppure questa non è veramente separazione, senti ancora tutte le altre parti. In molti casi, potrebbe non essere possibile recuperare esattamente le singole tracce che sono state mixate insieme. La sfida è quindi avvicinarli il meglio possibile, vale a dire il più vicino possibile agli originali senza creare troppe distorsioni.

Per anni sono state esplorate molte strategie, da dozzine di brillanti gruppi di ricerca provenienti da tutto il mondo. Se sei interessato a questo affascinante viaggio dovresti andare a leggere [questa panoramica della letteratura,](https://sigsep.github.io/literature/) o [questa](http://zafarrafii.com/Publications/Rafii-Liutkus-Stoter-Mimilakis-FitzGerald-Pardo%20-%20An%20Overview%20of%20Lead%20and%20Accompaniment%20Separation%20in%20Music%20-%202018.pdf) . Il ritmo del progresso ha recentemente fatto alcuni passi da gigante, principalmente grazie ai progressi nei metodi di apprendimento automatico. Per tenerne traccia, le persone hanno confrontato il loro algoritmo in [campagne di valutazione internazionali](https://sisec18.unmix.app/#/) . È così che sappiamo che **le** prestazioni di **Spleeter** corrispondono a quelle dei migliori algoritmi proposti.

Inoltre, **Spleeter** è _molto_ veloce. Se stai eseguendo la versione GPU, puoi aspettarti una separazione **100 volte più veloce del tempo reale, il** che lo rende una buona opzione per elaborare set di dati di grandi dimensioni.

## Cosa posso fare con Spleeter?

Molto direi. Se sei un ricercatore che lavora su Music Information Retrieval e hai sempre considerato che gli artefatti della separazione della sorgente lo rendessero inadatto come fase di pre-elaborazione nella tua pipeline ... Beh, dovresti probabilmente riconsiderare e provare **Spleeter** . Se sei un hacker musicale e vuoi creare qualcosa di fantastico usando **Spleeter** , allora vai avanti. In realtà **Spleeter** è [autorizzato dal MIT,](https://opensource.org/licenses/MIT) quindi sei _veramente_ libero di usarlo in qualsiasi modo tu voglia. Inutile dire che se **prevedi di** utilizzare **Spleeter** su brani protetti da copyright, assicurati di ottenere in anticipo l'autorizzazione appropriata dai proprietari dei diritti.

## Come posso usare Spleeter?

Sotto il cofano, **Spleeter** è un motore abbastanza complesso e realizzato, ma abbiamo lavorato duramente per renderlo davvero facile da usare. La separazione effettiva può essere ottenuta con una [singola riga di comando](https://github.com/deezer/spleeter/wiki/2.-Getting-started#usage) e dovrebbe funzionare sul tuo laptop indipendentemente dal tuo sistema operativo. Per gli utenti più avanzati, esiste una classe API Python chiamata `[Separator](https://github.com/deezer/spleeter/wiki/4.-API-Reference#separator)`che puoi manipolare direttamente nella tua solita pipeline.

Abbiamo cercato di trovare una [documentazione completa](https://github.com/Deezer/spleeter/wiki) . Non esitate a darci feedback, segnalare problemi o suggerire miglioramenti attraverso i tradizionali strumenti GitHub!

## **Perché rilasciare Spleeter?**

Risposta breve: lo usiamo per la nostra ricerca e pensiamo che anche altri potrebbero volerlo.

Lavoriamo da molto tempo sulla separazione alla fonte (e avevamo già una [pubblicazione all'ICASSP 2019](https://ieeexplore.ieee.org/document/8683555) ). Abbiamo confrontato **Spleeter** con [Open-Unmix, un](https://sigsep.github.io/open-unmix/) altro modello open source recentemente rilasciato da un team di ricerca di Inria, e riportato [prestazioni leggermente migliori](http://archives.ismir.net/ismir2019/latebreaking/000036.pdf) con maggiore velocità (si noti che il set di dati di addestramento non è lo stesso).

Uno dei limiti difficili affrontati dai ricercatori MIR è la mancanza di set di dati disponibili pubblicamente a causa di problemi di copyright. Qui a **Deezer** , abbiamo accesso a un catalogo abbastanza ampio che abbiamo sfruttato per costruire **Spleeter** . Dato che non possiamo condividere questi dati, trasformarli in uno strumento accessibile è per noi un modo per rendere la nostra ricerca riproducibile da tutti. Da un punto di vista più etico, riteniamo che non dovrebbe esserci una concorrenza sleale tra i ricercatori basata sul loro accesso a materiale protetto da copyright o sulla sua mancanza.

Ultimo ma non meno importante, addestrare questo tipo di modelli richiede molto tempo ed energia. Facendolo una volta e condividendo il risultato, speriamo di risparmiare ad altri problemi e risorse.

## Un'ultima parola

Da quando abbiamo rilasciato **Spleeter** , abbiamo ricevuto numerosi feedback, molti dei quali molto positivi e siamo entusiasti di vedere tutta quell'attenzione dedicata al nostro lavoro. Alcune di queste reazioni potrebbero tuttavia essere un po 'troppo entusiaste, quindi riaffermiamo solo alcune cose. **Spleeter** è uno strumento accurato, ma in nessun modo affermiamo di aver " _risolto_ " la separazione alla fonte. Centinaia di ricercatori e ingegneri che lavorano per decenni hanno fatto i progressi e costruito gli strumenti su cui si basa **Spleeter** . È il nostro contributo a un ecosistema vivido, in continua crescita e aperto e, si spera, qualcosa su cui anche altri si baseranno.

Infine, vale la pena sottolineare che il mixaggio musicale è un'arte raffinata e che il mastering degli ingegneri del suono sono artisti a pieno titolo. Ovviamente non intendiamo in alcun modo danneggiare il loro lavoro o incidere sul credito di nessuno. Quando usi **Spleeter** , fallo in modo responsabile.

Detto questo, felice di hackerare tutti!

