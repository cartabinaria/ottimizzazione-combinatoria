---
tags:
  - "#category/moc"
  - "#status/finished"
  - topic/ottimizzazione-combinatoria
date: 18-02-2025 10:28:15
---
# Ottimizzazione combinatoria
---
## Lezioni
### Ultima lezione
<!-- QueryToSerialize: TABLE WITHOUT ID file.link AS Lezione, file.inlinks AS Note FROM #category/lecture AND #topic/ottimizzazione-combinatoria SORT file.ctime DESC LIMIT 1 -->
<!-- SerializedQuery: TABLE WITHOUT ID file.link AS Lezione, file.inlinks AS Note FROM #category/lecture AND #topic/ottimizzazione-combinatoria SORT file.ctime DESC LIMIT 1 -->

| Lezione                                                           | Note                                                                                       |
| ----------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| [[lecture-05052025092115|Lecture 05052025092115]] | <ul><li>[[ottimizzazione-combinatoria|Ottimizzazione combinatoria]]</li></ul> |
<!-- SerializedQuery END -->

### Lista
<!-- QueryToSerialize: TABLE WITHOUT ID file.link AS Lezione, date AS Data FROM #category/lecture AND #topic/ottimizzazione-combinatoria  SORT file.ctime DESC -->
<!-- SerializedQuery: TABLE WITHOUT ID file.link AS Lezione, date AS Data FROM #category/lecture AND #topic/ottimizzazione-combinatoria  SORT file.ctime DESC -->

| Lezione                                                           | Data                |
| ----------------------------------------------------------------- | ------------------- |
| [[lecture-05052025092115|Lecture 05052025092115]] | 05-05-2025 09:21:15 |
| [[lecture-28042025091551|Lecture 28042025091551]] | 28-04-2025 09:15:51 |
| [[lecture-16042025091309|Lecture 16042025091309]] | 16-04-2025 09:13:09 |
| [[lecture-14042025091835|Lecture 14042025091835]] | 14-04-2025 09:18:35 |
| [[lecture-09042025091244|Lecture 09042025091244]] | 09-04-2025 09:12:44 |
| [[lecture-19032025092241|Lecture 19032025092241]] | 19-03-2025 09:22:41 |
| [[lecture-12032025091447|Lecture 12032025091447]] | 12-03-2025 09:14:47 |
| [[lecture-05032025091441|Lecture 05032025091441]] | 05-03-2025 09:14:41 |
| [[lecture-20032025131726|Lecture 20032025131726]] | 20-03-2025 13:17:26 |
| [[lecture-03032025091200|Lecture 03032025091200]] | 03-03-2025 09:12:00 |
| [[lecture-26022025091753|Lecture 26022025091753]] | 26-02-2025 09:17:53 |
| [[lecture-24022025091339|Lecture 24022025091339]] | 24-02-2025 09:13:39 |
| [[lecture-19022025091652|Lecture 19022025091652]] | 19-02-2025 09:16:52 |
| [[lecture-17022025090125|Lecture 17022025090125]] | 17-02-2025 09:01:25 |
<!-- SerializedQuery END -->

### Da processare
<!-- QueryToSerialize: TABLE WITHOUT ID file.link as Lezione, filter(file.tags, (t) => t="#status/pending" OR t="#status/ongoing") AS Status FROM #category/lecture AND #topic/ottimizzazione-combinatoria  AND (#status/pending OR #status/ongoing) SORT date DESC -->
<!-- SerializedQuery: TABLE WITHOUT ID file.link as Lezione, filter(file.tags, (t) => t="#status/pending" OR t="#status/ongoing") AS Status FROM #category/lecture AND #topic/ottimizzazione-combinatoria  AND (#status/pending OR #status/ongoing) SORT date DESC -->

| Lezione                                                           | Status                            |
| ----------------------------------------------------------------- | --------------------------------- |
| [[lecture-28042025091551|Lecture 28042025091551]] | <ul><li>#status/pending</li></ul> |
| [[lecture-05052025092115|Lecture 05052025092115]] | <ul><li>#status/pending</li></ul> |
<!-- SerializedQuery END -->


## Note
Argomenti:
- introduzione - [[problema-di-ottimizzazione|Problema di ottimizzazione]] e [[modello|Modelli]]
	- [[programmazione-lineare|Programmazione lineare]], [[programmazione-lineare-intera|Programmazione lineare intera]]
	- [[vincoli-di-assegnamento|Vincoli di assegnamento]], [[vincoli-di-semi-assegnamento|Vincoli di semi-assegnamento]], [[insiemi-ammissibili|Insiemi ammissibili]]
	- [[selezione-di-sottoinsiemi|Selezione di sottoinsiemi]], [[problema-di-copertura|Problema di copertura]], [[problema-di-partizione|Problema di partizione]], [[problema-di-riempimento|Problema di riempimento]]
	- [[variabili-a-valori-discreti|Variabili a valori discreti]]
	- [[minima-quantita-positiva-prefissata|Minima quantita' positiva prefissata]], [[funzione-con-carico-fisso|Funzione con carico fisso]]
	- [[valore-assoluto-in-problemi-di-ottimizzazione|Valore assoluto in problemi di ottimizzazione]]
	- [[funzioni-lineari-a-tratti|Funzioni lineari a tratti]]
- principali problemi - [[problema-su-rete|Problema su rete]], [[problema-di-flusso|Problema di flusso]]
	- [[taglio|Taglio]], [[taglio-s-t|Taglio s-t]], [[grafo-residuo|Grafo residuo]], [[cammino-aumentante|Cammino aumentante]]
	- [[problema-del-flusso-massimo|Problema del flusso massimo]]
		- [[algoritmo-di-ford-fulkerson|Algoritmo di Ford-Fulkerson]]
		- [[algoritmo-di-edmonds-karp|Algoritmo di Edmonds-Karp]]
		- [[algoritmo-di-goldberg-tarjan|Algoritmo di Goldberg-Tarjan]]
	- [[problema-del-flusso-di-costo-minimo|Problema del flusso di costo minimo]]
		- [[algoritmo-dei-cammini-minimi-successivi|Algoritmo dei cammini minimi successivi]]
		- [[algoritmo-di-cancellazione-dei-cicli|Algoritmo di cancellazione dei cicli]]
	- [[problema-di-accoppiamento|Problema di accoppiamento]]
- programmazione lineare - algoritmica dei problemi di ottimizzazione di programmazione lineare
	- [[algoritmi-per-la-programmazione-lineare|Algoritmi per la programmazione lineare]]
		- [[teorema-di-motzkin|Teorema di Motzkin]], [[teorema-fondamentale-della-programmazione-lineare|Teorema fondamentale della programmazione lineare]]
		- [[teoria-della-dualita|Teoria della dualita']], [[teorema-debole-di-dualita|Teorema debole di dualita']]
		- [[algoritmo-del-simplesso|Algoritmo del simplesso]]
		- [[tecnica-branch-and-bound|Tecnica branch-and-bound]]

<!-- QueryToSerialize: TABLE WITHOUT ID file.link AS Note, filter(file.tags, (t) => t="#status/pending" OR t="#status/ongoing" OR t="#status/finished") AS Status FROM #category/note AND #topic/ottimizzazione-combinatoria SORT file.ctime DESC -->
<!-- SerializedQuery: TABLE WITHOUT ID file.link AS Note, filter(file.tags, (t) => t="#status/pending" OR t="#status/ongoing" OR t="#status/finished") AS Status FROM #category/note AND #topic/ottimizzazione-combinatoria SORT file.ctime DESC -->

| Note                                                                                                                 | Status                             |
| -------------------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| [[algoritmo-dei-cammini-minimi-successivi|Algoritmo dei cammini minimi successivi]]                     | <ul><li>#status/finished</li></ul> |
| [[algoritmo-del-simplesso|Algoritmo del simplesso]]                                                     | <ul><li>#status/finished</li></ul> |
| [[direzione-di-crescita|Direzione di crescita]]                                                         | <ul><li>#status/finished</li></ul> |
| [[direzione-ammissibile|Direzione ammissibile]]                                                         | <ul><li>#status/finished</li></ul> |
| [[teorema-debole-di-dualita|Teorema debole di dualita']]                                               | <ul><li>#status/finished</li></ul> |
| [[teoria-della-dualita|Teoria della dualita']]                                                         | <ul><li>#status/finished</li></ul> |
| [[teorema-fondamentale-della-programmazione-lineare|Teorema fondamentale della programmazione lineare]] | <ul><li>#status/finished</li></ul> |
| [[teorema-di-motzkin|Teorema di Motzkin]]                                                               | <ul><li>#status/finished</li></ul> |
| [[algoritmi-per-la-programmazione-lineare|Algoritmi per la programmazione lineare]]                     | <ul><li>#status/finished</li></ul> |
| [[problema-di-accoppiamento-di-costo-minimo|Problema di accoppiamento di costo minimo]]                 | <ul><li>#status/finished</li></ul> |
| [[problema-di-accoppiamento-di-massima-cardinalita|Problema di accoppiamento di massima cardinalita']] | <ul><li>#status/finished</li></ul> |
| [[problema-di-accoppiamento|Problema di accoppiamento]]                                                 | <ul><li>#status/finished</li></ul> |
| [[algoritmo-di-cancellazione-dei-cicli|Algoritmo di cancellazione dei cicli]]                           | <ul><li>#status/finished</li></ul> |
| [[teorema-di-struttura-degli-pseudoflussi|Teorema di struttura degli pseudoflussi]]                     | <ul><li>#status/finished</li></ul> |
| [[problema-del-flusso-di-costo-minimo|Problema del flusso di costo minimo]]                             | <ul><li>#status/finished</li></ul> |
| [[algoritmo-di-goldberg-tarjan|Algoritmo di Goldberg-Tarjan]]                                           | <ul><li>#status/finished</li></ul> |
| [[algoritmo-di-edmonds-karp|Algoritmo di Edmonds-Karp]]                                                 | <ul><li>#status/finished</li></ul> |
| [[algoritmo-di-ford-fulkerson|Algoritmo di Ford-Fulkerson]]                                             | <ul><li>#status/finished</li></ul> |
| [[teorema-max-flow-min-cut|Teorema max-flow min-cut]]                                                   | <ul><li>#status/finished</li></ul> |
| [[problema-del-flusso-massimo|Problema del flusso massimo]]                                             | <ul><li>#status/finished</li></ul> |
| [[cammino-aumentante|Cammino aumentante]]                                                               | <ul><li>#status/finished</li></ul> |
| [[taglio-s-t|Taglio s-t]]                                                                               | <ul><li>#status/ongoing</li></ul>  |
| [[grafo-residuo|Grafo residuo]]                                                                         | <ul><li>#status/finished</li></ul> |
| [[taglio|Taglio]]                                                                                       | <ul><li>#status/finished</li></ul> |
| [[problema-di-flusso|Problema di flusso]]                                                               | <ul><li>#status/finished</li></ul> |
| [[flusso|Flusso]]                                                                                       | <ul><li>#status/finished</li></ul> |
| [[problema-su-rete|Problema su rete]]                                                                   | <ul><li>#status/finished</li></ul> |
| [[funzioni-lineari-a-tratti|Funzioni lineari a tratti]]                                                 | <ul><li>#status/finished</li></ul> |
| [[valore-assoluto-in-problemi-di-ottimizzazione|Valore assoluto in problemi di ottimizzazione]]         | <ul><li>#status/finished</li></ul> |
| [[funzione-con-carico-fisso|Funzione con carico fisso]]                                                 | <ul><li>#status/finished</li></ul> |
| [[minima-quantita-positiva-prefissata|Minima quantita' positiva prefissata]]                           | <ul><li>#status/finished</li></ul> |
| [[variabili-a-valori-discreti|Variabili a valori discreti]]                                             | <ul><li>#status/finished</li></ul> |
| [[problema-di-riempimento|Problema di riempimento]]                                                     | <ul><li>#status/finished</li></ul> |
| [[problema-di-partizione|Problema di partizione]]                                                       | <ul><li>#status/finished</li></ul> |
| [[problema-di-copertura|Problema di copertura]]                                                         | <ul><li>#status/finished</li></ul> |
| [[selezione-di-sottoinsiemi|Selezione di sottoinsiemi]]                                                 | <ul><li>#status/finished</li></ul> |
| [[insiemi-ammissibili|Insiemi ammissibili]]                                                             | <ul><li>#status/finished</li></ul> |
| [[vincoli-di-semi-assegnamento|Vincoli di semi-assegnamento]]                                           | <ul><li>#status/finished</li></ul> |
| [[vincoli-di-assegnamento|Vincoli di assegnamento]]                                                     | <ul><li>#status/finished</li></ul> |
| [[programmazione-lineare-intera|Programmazione lineare intera]]                                         | <ul><li>#status/finished</li></ul> |
| [[programmazione-lineare|Programmazione lineare]]                                                       | <ul><li>#status/finished</li></ul> |
| [[algoritmo-euristico|Algoritmo euristico]]                                                             | <ul><li>#status/finished</li></ul> |
| [[algoritmo-esatto|Algoritmo esatto]]                                                                   | <ul><li>#status/finished</li></ul> |
| [[problema-di-certificato|Problema di certificato]]                                                     | <ul><li>#status/finished</li></ul> |
| [[problema-di-decisione|Problema di decisione]]                                                         | <ul><li>#status/finished</li></ul> |
| [[problema|Problema]]                                                                                   | <ul><li>#status/finished</li></ul> |
| [[modello-di-simulazione|Modello di simulazione]]                                                       | <ul><li>#status/finished</li></ul> |
| [[processo-decisionale|Processo decisionale]]                                                           | <ul><li>#status/finished</li></ul> |
| [[modello-basato-su-gioco|Modello basato su gioco]]                                                     | <ul><li>#status/finished</li></ul> |
| [[problema-di-ottimizzazione|Problema di ottimizzazione]]                                               | <ul><li>#status/finished</li></ul> |
| [[modello-analitico|Modello analitico]]                                                                 | <ul><li>#status/finished</li></ul> |
| [[modello|Modello]]                                                                                     | <ul><li>#status/finished</li></ul> |
| [[rete|Rete]]                                                                                           | <ul><li>#status/finished</li></ul> |
<!-- SerializedQuery END -->



## Referenze