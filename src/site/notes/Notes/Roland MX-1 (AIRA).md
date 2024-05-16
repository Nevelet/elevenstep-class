---
{"dg-publish":true,"permalink":"/notes/roland-mx-1-aira/"}
---

Links:: [[Notes/Roland\|Roland]]

---

- [ROLAND MX-1 (AIRA) | Strumenti Musicali .net](https://www.strumentimusicali.net/product_info.php/products_id/51797/roland-mx-1-aira.html)
- [Roland - MX-1 | Mix Performer](https://www.roland.com/global/products/mx-1/)


## AIRA LINK

[MX-1: Che tipo di dispositivi possono essere collegati al terminale AIRA LINK (ingresso USB) dell'MX-1?](https://support.roland.com/hc/en-us/articles/360060655791-MX-1-What-kind-of-devices-can-be-connected-to-the-AIRA-LINK-terminal-USB-input-of-the-MX-1)

**AIRA LINK USB** di Roland, permette di far passare sia l'audio che il MIDI.

> AIRA LINK è una funzionalità rivoluzionaria che consente di collegare dispositivi della serie AIRA come TR-8, TB-3 e SYSTEM-1 all'MX-1 e inviare e ricevere informazioni audio/MIDI utilizzando un singolo cavo USB. L'MX-1 è dotato di quattro porte AIRA LINK, quindi puoi collegare un totale di quattro dispositivi con un solo cavo USB. — [Roland - Blog - Information - 【INFO】Mix Performer MX-1 活用術 -AIRA LINK編-](https://blog.roland.jp/info/mx1-airalink/)

## Cambiare il Sample Rate

- [MX-1: Changing the Sampling Rate – Roland Corporation](https://support.roland.com/hc/en-us/articles/205215985-MX-1-Changing-the-Sampling-Rate)

## Altre informazioni

**MX-1 USB 1 (CTRL)**
Sono abbastanza sicuro che l'opzione CTRL in USB sia da utilizzare quando ci si connette a un editor o per il controllo DAW. Questa linea non invia note MIDI, solo messaggi CC e SysEx, quindi penso che il punto sia che consente di mantenere i dati delle note separati da qualsiasi dato di controllo pesante (specialmente SysEx) che potrebbe passare tra il prodotto e il computer. Tendo a non utilizzare la porta CTRL poiché per quello che sto facendo è sufficiente la porta USB-1 standard.

## MX1 & Ableton

- [Ableton Live Performance Made Easy With New AIRA MX-1 Mode - Roland Resource Centre](https://rolandcorp.com.au/blog/aira-mx-1-ableton-live)
- [Roland MX-1 Ultimate Setup Guide - Ableton Live - YouTube](https://youtu.be/ZDYsF9HJzNM)
- [Roland MX-1 MIDI Ableton Live setup guide - YouTube](https://youtu.be/sqW1FYgXJbU)

## Manuali, Guide e Tutorial

**Manuali:**
- [English MX-1 Supplementary Manual](https://static.roland.com/assets/media/pdf/MX-1_LiveMode_e01.pdf)
- [Manuale Italiano.pdf](https://static.roland.com/assets/media/pdf/MX-1_i01_W.pdf)
- [Roland - The Ultimate Guide To The AIRA MX-1 Mix Performer](https://www.roland.com/uk/blog/aira-mx-1-ultimate-guide/)

**Video:**
- [AIRA Start - MX-1 (a short tutorial) - YouTube](https://youtu.be/nEkV0CnKehM)

## Routing (I/O)

![image|500](https://shop.niccolaimusica.it/13598-thickbox_default/roland-mx-1-aira.jpg)

- 17/18 è l'uscita che viene collegata al computer
- ha 4 mono e le altre stereo
- MX-1 (è l'uscita/entrata MIDI)

## Modalità

[AIRA Start - MX-1 (a short tutorial) - YouTube](https://youtu.be/nEkV0CnKehM?t=421)

Tenendo premuto il tasto GAIN mentre si accende, entra in modalità impostazioni.

- Mix (ogni traccia corrisponde allo strumento collegato all'ingresso)
- Sur (Funziona come controller MIDI per la tua DAW)
- External (l'MX-1 invia tutto l'audio direttamente alla tua DAW. I 18 canali dell'MX-1 controllano 18 tracce della tua DAW)
- Live Mode

### External Mixing Mode:

1. Tenendo premuto il pulsante [GAIN], accendere l'MX-1.
2. Premere il pulsante [TONE].
3. Ruotare la manopola [VALUE] per impostare la modalità mixer su [EXT].
4. Premere il pulsante [START/STOP] per salvare le impostazioni.
_Le impostazioni vengono salvate e l'MX-1 si riavvia._

**Per passare alla MODALITÀ ABLETON LIVE**
1. Accedere alla modalità EXT.
2. Tenere premuto il pulsante [RECALL] dell'MX-1 e premere il pulsante [STORE].

*Se si desidera tornare alla MODALITÀ MIXING ESTERNO, tenere premuto il pulsante [RECALL] e premere nuovamente il pulsante [STORE].

## Impostazioni di sincronizzazione

1. Premere il pulsante [SYNC] per accenderlo.
2. Ruotare la manopola [TEMPO] per selezionare il clock master MIDI. Il clock master selezionato lampeggia nel display sopra la manopola [TEMPO].

|        |                                                                                                                                                                                                                     |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AUTO   | Se un clock MIDI viene immesso da un dispositivo collegato, l'MX-1 si sincronizza con quel clock MIDI. Se vengono immessi più clock MIDI, MX-1 dà priorità alla porta USB, al connettore MIDI IN, quindi a USB 1-4. |
| INT    | L'MX-1 è il master del clock MIDI.                                                                                                                                                                                  |
| MIDI   | L'MX-1 si sincronizza con il clock MIDI del dispositivo collegato al connettore MIDI IN.                                                                                                                            |
| USB1–4 | L'MX-1 si sincronizza con il clock MIDI del dispositivo collegato alle porte USB HOST.                                                                                                                              |
| PC     | L'MX-1 si sincronizza con il clock MIDI  <br>specificato dal DAW in esecuzione sul computer collegato alla porta USB.                                                                                               |
|        |                                                                                                                                                                                                                     |

3. Premere il pulsante [SYNC] per confermare il clock master.


**Manuale:** 
- [MX-1: Sync Settings – Roland Corporation](https://support.roland.com/hc/en-us/articles/204590069-MX-1-Sync-Settings)
**Video:**
- [How to setup the Sync Function on the Roland MX-1 - YouTube](https://www.youtube.com/watch?v=IMMnmQyThBw)


