---
{"dg-publish":true,"permalink":"/3-resources/music-production/oversampling/"}
---

Links: [[3. Resources/Music Production/Teoria del Suono\|Teoria del Suono]], [[3. Resources/Music Production/Resampling Audio\|Resampling Audio]]

---
## Cos'è

L'oversampling audio **è una tecnica utilizzata nella registrazione e riproduzione audio digitale per migliorare la qualità del suono.** Consiste nel campionare il segnale audio a una frequenza più elevata rispetto alla [[3. Resources/Music Production/Audio/Frequenza di Campionamento\|Frequenza di Campionamento]] originale, solitamente almeno il doppio della frequenza originale. Questo processo permette di ridurre l'effetto dell'[[3. Resources/Music Production/Aliasing\|Aliasing]], ovvero la distorsione causata dalla presenza di [[3. Resources/Music Production/Frequenze\|Frequenze]] superiori alla metà della frequenza di campionamento. Inoltre, l'oversampling può ridurre il rumore e migliorare la risposta in frequenza del sistema audio digitale.

![Oversampling.png](/img/user/3.%20Resources/Images/Oversampling.png)
_source: [How Does Oversampling Sound? - The Science of Sound](https://science-of-sound.net/2016/07/how-does-oversampling-sound/)_

Una tecnica nota con il nome di sovracampionamento (oversampling) viene solitamente usata nelle conversioni audio, specialmente nell'output. L'idea consiste nell'usare una frequenza di campionamento superiore, in modo che un filtro digitale quasi-ideale possa abbassare l'alias fino alla frequenza di Nyquist, mentre un filtro analogico più semplice può bloccare le frequenze superiori ad una nuova più alta frequenza di Nyquist. — [Wikipedia](https://it.wikipedia.org/wiki/Filtro_anti-alias)

L'obiettivo del sovracampionamento è quello di abbassare i requisiti del filtro anti-alias, o ridurre l'aliasing stesso. Dal momento che il filtro finale è analogico, il sovracampionamento permette al filtro di essere più economico visto che i requisiti non sono così rigidi, ed allo stesso tempo permette al filtro di avere una frequenza di risposta più dolce, e quindi una risposta con una fase meno complessa.


![image|500](https://theproaudiofiles.com/wp-content/uploads/2021/02/aliasing.png)
_source: [Oversampling in Digital Audio: What Is It and When Should You Use It? — Pro Audio Files](https://theproaudiofiles.com/oversampling/)_


![image](https://www.malabdali.com/wp-content/uploads/2021/08/reconstructing-the-original-signal.jpg)


## Notes

- sovracampionamento
- Oversampling soltanto in elaborazione

## Resources

- [OVERSAMPLING spiegato in pratica, cosa fa e quando devi usarlo - YouTube](https://www.youtube.com/watch?v=uPY4A8YtY4w)

## Related Notes

- [[3. Resources/Music Production/Differenza tra Resampling e Oversampling\|Differenza tra Resampling e Oversampling]]
- [[3. Resources/Music Production/Resampling Audio\|Resampling Audio]]
- [[3. Resources/Music Production/Teorema del Campionamento (Nyquist Shannon)\|Teorema del Campionamento (Nyquist Shannon)]]
- [[3. Resources/Music Production/Audio/Frequenza di Campionamento\|Frequenza di Campionamento]]
- [[3. Resources/Music Production/True Peak\|True Peak]]

