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
    |  1    | Mar 25/2   | Administrivia; introduzione a Python                           | `PT 1`_; `TPT 3`_, `TPT 4`_ 1-6 e `TPT 5`_; H01_                    |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  2    | Ven 28/2   | Strutture dati ed algoritmi elementari su alberi e grafi       | H02_                                                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+   
    |  3    | Mar  4/3   | Ripasso su grammatiche e linguaggi                             | `PT 2`_ 1-4, [5-7], 9, [10-11]; H03_                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  4    | Ven  7/3   | Alberi di parsing, ambiguità (casi notevoli)                   | `PT 3`_ 1; `ICD 2` 1-4; H04_                                        |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  5    | Mar 11/3   | Introduzione al parsing                                        | `PT 3`_ 2-3, 4.1-3, [4.4-5], 5.1-5, [8]; H05_                       |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  6    | Ven 14/3   | Parsing, caso generale non direzionale (*CYK*)                 | `PT 4`_ 2.1-7; H06_                                                 |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  7    | Mar 18/3   | Linguaggi regolari e automi a stati finiti                     | `PT 5`_ 1-5, [7-9]; H07_                                            |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  8    | Ven 21/3   | Parsing top-down (*NPDA*, simulazione BF e DF)                 | `PT 6`_ 1-3, 5; H08_                                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  9    | Mar 25/3   | *Recursive descent* (con generazione automatica del parser)    | `PT 6`_ 4, 6.1; H09_                                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 10    | Ven 28/3   | Parsing bottom-up (simulazione BF e DF)                        | `PT 7`_ 1; H10_                                                     |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 11    | Mar  1/4   |                                                                | `PT 8`_ 1-2.1; H11_                                                 |
    +-------+------------+                                                                +---------------------------------------------------------------------+
    | 12    | Ven  4/4   | Parsing deterministico Top-Down (*LL*)                         | `PT 8`_ 2.2-6; H12_                                                 |
    +-------+------------+                                                                +---------------------------------------------------------------------+
    | 13    | Mar  8/4   |                                                                | H13_                                                                |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 14    | Ven 11/4   | Parsing deterministico Bottom-Up (*LR*)                        | `PT 9`_ 5 - 5.3; H14_                                               |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 15    | Mar 15/4   |                                                                | DAR 1-2, 9.1-2; H15_                                                |
    +-------+------------+ ANTLR: grammatiche, tokenizer, parser (*visitor* e *listener*) +---------------------------------------------------------------------+
    | 16    | Mar 22/4   |                                                                | DAR 3-4                                                             |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 17    | Mar 29/5   | Dall'albero di parsing all'AST                                 |                                                                     |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+

..
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 18    | Ven  9/5   | Traduzioni orientate ai dati                                   | [DAR 8]; `H 18`_                                                    |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 19    | Mar 13/5   | Traspilazione (verso Javascript e l'*AST* di Python)           | `H 19`_                                                             |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 20    | Ven 16/5   | Symbol table (e *scoping*)                                     | ICD 3; [DAR 8.4; MCD 2.11]; `H 20`_                                 |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 21    | Mar 20/5   | Interpreti ricorsivi (e *funzioni*)                            | ICD 4; [MCD 6.1-2]; `H 21`_                                         |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 22    | Ven 23/5   | Type checking (statico per tipi primitivi)                     | ICD 5; `H 22`_                                                      |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 23    | Mar 27/5   | Interpreti iterativi (*code threading* e VM a pila)            | MCD 5.1, 6.3; `H 23`_                                               |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 24    | Ven 30/5   | Generazione di codice (con l'*IR* di *LLVM*)                   | ICD 6.1-6; `H 24`_                                                  |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | **    | Mar  3/6   | *Presentazione progetto*                                       |                                                                     |
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

.. _H01: https://github.com/let-unimi/handouts/blob/dc3716c8778d2bcac510366c19616f748f537b47/L01.ipynb
.. _H02: https://github.com/let-unimi/handouts/blob/6dbc3895361c89a34c8395d866599aa93702a04c/L02.ipynb
.. _H03: https://github.com/let-unimi/handouts/blob/5cae78997eaea192ccd92cbd44be7eab61704142/L03.ipynb
.. _H04: https://github.com/let-unimi/handouts/blob/24a4897819ed347429ce7f673a4b0fe7d5f80fa1/L04.ipynb
.. _H05: https://github.com/let-unimi/handouts/blob/28413987ac4e474397713c6d45c6c8f51234f5ac/L05.ipynb
.. _H06: https://github.com/let-unimi/handouts/blob/f97fcd66723002c18f9ed58cf93f5c7bb712d7f6/L06.ipynb
.. _H07: https://github.com/let-unimi/handouts/blob/891b609823427511291cbebc4c84b9e653e3039f/L07.ipynb
.. _H08: https://github.com/let-unimi/handouts/blob/efb3b0b4acbda323aca0642bb7a92c44e9eac579/L08.ipynb
.. _H09: https://github.com/let-unimi/handouts/blob/83da61d945b3f0f36779120e2cf04276517d95bb/L09.ipynb
.. _H10: https://github.com/let-unimi/handouts/blob/efb3b0b4acbda323aca0642bb7a92c44e9eac579/L10.ipynb
.. _H11: https://github.com/let-unimi/handouts/blob/a226e3b35197d36fb47d2b329ce3a2c7d6b28bd3/L11.ipynb
.. _H12: https://github.com/let-unimi/handouts/blob/008585ab06e2f8ab6047afb7ded012288bb8d714/L12.ipynb
.. _H13: https://github.com/let-unimi/handouts/blob/35d2e240193acb8c94cc1d935194f47b79bcc40d/L13.ipynb
.. _H14: https://github.com/let-unimi/handouts/blob/caba340690763171eb70c4a80f0cab651af122ef/L14.ipynb
.. _H15: https://github.com/let-unimi/handouts/blob/25c124bd74557932f3975abb6254edd96bc5a628/L15.ipynb

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
