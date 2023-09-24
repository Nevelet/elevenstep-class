---
{"dg-publish":true,"permalink":"/notes/d-bfs/"}
---


0 dBFS è il segnale audio digitale più alto possibile che il sistema può gestire senza causare il clip digitale.

A differenza delle scale audio analogiche come dBV e dBu in cui il segnale può essere spinto oltre 0 dB senza causare distorsioni di [[Notes/Clipping\|Clipping]], l'audio digitale ha un soffitto rigido che non consente alcun headroom oltre 0 dBFS.

Per evitare il clipping digitale, è buona pratica mantenere i livelli ben al di sotto di 0 dBFS per darti abbastanza headroom.