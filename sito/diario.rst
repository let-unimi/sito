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
    |  1    | Mar 28/2   | Administrivia; introduzione a Python                           | `PT 1`_; `TPT 3`_, `TPT 4`_ 1-6 e `TPT 5`_; `H 1`_                  |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  2    | Gio  2/3   | Strutture dati ed algorimi elementari su alberi e grafi        | `H 2`_                                                              |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  3    | Mar  7/3   | Ripasso su grammatiche e linguaggi                             | `PT 2`_ 1-4, [5-7], 9, [10-11]; `H 3`_                              |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  4    | Gio  9/3   | Alberi di parsing, ambiguità (casi notevoli)                   | `PT 3`_ 1; `ICD 2` 1-4; `H 4`_                                      |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  5    | Max 14/3   | Introduzione al parsing                                        | `PT 3`_ 2-3, 4.1-3, [4.4-5], 5.1-5, [8]; `H 5`_                     |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  6    | Gio 16/3   | Parsing, caso generale non direzionale (*CYK*)                 | `PT 4`_ 2.1-7; `H 6`_                                               |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  7    | Mar 21/3   | Linguaggi regolari e automi a stati finiti                     | `PT 5`_ 1-5, [7-9]; `H 7`_                                          |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  8    | Gio 23/3   | Parsing top-down (*NPDA*, simulazione BF e DF)                 | `PT 6`_ 1-3, 5; `H 8`_                                              |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    |  9    | Mar 28/3   | *Recursive descent* (con generazione automatica del parser)    | `PT 6`_ 4, 6.1; `H 9`_                                              |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 10    | Gio 30/3   | Parsing bottom-up (simulazione BF e DF)                        | `PT 7`_ 1; `H 10`_                                                  |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 11    | Mar  4/4   |                                                                | `PT 8`_ 1-2.1                                                       |
    +-------+------------+                                                                +---------------------------------------------------------------------+
    | 12    | Gio 13/4   | Parsing deterministico Top-Down (*LL*)                         | `PT 8`_ 2.2-6                                                       |
    +-------+------------+                                                                +---------------------------------------------------------------------+
    | 13    | Mar 18/4   |                                                                |                                                                     |
    +-------+------------+----------------------------------------------------------------+---------------------------------------------------------------------+
    | 14    | Gio 20/4   | Parsing deterministico Bottom-Up (*LR*)                        | `PT 9`_ 5 - 5.3                                                     |
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

.. _H 1: https://github.com/let-unimi/handouts/blob/ca18ecc9d069284ffb195b55251e44fe62c5abae/L01.ipynb
.. _H 2: https://github.com/let-unimi/handouts/blob/8ef6a7b01fe7d85bd98ac58b989564205b79a9e2/L02.ipynb
.. _H 3: https://github.com/let-unimi/handouts/blob/946b028b86219174dd5db50e3130b11ee71b5e81/L03.ipynb
.. _H 4: https://github.com/let-unimi/handouts/blob/1a55556a77c9292b077ab23a40ebd21ed66e6a39/L04.ipynb
.. _H 5: https://github.com/let-unimi/handouts/blob/2b6e2d5a76a9c95e149a286f9baba76b126af5a1/L05.ipynb
.. _H 6: https://github.com/let-unimi/handouts/blob/81f14642b5274d4a532b9b2c161c6abc30897493/L06.ipynb
.. _H 7: https://github.com/let-unimi/handouts/blob/1be839a1010e2b6d37905778286d49badbb2d31f/L07.ipynb
.. _H 8: https://github.com/let-unimi/handouts/blob/c4335f0af928db81aa45641d0b170848fd51ef71/L08.ipynb
.. _H 9: https://github.com/let-unimi/handouts/blob/c07560be29a3b2484be43d7c35716a95485c11ea/L09.ipynb
.. _H 10: https://github.com/let-unimi/handouts/blob/e61fd06f28461240a2faae92abb7a0f779ac73d7/L10.ipynb