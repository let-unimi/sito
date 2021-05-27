Diario delle lezioni
====================

Potete trovare informazioni sulle modalità d'esame e sull'elenco degli argomenti
che costituiscono il programma nella pagina di :doc:`info`,

Il seguente diario riporta gli *argomenti* e il *materiale didattico e di
supporto* relativo sia alle **lezioni già svolte** (riguardo alle quali
costituisce il programma d'esame *de facto*), che alle lezioni **ancora da
svolgere**, per le quali è *da intendersi del tutto indicativo* (sia riguardo
alle date che al contenuto). Le lezioni si svolgono di norma dalle 11:30 alle
13:30.

.. admonition:: Lezioni sincrone e registrate
   :class: alert alert-secondary

   È possibile assistere alle lezioni in modalità **sincrona** tramite l'invito
   Zoom `http://bit.ly/lezioni-let-unimi <http://bit.ly/lezioni-let-unimi>`__
   (a cui possono collegarsi gli utenti registrati con email
   :samp:`@studenti.unimi.it`); nel `canale YouTube <http://bit.ly/3cB9snQ>`__
   dell'insegnamento è inoltre disponibile la *playlist* delle **registrazioni**
   delle `lezioni <http://bit.ly/3seGlhb>`__ (e la diretta della lezione
   corrente).

Il materiale didattico indicato come *TPT* si riferisce al documento `The Python
Tutorial <https://docs.python.org/3/tutorial/index.html>`_, quello indicato con
*PT* si riferisce al libro di testo `Parsing Techniques. A Practical Guide
<https://doi.org/10.1007/978-0-387-68954-8>`_, quello indicato con *ICD* al
libro `Introduction to Compiler Design
<https://doi.org/10.1007/978-3-319-66966-3>`__, e quello indicato con *DAR* a
`The Definitive ANTLR 4 Reference
<https://pragprog.com/book/tpantlr2/the-definitive-antlr-4-reference>`__; il
materiale indicato come *H* si riferisce agli `Handout
<https://github.com/let-unimi/handouts/>`__ del docente; si veda la nota sui
:ref:`numeri di sezione <numeridisezione>` che reca indicazioni su quali parti
del materiale sono **parte del programma** e quali *letture consigliate, ma
facoltative*.

|

  .. table::

    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | Num   | Data       | Argomento                                                      | Materiale didattico                                                 |
    +=======+============+================================================================+=====================================================================+
    | 1     | Gio  4/3   | Administrivia; introduzione a Python                           | `PT 1`_; `TPT 3`_, `TPT 4`_ 1-6 e `TPT 5`_; `H 1`_                  |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 2     | Mar  9/3   | Strutture dati ed algorimi elementari su alberi e grafi        | `H 2`_                                                              |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 3     | Gio 11/3   | Richiami su grammatiche e linguaggi                            | `PT 2`_ 1-4, [5-8], [10-12]; `H 3`_                                 |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 4     | Mar 16/3   |                                                                | `PT 2`_ 9; `PT 3`_ 1; `H 4`_                                        |
    +-------+------------+ Introduzione al *parsing*                                      +---------------------------------------------------------------------+
    | 5     | Gio 18/3   |                                                                | `PT 3`_ 2, 3, 4.1-3, [4.4-5], 5.1-5, [8-10]; `H 5`_                 |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 6     | Mar 23/3   |                                                                | `PT 4`_ 2.1-2; `H 6`_                                               |
    +-------+------------+ Parsing, caso generale non direzionale (*CYK*)                 +---------------------------------------------------------------------+
    | 7     | Gio 25/3   |                                                                | `PT 4`_ 2.3-7; `H 7`_                                               |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 8     | Mar 30/3   | Linguaggi regolari e automi a stati finiti                     | `PT 5`_ 1-5, [7-9]; `H 8`_                                          |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 9     | Mar 13/4   |                                                                | `PT 6`_ 1-3, 5; `H 9`_                                              |
    +-------+------------+ Parsing Top-Down (*Pushdown Automata*, *Recursive descent*)    +---------------------------------------------------------------------+
    | 10    | Gio 15/4   |                                                                | `PT 6`_ 4, 6.1; `H 10`_                                             |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 11    | Mar 20/4   | Parsing Bottom-up                                              | `PT 7`_ 1; `H 11`_                                                  |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 12    | Gio 22/4   |                                                                | `PT 8`_ 1-2.1; `H 12`_                                              |
    +-------+------------+ Parsing deterministico Top-Down (*LL*)                         +---------------------------------------------------------------------+
    | 13    | Mar 27/4   |                                                                | `PT 8`_ 2.2-6; `H 13`_                                              |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 14    | Gio 29/4   | Parsing deterministico Bottom-Up (*LR*)                        | `PT 9`_ 5 - 5.3; `H 14`_                                            |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 15    | Mar  4/5   |                                                                | DAR 1-2, 9.1-2; `H 15`_                                             |
    +-------+------------+ ANTLR: grammatiche, tokenizer, parser (*visitor* e *listener*) +---------------------------------------------------------------------+
    | 16    | Gio  6/5   |                                                                | DAR 3-4; `H 16`_                                                    |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 17    | Mar 11/5   | Dall'albero di parsing all'AST                                 | `H 17`_                                                             |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 18    | Gio 13/5   | Traduzioni orientate ai dati                                   | [DAR 8]; `H 18`_                                                    |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 19    | Mar 18/5   | Traspilazione (verso Javascript e l'*AST* di Python)           | `H 19`_                                                             |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 20    | Gio 20/5   | Symbol table (e *scoping*)                                     | ICD 3; [DAR 8.4; MCD 2.11]; `H 20`_                                 |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 21    | Mar 25/5   | Interpreti ricorsivi (e *funzioni*)                            | ICD 4; [MCD 6.1-2]; `H 21`_                                         |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 22    | Gio 27/5   | Type checking (statico per tipi primitivi)                     | ICD 5; `H 22`_                                                      |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 23    | Mar  1/6   | Interpreti iterativi (*code threading* e VM a pila)            | MCD 5.1, 6.3                                                        |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 24    | Gio  3/6   | Generazione di codice (con l'*IR* di *LLVM*)                   | ICD 6                                                               |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+

|

.. admonition:: Nota bene
  :class: alert alert-secondary

  Accanto a ciascun riferimento che reca un numero di *capitolo* possono trovarsi
  dei *numeri di sezione* essi sono da intendersi nel seguente modo:

  .. _numeridisezione:

  * se assenti: l'*intero capitolo è parte del programma* (ad esempio, con "`TPT 5`_" si intende
    l'intero capitolo 5 di `The Python Tutorial`_),

  * se presenti (fuori parentesi): solo *le sezioni indicate sono parte del programma* (ad esempio,
    con "`PT 2`_ 1-4, 9" si intende che del capitolo 2 di `Parsing Techniques. A Practical Guide`_
    sono strettamente parte del programma solo le sezioni 1, 2, 3, 4 e 9),

  * se presenti tra parentesi quadre: le  *sezioni indicate sono letture caldamente raccomandate,
    ma facoltative* (ad esempio con "`PT 2`_ [5-8, 10-12]" si intende che del capitolo 2 di
    `Parsing Techniques. A Practical Guide`_ è consigliata la lettura delle sezioni 5, 6, 7, 8,
    10, 11 e 12).

|

  .. _H 1: https://github.com/let-unimi/handouts/blob/f5ee884bd5ae4b7846eb5eb6b3b16879ae6aad95/L01.ipynb
  .. _H 2: https://github.com/let-unimi/handouts/blob/500cafd2acc199a2115c6009ddacd7d05f317094/L02.ipynb
  .. _H 3: https://github.com/let-unimi/handouts/blob/88c5c6d4a88ebccbd741b7f67d0bae75ca3a5b49/L03.ipynb
  .. _H 4: https://github.com/let-unimi/handouts/blob/38b08aa519a8ac6a77cdcd3ea61e025450cf23a8/L04.ipynb
  .. _H 5: https://github.com/let-unimi/handouts/blob/39b69b9faca50a48179925067206ee0310c66642/L05.ipynb
  .. _H 6: https://github.com/let-unimi/handouts/blob/58d1ce62e448feb966cd9bb1c0b37120d415a018/L06.ipynb
  .. _H 7: https://github.com/let-unimi/handouts/blob/732da9c5ccbac86da28b400f98674c43c7c92273/L07.ipynb
  .. _H 8: https://github.com/let-unimi/handouts/blob/718a867b221fe03eac1d23c736f9f3e17b547a8e/L08.ipynb
  .. _H 9: https://github.com/let-unimi/handouts/blob/826ce662546163efb97557a8dd88d7993fb9e3d7/L09.ipynb
  .. _H 10: https://github.com/let-unimi/handouts/blob/f600e06a53d004b47bec494d7b5c365530f4b62f/L10.ipynb
  .. _H 11: https://github.com/let-unimi/handouts/blob/a43bf194d80b7ec65c3c84856bf24bcc42ce4d63/L11.ipynb
  .. _H 12: https://github.com/let-unimi/handouts/blob/62ef28aa3df64cedfe0d033d68fc9ba280d63420/L12.ipynb
  .. _H 13: https://github.com/let-unimi/handouts/blob/48b3087f04fd5ea75d0086bd5367844783e20e13/L13.ipynb
  .. _H 14: https://github.com/let-unimi/handouts/blob/60265ce764f42f5b2326c866fe8267754067b349/L14.ipynb
  .. _H 15: https://github.com/let-unimi/handouts/blob/18c2817805261dc1a86f7783384fc5fda33c1133/L15.ipynb
  .. _H 16: https://github.com/let-unimi/handouts/blob/c331edf3e3f6bd04cfa446fd849d91e6da966296/L16.ipynb
  .. _H 17: https://github.com/let-unimi/handouts/blob/6ebfd23cb49923b44a82519810b6813896c106b9/L17.ipynb
  .. _H 18: https://github.com/let-unimi/handouts/blob/19c7783dfd02ea22cd6450e161bb56a01a368525/L18.ipynb
  .. _H 19: https://github.com/let-unimi/handouts/blob/cda1fbc48197730f0675d6ecd2da9b68efb21790/L19.ipynb
  .. _H 20: https://github.com/let-unimi/handouts/blob/15866e815f482fe44869440f677163d4060eee7e/L20.ipynb
  .. _H 21: https://github.com/let-unimi/handouts/blob/f4d07b48afd10acf7de68e948b23e8835749f48e/L21.ipynb
  .. _H 22: https://github.com/let-unimi/handouts/blob/d633961edf683ce8c9847483720acb448b1462d5/L22.ipynb

  .. _PT 1: https://link.springer.com/content/pdf/10.1007%2F978-0-387-68954-8_1.pdf
  .. _PT 2: https://link.springer.com/content/pdf/10.1007%2F978-0-387-68954-8_2.pdf
  .. _PT 3: https://link.springer.com/content/pdf/10.1007%2F978-0-387-68954-8_3.pdf
  .. _PT 4: https://link.springer.com/content/pdf/10.1007%2F978-0-387-68954-8_4.pdf
  .. _PT 5: https://link.springer.com/content/pdf/10.1007%2F978-0-387-68954-8_5.pdf
  .. _PT 6: https://link.springer.com/content/pdf/10.1007%2F978-0-387-68954-8_6.pdf
  .. _PT 7: https://link.springer.com/content/pdf/10.1007%2F978-0-387-68954-8_7.pdf
  .. _PT 8: https://link.springer.com/content/pdf/10.1007%2F978-0-387-68954-8_8.pdf
  .. _PT 9: https://link.springer.com/content/pdf/10.1007%2F978-0-387-68954-8_9.pdf

  .. _TPT 3: https://docs.python.org/3/tutorial/introduction.html
  .. _TPT 4: https://docs.python.org/3/tutorial/controlflow.html
  .. _TPT 5: https://docs.python.org/3/tutorial/datastructures.html
  .. _TPT 9: https://docs.python.org/3/tutorial/classes.html
