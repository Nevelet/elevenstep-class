---
{"dg-publish":true,"permalink":"/3-resources/music-production/plugins/plugin-audio/"}
---

Links:: [[3. Resources/Music Production/Plugins/Plugin\|Plugin]], [[3. Resources/General Knowledge/Audio\|Audio]]

---
I [[3. Resources/Music Production/Plugins/Plugin\|Plugin]] [[3. Resources/General Knowledge/Audio\|audio]] **sono piccoli programmi o estensioni software che vengono aggiunti a un software audio o DAW** (Digital Audio Workstation) **per aggiungere funzionalità o effetti extra al processo di produzione musicale**. Possono includere strumenti virtuali, effetti sonori, processori di suono e molto altro. I plugin audio consentono di manipolare o creare suoni in modo più avanzato e personalizzato all'interno di un ambiente digitale. Sono fondamentali per la produzione musicale moderna.

--- 

## Tipi di Plugin Audio

- [[3. Resources/Music Production/Plugins/Plugin Audio Effect\|Plugin Audio Effect]]
- [[3. Resources/Music Production/Plugins/Plugin Audio Effect MIDI\|Plugin Audio Effect MIDI]]
- [[3. Resources/Music Production/Plugins/Plugin Audio Instrument\|Plugin Audio Instrument]]

## Formati

- VST (VST2), VST 3 - (Virtual Studio Technology)
	- .dll (VST) e .vst3 (VST 3)
- CLAP
	- .clap
- AU
	- .component
- AAX
- RTAS

\***VST2 (chiamato anche VST2.4 o semplicemente VST)**

### Resources

- [Plugin Audio: Cosa Sono, Differenze tra i Formati, i Migliori | Guida](https://claudiomeloni.it/plugin-audio-cosa-sono-differenze-formati-migliori-vst-au-aax-rtas-tdm-lv2/)

## AU vs. VST

|                                 |            |              |              |
| ------------------------------- | ---------- | ------------ | ------------ |
|                                 | **AU**     | **VST2**     | **VST3**     |
| **Direct MIDI Output**          | no         | yes          | yes          |
| **Cross platform**              | macOS only | macOS or Win | macOS or Win |
| **Waves supported in Live**     | no         | yes          | recommended  |
| **Presets menu in Live device** | no         | yes          | no           |
| **File type**                   | .component | .vst         | .vst3        |
\*direct MIDI output (MIDI To) è la possibilità di mandare il MIDI da una traccia all'altra. — [Accessing the MIDI output of a VST plug-in – Ableton](https://help.ableton.com/hc/en-us/articles/209070189-Accessing-the-MIDI-output-of-a-VST-plug-in)

[Using AU and VST plug-ins on macOS – Ableton](https://help.ableton.com/hc/en-us/articles/209068929-Using-AU-and-VST-plug-ins-on-macOS)

## Percorsi

### MAC

- **AU (Audio Units):** `/Library/Audio/Plug-Ins/Components`
- **VST/VST3:** `/Library/Audio/Plug-Ins/VST` and `/Library/Audio/Plug-Ins/VST3`
- **AAX:** `/Library/Application Support/Avid/Audio/Plug-Ins`
- **CLAP:** `Library/Audio/Plug-ins/CLAP folder.`
- **RTAS:** `Library/Application Support/Digidesign/Plug-Ins`_

Nota: i plug-in AU e VST/VST3 possono anche essere inseriti nelle cartelle della Libreria dell'utente in `/Users/<nomeutente>/Library/Audio/Plug-Ins`

#### Presets o altro

- `/Users/<username>/Library/Audio/Presets/[nome plugin]`
- `/Users/<username>/Library/Preferences/[nome plugin]`
- `/Users/<username>/Library/Application Support/FabFilter/[nome plugin]`

Nota: a partire da OS X 10.7 (Lion), le cartelle della libreria di sistema e dell'utente sono contrassegnate come nascoste per impostazione predefinita. Per renderli nuovamente visibili nel Finder, apri Terminale (che si trova in /Applicazioni/Utility) e inserisci i seguenti comandi:
```
chflags nohidden /Library
chflags nohidden ~/Library
```

### Windows

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


## Related Notes

- [[3. Resources/Music Production/Plugins/Plugin Audio da Provare\|Plugin Audio da Provare]]
- [[3. Resources/Music Production/Plugins/Plugin Audio gratis del 2023\|Plugin Audio gratis del 2023]]
- [[3. Resources/Music Production/Ableton/Ableton - Configurazione Plugins\|Ableton - Configurazione Plugins]]
- [[4. Archived/1. Projects/Completed/ES - Content Creation (Elevenstep)/Come installare correttamente i plugin/Come installare correttamente i plugin\|Come installare correttamente i plugin]]
- [[4. Archived/1. Projects/Completed/ES - Content Creation (Elevenstep)/Come installare correttamente i plugin su Ableton/✍ Come installare correttamente i plugin su Ableton\|✍ Come installare correttamente i plugin su Ableton]]
- [[3. Resources/Music Production/Plugins/Disinstallare i Plugins\|Disinstallare i Plugins]]
