---
tags:
  - category/note
  - status/finished
  - topic/ottimizzazione-combinatoria
date: 27-04-2025 17:46:55
links:
  - "[[lecture-16042025091309|Lecture 16042025091309]]"
---
# Algoritmo del simplesso
---
## Introduzione
> L'**algoritmo del simplesso** e' un [[algoritmo|algoritmo]] [[iterazione|iterativo]] per la risoluzione dei problemi di [[programmazione-lineare|programmazione lineare]].

L'idea dell'algoritmo e' raccolta nei seguenti punti:
- visita in successione alcuni tra i vertici del poliedro che definisce l'insieme delle soluzioni ammissibili;
- dato un vertice $\bar{x}$ determina se e' ottimo cercando una soluzione $\bar{y}$ per il [[teoria-della-dualita|duale]] con lo stesso valore della funzione obiettivo e che sia ammissibile (usando il [[teorema-debole-di-dualita|teorema debole di dualita']]);
- nel caso in cui $\bar{x}$ non e' ottimo si costruisce una direzione ammissibile e di crescita, spostandosi fino a trovare il vincolo che costituisce un vertice; e se questo non si trova, allora il problema e' illimitato.

## Algoritmo
![[simplesso-primale.png]]

## Referenze