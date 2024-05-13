Diario delle lezioni
====================

Potete trovare informazioni sulle modalità d'esame e sull'elenco degli argomenti
che costituiscono il programma nella pagina di :doc:`info`,

Il seguente diario riporta gli *argomenti* e il *materiale didattico e di
supporto* relativo sia alle **lezioni già svolte** (riguardo alle quali
costituisce il programma d'esame *de facto*), che alle lezioni **ancora da
svolgere**, per le quali è *da intendersi del tutto indicativo* (sia riguardo
alle date che al contenuto). 

**Nota bene**: diversamente dagli anni passasti, le lezioni si svolgono di norma
il martedì e venerdì dalle ore 8:30 alle ore 10:30 in Aula Magistrale al V piano
di Via Celoria 18.

Il materiale didattico indicato come *TPT* si riferisce al documento `The Python
Tutorial <https://docs.python.org/3/tutorial/index.html>`_, quello indicato con
*PT* si riferisce al libro di testo `Parsing Techniques. A Practical Guide
<https://doi.org/10.1007/978-0-387-68954-8>`_, quello indicato con *ICD* al
libro `Introduction to Compiler Design
<https://doi.org/10.1007/978-3-319-66966-3>`__, e quello indicato con *DAR* a
`The Definitive ANTLR 4 Reference
<https://pragprog.com/book/tpantlr2/the-definitive-antlr-4-reference>`__; il
materiale indicato come *H*, *E* e *S* si riferisce agli `Handout
<https://github.com/let-unimi/handouts/>`__ del docente (relativamente a
lezioni, esercizi e soluzioni); si veda la nota sui :ref:`numeri di sezione
<numeridisezione>` che reca indicazioni su quali parti del materiale sono
**parte del programma** e quali *letture consigliate, ma facoltative*.

|

  .. table::

    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | Num   | Data       | Argomento                                                      | Materiale didattico                                                 |
    +=======+============+================================================================+=====================================================================+
    |  1    | Mar 27/2   | Administrivia; introduzione a Python                           | `PT 1`_; `TPT 3`_, `TPT 4`_ 1-6 e `TPT 5`_; H01_                    |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  2    | Ven  1/3   | Strutture dati ed algorimi elementari su alberi e grafi        | H02_                                                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  3    | Mar  5/3   | Ripasso su grammatiche e linguaggi                             | `PT 2`_ 1-4, [5-7], 9, [10-11]; H03_                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  4    | Ven  8/3   | Generazione delle parole, alberi di parsing e derivazioni      | `PT 3`_ 1; H04_                                                     |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  5    | Mar 12/3   | Ambiguità (casi notevoli); introduzione al parsing             | `ICD 2` 1-4; `PT 3`_ 2-3, 4.1-3, [4.4-5], 5.1-5, [8]; H05_          |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  6    | Ven 15/3   | Parsing, caso generale non direzionale (*CYK*)                 | `PT 4`_ 2.1-7; H06_                                                 |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  7    | Mar 19/3   | Linguaggi regolari e automi a stati finiti                     | `PT 5`_ 1-5, [7-9]; H07a_. H07b_                                    |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  8    | Ven 22/3   | Parsing top-down (*NPDA*, simulazione BF e DF)                 | `PT 6`_ 1-3, 5; H08_                                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  9    | Mar 26/3   | *Recursive descent* (con generazione automatica del parser)    | `PT 6`_ 4, 6.1; H09_                                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 10    | Ven  5/4   | Parsing bottom-up (simulazione BF e DF)                        | `PT 7`_ 1; H10_                                                     |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 11    | Mar  9/4   |                                                                | `PT 8`_ 1-2.1; H11_                                                 |
    +-------+------------+                                                                +---------------------------------------------------------------------+
    | 12    | Ven 12/4   | Parsing deterministico Top-Down (*LL*)                         | `PT 8`_ 2.2-6; H12_                                                 |
    +-------+------------+                                                                +---------------------------------------------------------------------+
    | 13    | Mar 16/4   |                                                                | H13_                                                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 14    | Ven 19/4   | Parsing deterministico Bottom-Up (*LR*)                        | `PT 9`_ 5 - 5.3; H14_                                               |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 15    | Mar 23/4   |                                                                | DAR 1-2, 9.1-2; H15_                                                |
    +-------+------------+ ANTLR: grammatiche, tokenizer, parser (*visitor* e *listener*) +---------------------------------------------------------------------+
    | 16    | Ven  3/5   |                                                                | DAR 3-4; H16_                                                       |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 17    | Mar  7/5   | Dall'albero di parsing all'AST                                 | H17_                                                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 18    | Ven 10/5   | Traduzioni orientate ai dati                                   | [DAR 8]; H18_                                                       |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 19    | Mar 14/5   | Traspilazione (verso Javascript e l'*AST* di Python)           |                                                                     |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 20    | Ven 17/5   | Symbol table (e *scoping*)                                     | ICD 3; [DAR 8.4; MCD 2.11]                                          |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 21    | Mar 21/5   | Interpreti ricorsivi (e *funzioni*)                            | ICD 4; [MCD 6.1-2]                                                  |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 22    | Ven 24/5   | Type checking (statico per tipi primitivi)                     | ICD 5                                                               |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 23    | Mar 28/5   | Interpreti iterativi (*code threading* e VM a pila)            | MCD 5.1, 6.3                                                        |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 24    | Ven 31/5   | Generazione di codice (con l'*IR* di *LLVM*)                   | ICD 6.1-6                                                           |
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

.. _H01: https://github.com/let-unimi/handouts/blob/2f464124124725cd41cfa86f145e50d814a491bd/L01.ipynb
.. _H02: https://github.com/let-unimi/handouts/blob/88f4ad9dedcaf14f13129aa2755322597f09e042/L02.ipynb
.. _H03: https://github.com/let-unimi/handouts/blob/d46818e72ad160e7c3c204ef4d42f7c12d7a2e21/L03.ipynb
.. _H04: https://github.com/let-unimi/handouts/blob/1090e0a2dd3b10fc8e0da1ac261384c654e76c78/L04.ipynb
.. _H05: https://github.com/let-unimi/handouts/blob/6fa5e8422fdbb8d14fa63e61f1b0a73d49bb60a6/L05.ipynb
.. _H06: https://github.com/let-unimi/handouts/blob/35150fc55b55f691428db6f6f12982510c6943dd/L06.ipynb
.. _H07a: https://github.com/let-unimi/handouts/blob/4812302e273b372a6e4202f50b0ee1eec1fd45e5/L07a.ipynb
.. _H07b: https://github.com/let-unimi/handouts/blob/4812302e273b372a6e4202f50b0ee1eec1fd45e5/L07b.ipynb
.. _H08: https://github.com/let-unimi/handouts/blob/9c19c8a54d810128ff57e38b5cdcae68209df982/L08.ipynb
.. _H09: https://github.com/let-unimi/handouts/blob/1c5a6692af85f44fd0e68c23df458fb2158cd6fe/L09.ipynb
.. _H10: https://github.com/let-unimi/handouts/blob/d4dbd983c3a459bc567754b8ef3f3c219861f8da/L10.ipynb
.. _H11: https://github.com/let-unimi/handouts/blob/ace628c73dc27306c67a2afed931037a1ffea6c5/L11.ipynb
.. _H12: https://github.com/let-unimi/handouts/blob/004cc51f5a9ec415c9de62ac5b3ab70d9c61636d/L12.ipynb
.. _H13: https://github.com/let-unimi/handouts/blob/5eebc04b0bc58fc1af5110bdca033bc9321da9a1/L13.ipynb
.. _H14: https://github.com/let-unimi/handouts/blob/1410273662260a2a36b460f73828216f09b32ae2/L14.ipynb
.. _H15: https://github.com/let-unimi/handouts/blob/0ad84f0b334e971a65d397dcdfa5a800f9323d17/L15.ipynb
.. _H16: https://github.com/let-unimi/handouts/blob/b56ba1aa9485ac92bd35b78cdbf20a86fc811e25/L16.ipynb
.. _H17: https://github.com/let-unimi/handouts/blob/56b15caa3661ef1ed86e51e4509da95174a922a4/L17.ipynb
.. _H18: https://github.com/let-unimi/handouts/blob/6d32d9e7e78f20db31ccdcabb8d695453063de70/L18.ipynb

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
