Diario delle lezioni
====================

Potete trovare informazioni sulle modalità d'esame e sull'elenco degli argomenti
che costituiscono il programma nella pagina di :doc:`info`,

Il seguente diario riporta gli *argomenti* e il *materiale didattico e di
supporto* relativo sia alle **lezioni già svolte** (riguardo alle quali
costituisce il programma d'esame *de facto*), che alle lezioni **ancora da
svolgere**, per le quali è *da intendersi del tutto indicativo* (sia riguardo
alle date che al contenuto). 

|

  .. table::

    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | Num   | Data       | Argomento                                                      | Materiale didattico                                                 |
    +=======+============+================================================================+=====================================================================+
    |  1    | Mar  3/3   | Administrivia; introduzione a Python                           | `PT 1`_; `TPT 3`_, `TPT 4`_ 1-6 e `TPT 5`_; H01_                    |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  2    | Ven  6/3   | Strutture dati ed algoritmi elementari su alberi e grafi       | H02_                                                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+   
    |  3    | Mar 10/3   | Ripasso su grammatiche e linguaggi                             | `PT 2`_ 1-4, [5-7], 9, [10-11]; H03_                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  4    | Ven 13/3   | Alberi di parsing e derivazioni, ambiguità (casi notevoli)     | `PT 3`_ 1; `ICD 2` 1-4; H04_                                        |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  5    | Mar 17/3   | Introduzione al Parsing                                        | `ICD 2` 1-4; `PT 3`_ 2-3, 4.1-3, [4.4-5], 5.1-5, [8]; H05_          |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  6    | Ven 20/3   | Caso generale non direzionale (*CYK*)                          | `PT 4`_ 2.1-7; H06_                                                 |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  7    | Mar 24/3   | Linguaggi regolari e automi a stati finiti                     | `PT 5`_ 1-5, [7-9]; H07_                                            |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  8    | Ven 27/3   | Parsing top-down (*NPDA*, simulazione BF e DF)                 | `PT 6`_ 1-3, 5; H08_                                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  9    | Mar 31/3   | *Recursive descent* (con generazione automatica del parser)    | `PT 6`_ 4, 6.1; H09_                                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 10    | Ven 10/4   | Parsing bottom-up (simulazione BF e DF)                        | `PT 7`_ 1; H10_                                                     |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 11    | Mar 14/4   |                                                                | `PT 8`_ 1-2.1; H11_                                                 |
    +-------+------------+                                                                +---------------------------------------------------------------------+
    | 12    | Ven 17/4   | Parsing deterministico Top-Down (*LL*)                         | `PT 8`_ 2.2-6; H12_                                                 |
    +-------+------------+                                                                +---------------------------------------------------------------------+
    | 13    | Mar 21/4   |                                                                | H13_                                                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 14    | Ven 24/4   | Parsing deterministico Bottom-Up (*LR*)                        | `PT 9`_ 5 - 5.3; H14_                                               |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 15    | Mar 28/4   |                                                                | DAR 1-2, 9.1-2                                                      |
    +-------+------------+ ANTLR: grammatiche, tokenizer, parser (*visitor* e *listener*) +---------------------------------------------------------------------+
    | 16    | Mar  5/5   |                                                                | DAR 3-4                                                             |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 17    | Ven  8/5   | Dall'albero di parsing all'AST                                 |                                                                     |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 18    | Mar 12/5   | Traduzioni orientate ai dati                                   | [DAR 8]                                                             |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 19    | Ven 15/5   | Traspilazione (verso Javascript e l'*AST* di Python)           |                                                                     |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 20    | Mar 19/5   | Symbol table (e *scoping*)                                     | ICD 3; [DAR 8.4; MCD 2.11]                                          |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 21    | Ven 22/5   | Interpreti ricorsivi (e *funzioni*)                            | ICD 4; [MCD 6.1-2]                                                  |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 22    | Mar 26/5   | Type checking (statico per tipi primitivi)                     | ICD 5                                                               |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 23    | Ven 29/5   | Interpreti iterativi (*code threading* e VM a pila)            | MCD 5.1, 6.3                                                        |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 24    | Ven  5/6   | Generazione di codice (con l'*IR* di *LLVM*)                   | ICD 6.1-6                                                          |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+

|

.. admonition:: Legenda
  :class: alert alert-secondary

  Le **sigle** utilizzate per i riferimenti al materiale didattico sono le seguenti:

  * *TPT* si riferisce a `The Python Tutorial <https://docs.python.org/3/tutorial/index.html>`_, 
  * *PT* si riferisce a `Parsing Techniques. A Practical Guide <https://doi.org/10.1007/978-0-387-68954-8>`_, 
  * *ICD* si riferisce a `Introduction to Compiler Design <https://doi.org/10.1007/978-3-319-66966-3>`__, 
  * *MCD* si riferisce a `Modern Compiler Design <https://doi.org/10.1007/978-1-4614-4699-6>`__,
  * *DAR*  si riferisce a `The Definitive ANTLR 4 Reference <https://pragprog.com/titles/tpantlr2/the-definitive-antlr-4-reference>`__,
  * *H* si riferisce agli `Handout <https://github.com/let-unimi/handouts/>`__ del docente,

  Accanto a ciascun riferimento che reca un **numero di capitolo** possono trovarsi
  dei **numeri di sezione** essi sono da intendersi nel seguente modo:

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

.. _H01: https://github.com/let-unimi/handouts/blob/aa2526/L01.ipynb
.. _H02: https://github.com/let-unimi/handouts/blob/aa2526/L02.ipynb
.. _H03: https://github.com/let-unimi/handouts/blob/aa2526/L03.ipynb
.. _H04: https://github.com/let-unimi/handouts/blob/aa2526/L04.ipynb
.. _H05: https://github.com/let-unimi/handouts/blob/aa2526/L05.ipynb
.. _H06: https://github.com/let-unimi/handouts/blob/aa2526/L06.ipynb
.. _H07: https://github.com/let-unimi/handouts/blob/aa2526/L07.ipynb
.. _H08: https://github.com/let-unimi/handouts/blob/aa2526/L08.ipynb
.. _H09: https://github.com/let-unimi/handouts/blob/aa2526/L09.ipynb
.. _H10: https://github.com/let-unimi/handouts/blob/aa2526/L10.ipynb
.. _H11: https://github.com/let-unimi/handouts/blob/aa2526/L11.ipynb
.. _H12: https://github.com/let-unimi/handouts/blob/aa2526/L12.ipynb   
.. _H13: https://github.com/let-unimi/handouts/blob/aa2526/L13.ipynb
.. _H14: https://github.com/let-unimi/handouts/blob/aa2526/L14.ipynb

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
