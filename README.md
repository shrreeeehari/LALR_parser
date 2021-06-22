# LALR_parser

LALR parser are same as CLR parser with one difference. In CLR parser if two states differ only in lookahead then we combine those states in LALR parser. After minimisation if the parsing table has no conflict that the grammar is LALR also.

For example,
consider the grammar:

S -> AA <br>
A -> aA | b

Augmented grammar :

S' -> S <br>
S -> AA <br>
A -> aA | b

<img src="images/Iris.png" height="600">


