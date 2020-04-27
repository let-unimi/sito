Diario delle lezioni
====================

Il seguente diario riporta gli *argomenti* e il *materiale didattico e di
supporto* relativo sia alle **lezioni già svolte** (riguardo alle quali
costituisce il programma d'esame *de facto*), che alle lezioni **ancora da
svolgere**, per le quali è *da intendersi del tutto indicativo* (sia riguardo
alle date che al contenuto). Le lezioni si svolgono di norma dalle 11:30 alle
13:30.

Nel `canale YouTube <http://bit.ly/3cB9snQ>`__ dell'insegnamento disponibili sia
la *playlist* delle registrazioni delle `lezioni <https://bit.ly/2J5ihsN>`__,
che quella delle `"pillole" <https://bit.ly/2U4m7Zw>`__.

Il materiale didattico indicato come *TPT* si riferisce al documento `The Python
Tutorial <https://docs.python.org/3/tutorial/index.html>`_, quello
indicato con *PT* si riferisce al libro di testo `Parsing Techniques. A
Practical Guide <https://doi.org/10.1007/978-0-387-68954-8>`_, quello indicato con
*MCD* al libro `Modern Compiler Design <https://doi.org/10.1007/978-1-4614-4699-6>`__
e quello indicato con *DAR* a `The Definitive ANTLR 4 Reference <https://pragprog.com/book/tpantlr2/the-definitive-antlr-4-reference>`__;
il materiale
indicato come *H* si riferisce agli `Handout
<https://github.com/let-unimi/handouts/>`__ del docente; si veda la nota sui
:ref:`numeri di sezione <numeridisezione>` che reca indicazioni su quali parti
del materiale sono **parte del programma** e quali *letture consigliate, ma
facoltative*.

|

.. table::

   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | Num   | Data       | Argomento                                                    | Materiale didattico                                                 |
   +=======+============+==============================================================+=====================================================================+
   | 1     | Gio 12/3   | Obiettivi e struttura dell'insegnamento                      | `PT 1`_                                                             |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 2     | Mar 17/3   | Introduzione a Python                                        | `TPT 3`_; `TPT 4`_ 1-6; `H 2`_                                      |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 3     | Gio 19/3   | Strutture dati ed algoritmi di base per alberi e grafi       | `TPT 5`_; `TPT 9`_ 1-4; `H 3`_                                      |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 4     | Mer 25/3   |                                                              | `PT 2`_ 1-3; `H 4`_                                                 |
   +       +            + Grammatiche e linguaggi                                      +---------------------------------------------------------------------+
   | 5     | Gio 26/3   |                                                              | `PT 2`_ 3, 4, [5-8], 9, [10-12]; `H 5`_                             |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 6     | Mar 31/3   |                                                              | `PT 3`_ 1, 2; `H 6`_                                                |
   +       +            + Introduzione al parsing                                      +---------------------------------------------------------------------+
   | 7     | Gio 2/4    |                                                              | `PT 3`_ 3, 4.1-3, [4.4-5], 5.1-5, 8, [9, 10]; `H 7`_                |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 8     | Mar 7/4    |                                                              | `PT 4`_ 2.1-2; `H 8`_                                               |
   +       +            + Parsing, caso generale non direzionale (*CYK*)               +---------------------------------------------------------------------+
   | 9     | Gio 16/4   |                                                              | `PT 4`_ 2.3-7; `H 9`_                                               |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 10    | Mar 21/4   | Linguaggi regolari e automi a stati finiti                   | `PT 5`_ [1] 2-3; `H 10`_                                            |
   +       +            +                                                              +---------------------------------------------------------------------+
   | 11    | Gio 23/4   |                                                              | `PT 5`_ 4-5 [7-9]; `H 11`_                                          |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 12    | Gio 28/4   | Parsing Top-Down (*Pushdown Automata*, *Recursive descent*)  | `PT 6`_  1-3, 5;                                                    |
   +       +            +                                                              +---------------------------------------------------------------------+
   | 13    | Mar 30/4   |                                                              | `PT 6`_  4, 6.1;                                                    |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+

..
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 14    | Mar 16/4   | Parsing Bottom-Up                                            | `PT 7`_ 1; `H 14`_                                                  |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   |       |            | *Vacanze di Pasqua* (3 lezioni)                              | `Homework`_                                                         |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 15    | Mar 30/4   | Parsing deterministico Top-Down (*LL*)                       | `PT 8`_ 1 - 2.2.1 [4], MCD 3.4.1 - 3.4.6; `H 15`_                   |
   +       +            +                                                              +---------------------------------------------------------------------+
   | 16    | Gio 2/5    |                                                              | `PT 8`_ 2.2.2 - 2.6 [5]; `H 16`_                                    |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 17    | Mar 7/5    | Parsing deterministico Bottom-Up (*LR*)                      | `PT 9`_ 5 - 5.3, 9.5.5 [6.3]; MCD 3.5.1 - 3.5.3; `H 17`_            |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 18    | Gio 9/5    | ANTLR                                                        | DAR 1 - 4; `H 18`_                                                  |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 19    | Mar 14/5   | Alberi sintattici e loro annotazione                         | [MCD 4, 5]; `H 19`_                                                 |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 20    | Gio 16/5   | Traduzioni (orientate ai dati)                               | `H 20`_                                                             |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 21    | Mar 21/5   | Transpilatori (verso JavaScript e l'AST di Python)           | DAR 8; `H 21`_                                                      |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 22    | Gio 23/5   | Symbol table (scope di blocco e controllo dei tipi)          | `H 22`_                                                             |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 23    | Mar 28/5   | Interpreti ricorsivi (e funzioni)                            | [MCD 6]; `H 23`_                                                    |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 24    | Gio 30/5   | Interpreti iterativi (*code threading*)                      | [MCD 7]; `H 24`_                                                    |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+

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

.. _H 2: https://github.com/let-unimi/handouts/blob/2f784316dc9f3d93b8abea2a84acb6403e175854/L02.ipynb
.. _H 3: https://github.com/let-unimi/handouts/blob/50e770fcfcba844ef11da170a4ba084fef6e4c99/L03.ipynb
.. _H 4: https://github.com/let-unimi/handouts/blob/1044eca47bf481ad124b219a05524f386cd0d836/L04.ipynb
.. _H 5: https://github.com/let-unimi/handouts/blob/05fea097a5fc168342d3eeb438804b836567fe44/L05.ipynb
.. _H 6: https://github.com/let-unimi/handouts/blob/2b28ef96902ce534701c4233faa70a08c65f165e/L06.ipynb
.. _H 7: https://github.com/let-unimi/handouts/blob/4ea9b6740b51de79b905e278f95e6e110d6b8eac/L07.ipynb
.. _H 8: https://github.com/let-unimi/handouts/blob/f581e79b0a18f7072cad454a68696c98b69283eb/L08.ipynb
.. _H 9: https://github.com/let-unimi/handouts/blob/9998d99152b4e452f5bd7efd592180a05cd36070/L09.ipynb
.. _H 10: https://github.com/let-unimi/handouts/blob/f0f61d064f44bbbdba78e46ece643bb04c34f98d/L10.ipynb
.. _H 11: https://github.com/let-unimi/handouts/blob/f6baaa717a1f9339caafde5523b1aa8a093db13f/L11.ipynb

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
