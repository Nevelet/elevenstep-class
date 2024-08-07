---
{"dg-publish":true,"permalink":"/3-resources/music-production/plugins/disinstallare-i-plugins/"}
---

Links:: [[3. Resources/Music Production/Plugins/Plugin Audio\|Plugin Audio]]

---
## Tipi di installer

- 1. Installer (operazione automatica)
	- pkg (MAC)
	- exe (WIN)
- 2. Copia file (operazione manuale)
	- dll, vst3, clap ecc.

## Disinstallatore (Uninstaller)

- la versione Installer, ha di solito un altro eseguibile chiamato "Uninstaller" che serve per disinstallare il plugin. Anche se di solito non riesce a togliere tutto. Per questo motivo, è utile usare dei programmi appositi per la rimozione di alcuni file: file di registro, cartelle nascoste ecc.
- disinstallare i programmi usando direttamente la funzione del proprio sistema operativo, non elimina del tutto i file associati al programma. 

### WIN

- [HiBit Uninstaller](https://www.hibitsoft.ir/Uninstaller.html)
- [Revo Uninstaller Free](https://www.revouninstaller.com/it/products/revo-uninstaller-free/)


### MAC

- [AppCleaner (free)](https://freemacsoft.net/appcleaner/)
- [McClean (a pagamento)](https://apps.apple.com/it/app/mcclean/id440318935?mt=12)
- [CleanMyMac X (a pagamento)](https://cleanmymac.com/it)



## MAC


### Formati plugin

_Go/Finder → Computer → Macintosh HD_

- **AU (Audio Units):** `/Library/Audio/Plug-Ins/Components`
- **VST/VST3:** `/Library/Audio/Plug-Ins/VST` and `/Library/Audio/Plug-Ins/VST3`
- **AAX:** `/Library/Application Support/Avid/Audio/Plug-Ins`
- **CLAP:** `Library/Audio/Plug-ins/CLAP folder.`
- **RTAS:** `Library/Application Support/Digidesign/Plug-Ins`_

Nota: i plug-in AU e VST/VST3 possono anche essere inseriti nelle cartelle della Libreria dell'utente in `/Users/<nomeutente>/Library/Audio/Plug-Ins`

È possibile cercare i plugin anche usando la ricerca di Mac, digitando il formato del plugin da cercare, ad esempio: .vst per trovare tutti i vst.

### Presets o altro

Per disinstallare i plug-in dal tuo Mac, puoi semplicemente eliminare i file plug-in specifici nelle posizioni sopra indicate. Infine, se desideri davvero eliminare tutti i dati scritti dai nostri plug-in, puoi rimuovere anche le seguenti cartelle/file dalla cartella Libreria dell'utente:

- `/Users/<username>/Library/Audio/Presets/[nome plugin]`
- `/Users/<username>/Library/Preferences/[nome plugin]`
- `/Users/<username>/Library/Application Support/FabFilter/[nome plugin]`


Nota: a partire da OS X 10.7 (Lion), le cartelle della libreria di sistema e dell'utente sono contrassegnate come nascoste per impostazione predefinita. Per renderli nuovamente visibili nel Finder, apri Terminale (che si trova in /Applicazioni/Utility) e inserisci i seguenti comandi:
```
chflags nohidden /Library
chflags nohidden ~/Library
```


### Programma

- [Audio Plugin Uninstaller Completely uninstall your audio plugins on Mac. | Wide Blue Sound](https://www.widebluesound.com/audio-plugin-uninstaller/)
- [How to Uninstall VST/AU Plugins on a Mac | FREE VST AU AXX Plugin Uninstaller - YouTube](https://www.youtube.com/watch?v=1v4IlqLH0yA)



### Reference

- [How To Install Serum Presets For Mac OS - YouTube](https://youtu.be/UZ61h11r_wE)
- [Using AU and VST plug-ins on macOS – Ableton](https://help.ableton.com/hc/en-us/articles/209068929-Using-AU-and-VST-plug-ins-on-macOS)
- [Come CANCELLARE APP SU MAC nel modo CORRETTO! - Luca Crocco - YouTube](https://www.youtube.com/watch?v=WmlcBSwNDxM)








## Windows

- VST, percorsi comuni:
	- `C:\Program Files\Common Files\VST2`
	- `C:\Program Files\VST Plugins`
	- `C:\Program Files\Steinberg\Plugins`
- VST3: 
	- `C:\Programmi\File comuni\VST3.`
- AAX: 
	- `C:\Program Files\Common Files\Avid\Audio\Plug-Ins`
- RTAS:
	- `C:\Program Files(x86)\Common Files\Digidesign\DAE\Plug-ins\`
- CLAP:
	- `C:\Program Files\Common Files\CLAP\`



\*_i VST su Windows, possono essere installati in qualsiasi percorso definito dall'utente durante l'installazione. Mentre per i VST3 c'è un percorso fisso, come indicato sopra._

**Nelle corrispettive cartelle indicate sopra, devono contenere solo i formati dei plugin (ad es. dll, vst3) e non altri file**

**Inoltre, non installare le versioni standalone e VST nella stessa cartella.**

Alcuni plugin (ad es. Waves) può risultare più difficile trovare i file da eliminare. Tuttavia, è possibile cercare informazioni direttamente sulla casa produttrice del plugin per conoscere i vari percorsi. 

### Reference

- [Using VST plug-ins on Windows – Ableton](https://help.ableton.com/hc/en-us/articles/209071729-Using-VST-plug-ins-on-Windows)
- [Where is the plug-in located on my computer?](https://support.two-notes.com/knowledgebase.php?article=103)
- [CLAP Plugins](https://www.multitrackstudio.com/clapplugin.php)


## Programmi di ricerca

WIN
- [voidtools](https://www.voidtools.com/)

MAC
- https://alternativeto.net/software/easy-find/about/
- https://alternativeto.net/software/spotlight/about/



## 🔗 Related Notes

- [[4. Archived/1. Projects/Completed/ES - Content Creation (Elevenstep)/Come Eliminare definitivamente i Plugin\|Come Eliminare definitivamente i Plugin]]

## References

- [FabFilter Pro-Q 3 Help - Manual installation](https://www.fabfilter.com/help/pro-q/support/manualinstallation)
- [CLAP Plugins](https://www.multitrackstudio.com/clapplugin.php)
- [Where is the plug-in located on my computer?](https://support.two-notes.com/knowledgebase.php?article=103)
- [Come Cancellare Definitivamente i Plugin Audio su Mac | claudiomeloni.it](https://claudiomeloni.it/come-cancellare-definitivamente-i-plugin-audio-su-mac/)
- [La mia lista di plugin audio](https://docs.google.com/spreadsheets/d/1hYe_2ecsCTi_l9xT6lH9ZZquvJy-eNQ9wSXf0_d3Y5I/edit#gid=642549102)

