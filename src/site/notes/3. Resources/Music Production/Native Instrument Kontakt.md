---
{"dg-publish":true,"permalink":"/3-resources/music-production/native-instrument-kontakt/","tags":["note"]}
---

Links:: [[3. Resources/Music Production/Plugins/Plugin Audio Instrument\|Plugin Audio Instrument]]

---
È un plugin multi-timbrico, ossia che può caricare più suoni, librerie e con canali midi e audio diversi 

## Tipi di formati

- Instrument (nki)
- Multi-Instrument (nkm)
- Bank (nkb)

[Kontakt Manual](https://www.native-instruments.com/ni-tech-manuals/kontakt-manual/en/index-en)
[How to Use Everything in KONTAKT 7 | Native Instruments - YouTube](https://www.youtube.com/watch?v=cANXrimv8C8)

## KeySwitch

Key switching
key switches
KeySwitch

- innescare un cambio ad es. di articolazione tramite nota
- KeySwitch and Expression Map è un dispositivo di [[3. Resources/Music Production/Max for Live (Ableton)\|Max for Live (Ableton)]] per ableton 
	- [KeySwitch & Expression Map for Ableton Live | swub](https://www.swub.de/en/software/keyswitch-expression-map-ableton-live/)
	- [KeySwitch & Expression Map 4.2 (Ableton Live) - Looking for authenticity in orchestral programming? - YouTube](https://www.youtube.com/watch?v=dDZhmrQ84W0)

- [Using Ableton Live to choose articulations using Kontakt Instrument Banks instead of key switches - YouTube](https://youtu.be/1oW-PPKqnZQ)


- è possibile cambiare i bank tramite le note. C'è uno script per farlo. Cliccare su KSP (in alto a destra) dopodiché su "Preset" d nella categoria Transform, cliccare sulla voce "Notes To Prog Change"


- [[3. Resources/Music Production/Kontakt - Cambiare Articolazioni\|Kontakt - Cambiare Articolazioni]]


## Edit Mode

### Gruppi

- i gruppi sono dei contenitori che possono contenere diversi tipi di suoni o timbriche
- ogni gruppo può anche avere diverse impostazioni, come pitch, effetti, routing ecc.
- di default i gruppi suonano contemporaneamente insieme, altrimenti si deve usare la funzione "Group Start" che trovi sotto
- per cambiare gruppo con le note, si deve usare "Group Start Options" che sta sempre nel riquadro "Group Editor"


## Mixer (Outputs)

- [[4. Archived/Projects Completed/ES - Content Creation (Elevenstep)/Impostare gli outputs su Kontakt\|Impostare gli outputs su Kontakt]]


## Risparmiare RAM

- il Kontakt caricherà tutti samples di una determinata libreria, questo occuperà più spazio nella nostra RAM. Sì la RAM, perché è una memoria veloce e quindi ci permette di suonare con più fluidità. Per poter usare solo i campioni che stiamo suonando attraverso le note, possiamo usare una funziona del Kontakt chiamata "Purge all samples" situata nell'header vicino la scritta appunto Purge.
- In alto è possibile vedere quanta RAM sta occupando il Kontakt
- Ho fatto dei test salvando il progetto e riaprendolo, e anzi il Kontakt non carica tutti i samples.
- Reference: [Kontakt Trick by Ledzyofficial | TikTok](https://www.tiktok.com/@ledzyofficial/video/7336267712487836960?_r=1&_t=8jxSkrg7RUe)


