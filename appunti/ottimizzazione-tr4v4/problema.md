---
tags:
  - category/note
  - status/finished
  - topic/ottimizzazione-combinatoria
  - topic/informatica-teorica
date: 23-02-2025 13:43:20
links:
  - "[[lecture-17022025090125|Lecture 17022025090125]]"
  - "[[lecture-16022026120505|Lecture 16022026120505]]"
  - "[[lecture-18022026140350|Lecture 18022026140350]]"
---
# Problema
---
## Introduzione
> Un **problema** e' una _domanda espressa in termini generali_, ma la cui _risposta dipende da un certo numero di parametri e variabili_. Formalmente, un problema $\mathcal{P}$, viene descritto tramite:
> - _parametri e variabili_;
> - _caratteristiche delle soluzioni_;
> 
> Ancora piu' formalmente, nell'ambito dell'informatica teorica, un problema viene definito come una _[[relazione|relazione]] binaria tra stringhe, la cui prima viene detta `input` e la seconda `output`_.

Per esempio, il problema della _somma_ contiene la tupla $<(2, 3), 5>$.

## Caratterizzazione
Non vogliamo pero' elencare, in modo estensionale, le infinite tuple di un problema, ma _cercare di catturare la sua essenza in modo intensionale_...

Quando caratterizziamo un problema, allora, definiamo 3 principali elementi:
- cos'è l'**input**, e come viene rappresentato;
- cos'è l'**output**, e come viene rappresentato;
- che **relazione** c'è **tra l'input e l'output**;

<u>Nota bene</u>: non c'e' la domanda "come ottengo l'output dall'input", perche' _il problema non ci chiede il modo in cui realizzare l'[[algoritmo|algoritmo]] che calcola la sua relazione_.

## Famiglie
I problemi formali si dividono in 2 grandi macro-famiglie:
- [[problema-di-ricerca|problemi di ricerca]];
- [[problema-di-decisione|problemi di decisione]];

### Equivalenza
La grande distinzione tra queste due famiglie di problemi, in realta', e' solo apparente. Infatti partiamo col dire che _possiamo certamente associare ad ogni problema di ricerca un rispettivo problema di decisione_. E poi, si puo' dimostrare che quasi sempre:
- **se un problema di ricerca e' facile, allora anche la sua variante di decisione e' facile** (triviale);
- **se un problema di ricerca e' difficile, allora anche la sua variante di decisione dovra' essere difficile** (non triviale affatto!);

Di conseguenza, data questa proprieta', **gli studi si concentrano principalmente sui problemi di decisione**, cui formulazione e' oggettivamente piu' semplice.

### Focus
I problemi di decisione sono tanti, e alcuni anche molto complessi. Vogliamo un sistema formale che ci consenta di rappresentare i problemi in modo semplice, unico e completo: i [[linguaggio-formale|linguaggi formali]].

L'idea e' semplice:
> **Ogni problema di decisione puo' essere ricondotto al riconoscimento di uno specifico linguaggio**.

Per questa ragione possiamo concentrarci sul **problema della decisione di un linguaggio**, vale a dire nel _chiedersi, dato un linguaggio $L$ fissato, se e' vero o no che una stringa $w \in L$_.

Per esempio, il problema di decisione del decidere se nel [[grafo|grafo]] $g$ e' presente un percorso tra il nodo $s$ e il nodo $t$, e' formalizzabile nel linguaggio:
$$<path=\{<g, s, t> | \text{g è un grafo, s e t sono nodi del grafo g ed esiste un percorso da s a t}\}>$$

Grazie a questo passaggio nel mondo dei linguaggi formali, riusciamo con facilita' e formalita' a determinare [[calcolabilita|calcolabilita']] e [[complessita|complessita']] di ogni problema.

In particolare, lo strumento che useremo per decidere i linguaggi, saranno ovviamente gli **[[automa|automi]], e in particolare le [[macchina-di-turing|macchine di Turing]]: letteralmente i nostri algoritmi risolutivi**!

## Istanze
Un'**istanza** del problema $\mathcal{P}$ si ottiene _specificando dei valori concreti per tutti i parametri del problema, ma non per le variabili_. Ricorda infatti che:
- **i parametri sono i dati del problema**, che definiscono la sua istanza;
- **le variabili sono le incognite del problema**, che definiscono le sue soluzioni.

Per esempio, il problema $ax^2+bx+c=0$ puo' avere come istanza $5x^2+3x+1=0$.

## Descrizione
Per descrivere un problema $\mathcal{P}$ si costruisce l'**insieme delle sue soluzioni ammissibili $\mathbb{F}_{\mathcal{P}}$**. Di solito $\mathbb{F}_{\mathcal{P}} \subseteq \mathbb{G}$, e si trova specificando dei vincoli che un generico $g \in \mathbb{G}$ deve soddisfare per far parte di $\mathbb{F}_{\mathcal{P}}$. Gli elementi che appartengono a **$\mathbb{G} \setminus \mathbb{F}_{\mathcal{P}}$ sono detti soluzioni non ammissibili**.

Per esempio, la descrizione di un'istanza di un problema puo' essere la seguente:
$$5x^{2}-6x+1=0 \implies \begin{array}{align} \mathbb{G}=\mathbb{R} \\ \mathbb{F}_{\mathcal{P}} = \{x\in\mathbb{G}\ | \ 5x^{2}-6x+1=0\}\end{array}$$

## Referenze
- [[problema-decidibile|Problema decidibile]]
- [[problema-indecidibile|Problema indecidibile]]