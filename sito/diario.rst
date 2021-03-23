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

    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | Num   | Data       | Argomento                                                    | Materiale didattico                                                 |
    +=======+============+==============================================================+=====================================================================+
    | 1     | Gio  4/3   | Administrivia; introduzione a Python                         | `PT 1`_; `TPT 3`_, `TPT 4`_ 1-6 e `TPT 5`_; `H 1`_                  |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 2     | Mar  9/3   | Strutture dati ed algorimi elementari su alberi e grafi      | `H 2`_                                                              |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 3     | Gio 11/3   | Richiami su grammatiche e linguaggi                          | `PT 2`_ 1-4, [5-8], [10-12]; `H 3`_                                 |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 4     | Mar 16/3   |                                                              | `PT 2`_ 9; `PT 3`_ 1; `H 4`_                                        |
    +-------+------------+ Introduzione al *parsing*                                    +---------------------------------------------------------------------+
    | 5     | Gio 18/3   |                                                              | `PT 3`_ 2, 3, 4.1-3, [4.4-5], 5.1-5, [8-10]; `H 5`_                 |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 6     | Mar 23/3   |                                                              | `PT 4`_ 2.1-2; `H 6`_                                               |
    +-------+------------+ Parsing, caso generale non direzionale (*CYK*)               +---------------------------------------------------------------------+
    | 7     | Gio 25/3   |                                                              | `PT 4`_ 2.3-7                                                       |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 8     | Mar 30/3   | Linguaggi regolari e automi a stati finiti                   | `PT 5`_ [1], 2-5, [7-9]                                             |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 9     | Mar 13/4   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 10    | Gio 15/4   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 11    | Mar 20/4   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 12    | Gio 22/4   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 13    | Mar 27/4   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 14    | Gio 29/4   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 15    | Mar  4/5   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 16    | Gio  6/5   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 17    | Mar 11/5   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 18    | Gio 13/5   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 19    | Mar 18/5   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 20    | Gio 20/5   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 21    | Mar 25/5   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 22    | Gio 27/5   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 23    | Mar  1/6   |                                                              |                                                                     |
    +-------+------------+--------------------------------------------------------------+---------------------------------------------------------------------+
    | 24    | Gio  3/6   |                                                              |                                                                     |
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

  .. _H 1: https://github.com/let-unimi/handouts/blob/f5ee884bd5ae4b7846eb5eb6b3b16879ae6aad95/L01.ipynb
  .. _H 2: https://github.com/let-unimi/handouts/blob/500cafd2acc199a2115c6009ddacd7d05f317094/L02.ipynb
  .. _H 3: https://github.com/let-unimi/handouts/blob/88c5c6d4a88ebccbd741b7f67d0bae75ca3a5b49/L03.ipynb
  .. _H 4: https://github.com/let-unimi/handouts/blob/38b08aa519a8ac6a77cdcd3ea61e025450cf23a8/L04.ipynb
  .. _H 5: https://github.com/let-unimi/handouts/blob/39b69b9faca50a48179925067206ee0310c66642/L05.ipynb
  .. _H 6: https://github.com/let-unimi/handouts/blob/58d1ce62e448feb966cd9bb1c0b37120d415a018/L06.ipynb

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
