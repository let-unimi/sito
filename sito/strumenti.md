## Strumenti e materiale di supporto

Questa pagina contiene alcune indicazioni circa il [linguaggio di
programmazione](#python) e lo strumento di [generazione automatica di
analizzatori lessicali e sintattici](#antlr) adottati per il corso; in futuro
conterrà anche del materiale specifico di supporto al corso, come alcune
dispense integrative e strumenti software sviluppati dal docente.

Si osserva che, data la *maturità culturale* che ci si attende dagli studenti
che frequentano un insegnamento complementare, il docente **non intende fornire
alcun supporto** all'installazione, configurazione e uso pratico degli strumenti
qui descritti.


### Python

Gli algoritmi illustrati a lezione saranno presentati attraverso una loro
implementazione elementare in [Python 3](https://www.python.org/), la scelta del
linguaggio è dovuta sia per alla sua *leggibilità*, che per alla disponibilità
di *strutture dati elementari* (come liste, pile, code e dizionari…) nella sua
libreria standard.

Chi non conosce il linguaggio può facilmente apprendere quanto necessario
all'uso che ne verrà fatto in questo insegnamento leggendo i primi cinque
capitoli da "[The Python Tutorial](https://docs.python.org/3/tutorial/index.html)" 
reperibile sul sito della [documentazione ufficiale](https://docs.python.org/3/) 
del linguaggio.


### ANTLR

Una volta investigati gli algoritmi di base per l'analisi lessicale e sintattica
verrà introdotto uno strumento di generazione automatica per tali analizzatori.
Lo strumento scelto è [ANTLR](http://www.antlr.org/), originariamente ideato e
sviluppato da [Terence Parr](https://parrt.cs.usfca.edu/). 

La documentazione necessaria al suo uso (oltre ai libri indicati nella
[bibliografia](info#bibliografia) delle informazioni generali sul corso) può
essere reperita gratuitamente nel [repository
ufficiale](https://github.com/antlr/antlr4/blob/master/doc/index%2emd), in
particolare può risultare utile la lettura della guida "[Getting
Started](https://github.com/antlr/antlr4/blob/master/doc/getting-started%2emd)" e
delle indicazioni sull'uso del [target per Python
3](https://github.com/antlr/antlr4/blob/master/doc/python-target%2emd), così come
il [repository della versione Python
3](https://github.com/jszheng/py3antlr4book) dei programmi di esempio contenuti
nel libro "[The Definitive ANTLR 4
Reference](https://pragprog.com/book/tpantlr2/the-definitive-antlr-4-reference)".