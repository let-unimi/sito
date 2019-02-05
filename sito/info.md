## Informazioni sul corso

### Orario e modalità delle lezioni

Le lezioni del corso si tengono il **martedì** alle ore **10:30 – 12:30** in
[Aula 109](https://orari-be.divsi.unimi.it/EasyRoom//index.php?content=gestore_aree_pubblico&cercaSede=3>)
e il **giovedì** alle ore **11:30 – 13:30** in
[Aula Alfa](https://orari-be.divsi.unimi.it/EasyRoom//index.php?content=gestore_aree_pubblico&cercaSede=79);
la lezione del martedì può estendersi fino alle 14:30 nel caso di approfondimenti pratici, o **esercitazioni**.

Le lezioni (ed esercitzioni) sono **frontali**, nell'attuale manifesto degli
studi il corso *non prevede un laboratorio*; per questa e [altre ottime
ragioni](https://cs.brown.edu/courses/cs019/2018/laptop-policy.html) in classe è
**vietato l'uso di laptop** e strumenti analoghi.

### Obiettivi dell’insegnamento

La teoria dei **linguaggi** formali è una delle discipline centrali
dell'informatica; l'uso delle *grammatiche* da essa studiate non solo permette
di definire in modo conciso ed esatto insiemi infiniti (come ad esempio: i
programmi sintatticamente corretti, i documenti HTML validi, i file XML ben
formati, gli indirizzi email o le URL aderenti allo standard), ma consente anche
vari tipi di trattamento automatico dei medesimi. In particolare, permette di
definire **traduttori** che, sfruttando la struttura grammaticale, conseguono
obiettivi di grande complessità ed utilità (come, ad esempio: la compilazione,
interpretazione e transpilazione del codice, l'individuazione di errori di
programmazione, l'estrazione di informazioni strutturate…).

Questo insegnamento ha per obiettivo l'apprendimento degli aspetti *teorici* e
*algoritmici* dei linguaggi formali coinvolti nelle attività di definizione e
uso delle grammatiche, analisi e traduzione e di metterli in *pratica*
attraverso la realizzazione di programmi concreti relativi a semplici casi di
studio.

### Risultati di apprendimento attesi

A seguito del superamento dell'esame, lo studente:

* conosce le principali nozioni riguardanti i linguaggi regolari e liberi dal
  contesto,
* conosce le tecniche di analisi lessicale e sintattica di base e la loro
  implementazione pratica,
* conosce alcuni rudimenti del funzionamento di interpreti, transpilatori e più
  in generale di traduzione tra formati strutturati;

inoltre è in grado di:

* definire una grammatica (regolare, o libera dal contesto) per descrivere
  semplici linguaggi di uso comune,
* utilizzare uno strumento di costruzione automatica di analizzatori lessicali e
  sintattici,
* scrivere il codice necessario a realizzare semplici traduttori.

### Argomenti trattati

Riguardo all'ambito generale dei linguaggi formali:

* nozioni di base: alfabeto, linguaggio, grammatica;
* gerarchia di Chomsky, con particolare riferimento a linguaggi regolari e
  liberi dal contesto (e relative forme normali);
* riconoscimento e generazione: derivazioni, ambiguità, alberi sintattici;
* automi a stati finiti e a pila, deterministici e non.

Riguardo agli aspetti legati alla traduzione:

* analisi lessicale e divisione in *token*: espressioni regolari, relazione con
  gli automi a stati finiti;
* analisi grammaticale e *parsing*: tecniche generali non direzionali, tecniche
  generali direzionali (*top-down* e *bottom-up*), tecniche deterministiche
  (grammatiche *LL* e *LR*);
* interpreti transpilatori e traduttori: nozioni di base, grammatiche con
  attributi, pattern generali.

### Prerequisiti

Di seguito sono elencate alcune conoscenze preliminari che è bene aver acquisito
*in modo solido* prima di apprestarsi a seguire le lezioni:

* tecniche di dimostrazione, con particolare riguardo a quella per *induzione*
  [dagli insegnamenti di "Matematica del discreto" e/o "Logica matematica"];
* programmazione, con particolare riguardo alla *ricorsione* [dal corso di
  "Programmazione"];
* strutture dati elementari (liste, pile, code e dizionari); *grafi* e *alberi*
  e relativi *algoritmi di visita* (ampiezza, profondità…) [dal corso di
  "Algoritmi e strutture dati"];
* aspetti di base dei linguaggi formali [dal corso "Linguaggi formali e
  automi"].

### Modalità di valutazione

L'insegnamento non prevede prove in itinere. La prova finale è costituita da un
**colloquio orale** in cui il candidato deve dimostrare:

* la conoscenza delle definizioni e delle nozioni teoriche fondamentali, e la
  comprensione del funzionamento dei vari algoritmi di analisi lessicale e
  sintattica e traduzione;
* la capacità di applicare tale conoscenza a un semplice caso concreto, sia in
  relazione agli aspetti grammaticali che algoritmici;
* la capacità di utilizzare uno strumento per la generazione automatica di
  analizzatori e/o traduttori.

La prova orale può essere accompagnata da un **progetto** software da realizzare
in modo autonomo, o in gruppo, come concordato assieme al docente nell'arco
delle lezioni.

### Bibliografia

I testi di riferimento per la parte teorica ed algoritmica del corso sono:

* Dick Grune e Ceriel J. H. Jacobs (2008),
  [Parsing Techniques. A Practical Guide](https://doi.org/10.1007/978-0-387-68954-8), *Springer*, New York;

* Terence Parr (2009),
  [Language Implementation Patterns](https://pragprog.com/book/tpdsl/language-implementation-patterns), *The Pragmatic Bookshelf*.

La maggior parte del materiale sarà tratta dai primi capitoli del primo libro
(di cui è possibile scaricare una versione PDF gratuita dalla rete dell'Ateneo,
nei termini della licenza d'uso stabilita dall'editore); il secondo testo tratta
aspetti più pratici e legati allo strumento di costruzione automatica di
analizzatori lessicali e sintattici utilizzato nel corso.

Come approfondimento individuale, con maggior orientamento alla parte di
costruzione di interpreti e compilatori, si consiglia

* Dick Grune, Kees van Reeuwijk, Henri E. Bal, Ceriel J.H. Jacobs e Koen Langendoen (2012)
  [Modern Compiler Design](https://doi.org/10.1007/978-1-4614-4699-6), *Springer*, New York;

mentre per quanto concerne lo strumento di costruzione automatica di
analizzatori lessicali e sintattici, il testo di riferimento è:

* Terence Parr (2013),
  [The Definitive ANTLR 4 Reference](https://pragprog.com/book/tpantlr2/the-definitive-antlr-4-reference), *The Pragmatic Bookshelf*.

Un testo di riferimento per i linguaggi formali, utile come approfondimento, o
per colmare eventuali lacune rimaste dal corso di "Linguaggi formali", è il
classico:

* John E. Hopcroft, Rajeev Motwani, e Jeffrey D. Ullman (2007),
  [Introduction to Automata Theory, Languages, and Computation](https://www.pearson.com/us/higher-education/program/Hopcroft-Introduction-to-Automata-Theory-Languages-and-Computation-3rd-Edition/PGM64331.html), *Pearson*.

Ci sono validi testi in italiano che riguardano sia la parte dei linguaggi
formali che quella di analisi e traduzione, come:

* Stefano Crespi Reghizzi, Luca Breveglieri e Angelo Morzenti (2015), [Linguaggi formali e compilazione](https://www.editrice-esculapio.com/s-crespi-reghizzi-l-breveglieri-a-morzenti-linguaggi-formali-e-compilazione/), *Esculapio*;

* John E. Hopcroft, Rajeev Motwani,  e Jeffrey D. Ullman [Automi, linguaggi e calcolabilità](https://www.pearson.it/opera/pearson/0-6576-automi_linguaggi_e_calcolabilita), *Pearson*;

sono suggeriti solo per chi avesse seri problemi con la lingua inglese, per
tutti gli altri studenti si raccomanda l'uso dei volumi sopra citati.
