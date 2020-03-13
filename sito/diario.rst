Diario delle lezioni
====================

Il seguente diario riporta gli *argomenti* e il *materiale didattico e di
supporto* relativo sia alle **lezioni già svolte** (riguardo alle quali
costituisce il programma d'esame *de facto*), che alle lezioni **ancora da
svolgere**, per le quali è *da intendersi del tutto indicativo* (sia riguardo
alle date che al contenuto). Le lezioni si svolgono di norma dalle 11:30 alle
13:30. Alcuni minuti prima di ciascuna lezione questa pagina sarà aggiornata con
le **indicazioni necessarie ad assistere allo streaming** della lezione stessa.

.. admonition:: Canale Telegram
   :class: alert alert-warning

   Dalla prossima lezione, in via sperimentale, l'annuncio relativo al link ove
   reperire lo stream della lezione e la chat interattiva con gli studenti
   saranno gestite tramite un **canale privato Telegram**; gli studenti interessati
   che non avessero ricevuto il link per l'adesione al canale sono pregati di
   *contattare il docente per email*; gli studenti che viceversa ritenessero
   questa soluzione *non accettabile*, sono parimenti pregati di segnalarlo per
   email al docente.


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
   | 1     | Gio 12/3   | Obiettivi e struttura del corso                              | `PT 1`_                                                             |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 2     | Mar 17/3   | Introduzione a Python                                        | `TPT 3`_; `TPT 4`_ 1-6                                              |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+

..
   | 2     | Gio 5/3    | Introduzione a Python                                        | `TPT 3`_; `TPT 4`_ 1-6; `H 2`_                                      |
   | 3     | Mar 05/3   | Strutture dati ed algoritmi di base per alberi e grafi       | `TPT 5`_; `TPT 9`_ 1-4; `H 3`_                                      |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   |       |            | *Vacanze di carnevale* (1 lezione)                           |                                                                     |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 4     | Mar 12/3   |                                                              | `PT 2`_ 1-3; `H 4`_                                                 |
   +       +            + Grammatiche e linguaggi                                      +---------------------------------------------------------------------+
   | 5     | Gio 14/3   |                                                              | `PT 2`_ 1-4, 9 [5-8, 10-12]; `H 5`_                                 |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 6     | Mar 19/3   |                                                              | `PT 3`_ 1, 2; `H 6`_                                                |
   +       +            + Introduzione al parsing                                      +---------------------------------------------------------------------+
   | 7     | Gio 21/3   |                                                              | `PT 3`_ 3, 4.1-3, 5.1-5, 8 [4.4-5, 9-10]                            |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 8     | Mar 26/3   |                                                              | `PT 4`_ 2.1-2; `H 8`_                                               |
   +       +            + Parsing, caso generale non direzionale (*CYK*)               +---------------------------------------------------------------------+
   | 9     | Gio 28/3   |                                                              | `PT 4`_ 2.3-7; `H 9`_                                               |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 10    | Mar 2/4    | Linguaggi regolari e automi a stati finiti                   | `PT 5`_ 2-5 [1, 7, 8, 9]; `H 10`_                                   |
   +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
   | 11    | Gio 4/4    | Parsing Top-Down (*Pushdown Automata*, *Recursive descent*,  | `PT 6`_  1-3, 5; `H 11`_                                            |
   +       +            + *Continuation*)                                              +---------------------------------------------------------------------+
   | 12    | Mar 9/4    |                                                              | `PT 6`_  4, 6.1; `H 12`_                                            |
   +       +            +                                                              +---------------------------------------------------------------------+
   | 13    | Gio 11/4   |                                                              | `PT 6`_  6.2; `H 13`_                                               |
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

.. _H 2: https://github.com/let-unimi/handouts/blob/0159d09ebbdeac82b03adc38fdc069a40f54cb1c/L02.ipynb
.. _H 3: https://github.com/let-unimi/handouts/blob/d49c9c5c8c1937b22728e8eae3294fa14b66cbe8/L03.ipynb
.. _H 4: https://github.com/let-unimi/handouts/blob/b7f83cbad560f3930030231ffe86215d908f6f5c/L04.ipynb
.. _H 5: https://github.com/let-unimi/handouts/blob/6af080b886246ec84a6996c394826620a2cf324a/L05.ipynb
.. _H 6: https://github.com/let-unimi/handouts/blob/e8aa240ba6331e9d820d3d252964088433a5dee1/L06.ipynb
.. _H 8: https://github.com/let-unimi/handouts/blob/b4ceba2b0e57f07c7c1d0f2e5c676e3d995e2ae0/L08.ipynb
.. _H 9: https://github.com/let-unimi/handouts/blob/d2f2e1ea4359ba55061c5ea2c346fd3197b32035/L09.ipynb
.. _H 10: https://github.com/let-unimi/handouts/blob/f04a17e73f732802bca19c19002a1e18315877c5/L10.ipynb
.. _H 11: https://github.com/let-unimi/handouts/blob/20a4d48e675b63875498fe1896b49d909fbb9aad/L11.ipynb
.. _H 12: https://github.com/let-unimi/handouts/blob/14d87c1f84f879035fec61be78566b72b4312428/L12.ipynb
.. _H 13: https://github.com/let-unimi/handouts/blob/6f26e57bc7a3cbcd11159a688cd3bd31fc68ff2c/L13.ipynb
.. _H 14: https://github.com/let-unimi/handouts/blob/fb671dd9276cef39970475ca0120703c3220eae2/L14.ipynb
.. _Homework: https://github.com/let-unimi/handouts/blob/master/MT-HW.ipynb
.. _H 15: https://github.com/let-unimi/handouts/blob/59c64002275a1817698f6298f7b529cd658a0a61/L15.ipynb
.. _H 16: https://github.com/let-unimi/handouts/blob/790844f0053fc3ca7b2ad74680dcd361424f6b5f/L16.ipynb
.. _H 17: https://github.com/let-unimi/handouts/blob/dbb1460dfc8fe84762cba81b160b810ab8bd69ea/L17.ipynb
.. _H 18: https://github.com/let-unimi/handouts/blob/97db25c2effd32772f09ebf9dcd3faf9cf9fd8d0/L18.ipynb
.. _H 19: https://github.com/let-unimi/handouts/blob/42596d8afff14cbaf06abc0955e0f04f232b363d/L19.ipynb
.. _H 20: https://github.com/let-unimi/handouts/blob/a6a5bfbfaf00ce849ad2433da3aa1dfe34301f8e/L20.ipynb
.. _H 21: https://github.com/let-unimi/handouts/blob/c2a9e2ad332d8d9a7d5f67a94965cf5a7a56ef87/L21.ipynb
.. _H 22: https://github.com/let-unimi/handouts/blob/b90a4c13a05cebe37e848ec2494e0a96da8edd77/L22.ipynb
.. _H 23: https://github.com/let-unimi/handouts/blob/c6c521e07384624fd30223ad91d5020626e73d09/L23.ipynb
.. _H 24: https://github.com/let-unimi/handouts/blob/45b948c061775031637bd2a172d8c885d0616505/L24.ipynb

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
