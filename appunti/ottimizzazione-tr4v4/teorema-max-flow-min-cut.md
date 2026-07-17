---
tags:
  - category/note
  - status/finished
  - topic/ottimizzazione-combinatoria
date: 24-03-2025 16:57:35
links:
  - "[[lecture-12032025091447|Lecture 12032025091447]]"
---
# Teorema max-flow min-cut
---
## Introduzione
> Il **teorema max-flow min-cut** dice che _il valore del massimo [[flusso|flusso]] è uguale alla minima capacità dei [[taglio|tagli]]_.

## Dimostrazione
Per dimostrare il teorema ci avvaliamo dell'[[algoritmo-di-ford-fulkerson|algoritmo di Ford-Fulkerson]]. Supponiamo infatti di aver trovato il flusso massimo $x$ con tale algoritmo. Ora, prendiamo il [[taglio-s-t|taglio s-t]] $(N_{s}, N_{t})$ tale che $N_{s}$ contenga tutti i nodi raggiungibili da $s$ nel [[grafo-residuo|grafo residuo]] $G_{x}$, e $N_{t} = N \setminus N_{s}$. A questo punto, dal lemma sull'algoritmo, sappiamo che tale taglio ha proprio la capacità del flusso massimo $x$.

Segue che _questo taglio dev'essere quello di capacità minima_: se non fosse di capacità minima, allora preso un altro taglio questo verrebbe attraversato da $x$, il che violerebbe il lemma sulle capacità dei tagli.

**Qed**.

## Referenze