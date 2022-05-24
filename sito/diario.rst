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
    |  1    | Mar  8/3   | Administrivia; introduzione a Python                           | `PT 1`_; `TPT 3`_, `TPT 4`_ 1-6 e `TPT 5`_; `H 1`_                  |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  2    | Gio 10/3   | Strutture dati ed algorimi elementari su alberi e grafi        | `H 2`_, `E 2`_, `S 2`_                                              |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  3    | Mar 15/3   | Ripasso su grammatiche e linguaggi                             | `PT 2`_ 1-4, [5-7], 9, [10-11]; `H 3`_, `E 3`_, `S 3`_              |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  4    | Gio 17/3   | Alberi di parsing, ambiguità (casi notevoli)                   | `PT 3`_ 1; `ICD 2` 1-4; `H 4`_, `E 4`_                              |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  5    | Max 22/3   | Introduzione al parsing                                        | `PT 3`_ 2-3, 4.1-3, [4.4-5], 5.1-5, [8]; `H 5`_                     |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  6    | Gio 24/3   | Parsing, caso generale non direzionale (*CYK*)                 | `PT 4`_ 2.1-7; `H 6`_, `S 6`_                                       |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  7    | Mar 29/3   | Linguaggi regolari e automi a stati finiti                     | `PT 5`_ 1-5, [7-9]; `H 7`_                                          |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  8    | Gio 31/3   | Parsing top-down (*NPDA*, simulazione BF e DF)                 | `PT 6`_ 1-3, 5; `H 8`_                                              |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  9    | Mar  5/4   | *Recursive descent* (con generazione automatica del parser)    | `PT 6`_ 4, 6.1; `H 9`_                                              |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 10    | Gio  7/4   | Parsing bottom-up (simulazione BF e DF)                        | `PT 7`_ 1; `H 10`_                                                  |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 11    | Mar 12/4   |                                                                | `PT 8`_ 1-2.1; `H 11`_                                              |
    +-------+------------+                                                                +---------------------------------------------------------------------+
    | 12    | Gio 21/4   | Parsing deterministico Top-Down (*LL*)                         | `PT 8`_ 2.2-6; `H 12`_                                              |
    +-------+------------+                                                                +---------------------------------------------------------------------+
    | 13    | Mar 26/4   |                                                                | `H 13`_                                                             |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 14    | Gio 28/4   | Parsing deterministico Bottom-Up (*LR*)                        | `PT 9`_ 5 - 5.3; `H 14`_                                            |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 15    | Mar  3/5   |                                                                | DAR 1-2, 9.1-2; `H 15`_                                             |
    +-------+------------+ ANTLR: grammatiche, tokenizer, parser (*visitor* e *listener*) +---------------------------------------------------------------------+
    | 16    | Gio  5/5   |                                                                | DAR 3-4; `H 16`_                                                    |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 17    | Mar 10/5   | Dall'albero di parsing all'AST                                 | `H 17`_                                                             |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 18    | Gio 12/5   | Traduzioni orientate ai dati                                   | [DAR 8]; `H 18`_                                                    |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 19    | Mar 17/5   | Traspilazione (verso Javascript e l'*AST* di Python)           | `H 19`_                                                             |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 20    | Gio 19/5   | Symbol table (e *scoping*)                                     | ICD 3; [DAR 8.4; MCD 2.11]; `H 20`_                                 |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 21    | Mar 24/5   | Interpreti ricorsivi (e *funzioni*)                            | ICD 4; [MCD 6.1-2]; `H 21`_                                         |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 22    | Gio 26/5   | Type checking (statico per tipi primitivi)                     | ICD 5                                                               |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 23    | Mar 31/5   | Interpreti iterativi (*code threading* e VM a pila)            | MCD 5.1, 6.3                                                        |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 24    | Gio  2/6   | Generazione di codice (con l'*IR* di *LLVM*)                   | ICD 6.1-6                                                           |
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

.. _H 1: https://github.com/let-unimi/handouts/blob/e40103253530683c4be020b22fe41c1247e36247/L01.ipynb
.. _H 2: https://github.com/let-unimi/handouts/blob/35df58cce0b26fcc3377771c412b572b601bc37d/L02.ipynb
.. _E 2: https://github.com/let-unimi/handouts/blob/40f45c4b530a4717d34f4c5df64f324c93a82cac/E02.ipynb
.. _S 2: https://github.com/let-unimi/handouts/blob/00e24dd3d7a833a1e7f0533d849720d98b939233/S02.ipynb

.. _H 3: https://github.com/let-unimi/handouts/blob/c1fe742f710ef56b403d52195f8ae67688f92bfa/L03.ipynb
.. _E 3: https://github.com/let-unimi/handouts/blob/1c011f7a44cfb5bbf1f318c84962c808ee47b042/E03.ipynb
.. _S 3: https://github.com/let-unimi/handouts/blob/476a3f10755f6cedd4274f6634ec997ac59472b8/S03.ipynb

.. _H 4: https://github.com/let-unimi/handouts/blob/1fe96d931dc71757e511350a4dc5470ba1c18ac9/L03.ipynb
.. _E 4: https://github.com/let-unimi/handouts/blob/1fe96d931dc71757e511350a4dc5470ba1c18ac9/E04.ipynb

.. _H 5: https://github.com/let-unimi/handouts/blob/384192bfd495a96b862ac86f90fe732db595bfd9/L05.ipynb

.. _H 6: https://github.com/let-unimi/handouts/blob/b56e2d0c3489074dbf2c67ac89769368a1999fa6/L06.ipynb
.. _S 6: https://github.com/let-unimi/handouts/blob/535799b11bb983760a4a25062bb6ffe038fd4df4/S06.ipynb

.. _H 7: https://github.com/let-unimi/handouts/blob/bf24e60137de24822a292c88efcabd3c0109cb4b/L07.ipynb

.. _H 8: https://github.com/let-unimi/handouts/blob/5806377a3fc07b1b59e04ef8fbeba9f58d9ed859/L08.ipynb

.. _H 9: https://github.com/let-unimi/handouts/blob/733bb66dbd47a11f43c9ff23dcf844d2724d0823/L09.ipynb

.. _H 10: https://github.com/let-unimi/handouts/blob/93ec74bc70c9990b3172a5d3e7df7e4cf3c7e9a4/L10.ipynb

.. _H 11: https://github.com/let-unimi/handouts/blob/52471b928342dc9f633d12a67909ec3cecc08e49/L11.ipynb
.. _H 12: https://github.com/let-unimi/handouts/blob/271d4d360ddc25084ab225e3ecd7ec39165f6536/L12.ipynb
.. _H 13: https://github.com/let-unimi/handouts/blob/99470b4e84b18e7c41fb74f3010297223e5f3935/L13.ipynb
.. _H 14: https://github.com/let-unimi/handouts/blob/90a11625f09c668a06dd69e59fd72afb7e6e61f5/L14.ipynb

.. _H 15: https://github.com/let-unimi/handouts/blob/ce7acbf4d5e857b7b0184ffe735d858299b3dfd8/L15.ipynb
.. _H 16: https://github.com/let-unimi/handouts/blob/ebe7fe593331703b9fb47afe5f5f1462e0612696/L16.ipynb
.. _H 17: https://github.com/let-unimi/handouts/blob/92caf1386b70cd738d2add3cdcb88ea5dfc859bc/L17.ipynb
.. _H 18: https://github.com/let-unimi/handouts/blob/a682bbb14e53783b877000ebd5129febbf18d97b/L18.ipynb
.. _H 19: https://github.com/let-unimi/handouts/blob/3cfb74a1bff216467e434d65d544db43d1053adb/L19.ipynb
.. _H 20: https://github.com/let-unimi/handouts/blob/ed19a449aa5135bdb5f879a40c285926699706cc/L20.ipynb
.. _H 21: https://github.com/let-unimi/handouts/blob/05d7a2e0d6c34e5fcc8a8319c25aa9a0030fb0a8/L21.ipynb

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
