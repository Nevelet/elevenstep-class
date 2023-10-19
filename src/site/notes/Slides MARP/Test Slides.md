---
{"dg-publish":true,"permalink":"/slides-marp/test-slides/"}
---



<style >
h2#descrizione {
  display: none
}
</style>

## Cosa sono i Decibel


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/notes/decibel-d-b/#1d5d44" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



Il decibel (simbolo: dB) è un’unità di misura relativa corrispondente a un decimo di bel. Viene usato per esprimere il rapporto tra un valore di una potenza o quantità di campo rispetto a un altro, su una scala logaritmica.  

</div></div>



---

<!-- .element: style="font-size: 40px" -->
## Cos'è il LUFS


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/notes/lufs/#d040ce" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



“Loudness unit in reference at full scale” “Unità sonora di riferimento a fondo scala” è un'evoluzione del sistema RMS, e come lui misura "l'average" del segnale e non i picchi. 

</div></div>
 


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/notes/lufs/#6a2a89" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



==I LUFS sono sensibili intorno alle medio alte==, alte frequenze, come le nostre orecchie.
A proposito della sensibilità del nostro orecchio, qui troverai una pagina sulle curve isofoniche, per capire in quale frequenze siamo più sensibili in base al volume. Eccola: [[Curve Isofoniche\|Curve Isofoniche]] 

</div></div>
 

---

<!-- .element: style="font-size: 35px" -->
## Cosa sono i Peak Meter


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/notes/peak-meter/#descrizione" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





<!-- headingDivider: 2 -->
<!-- headingDivider: 3 -->

## Descrizione

I Peak Meter sono strumenti di misura utilizzati per visualizzare il livello di picco di un segnale audio. Sono spesso presenti sui mixer audio, sui software di registrazione e produzione musicale, sui processori di segnale e su altri dispositivi audio. Grazie ai Peak Meter è possibile controllare la saturazione del segnale e prevenire la distorsione, mantenendo così una qualità audio ottimale. I Peak Meter possono essere rappresentati da indicatori a barre o da un display a LED.

## Notes

La misurazione di picco è progettata per rispondere rapidamente in modo che il display del misuratore reagisca esattamente in proporzione alla tensione del segnale audio. I misuratori di picco sono anche molto utili quando si verifica una potenziale distorsione di clipping causata da un segnale che supera i 0 dBFS.

Per calibrare un plug-in VU meter nel mondo digitale e ottenere un riferimento dBfs da abbinare a 0VU imposta su -18 dBfs = 0VU ed otterrai circa 18 dB di headroom (approssimativamente).

---
Quando si effettuano registrazioni audio è preferibile utilizzare un livello di registrazione che sia appena sufficiente per raggiungere la massima capacità del registratore ai suoni più forti, indipendentemente dal livello medio del suono. La misurazione del livello di peak \[picco\] è utile per monitorare improvvisi cambiamenti di livello e alterare i sovraccarichi digitali, che è fondamentale per evitare il clipping del segnale.

---
Tuttavia, la misurazione del peak non ti darà un’indicazione adeguata del volume percepito. I misuratori di PPM sono migliori per il monitoraggio dei transitori e vengono spesso utilizzati per trovare suoni che spuntano in modo da poter effettuare regolazioni che li mantengono a livelli più coerenti.




</div></div>
