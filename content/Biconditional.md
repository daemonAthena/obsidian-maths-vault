Bicondition, or *bicon*, or if and only if, or iff is a logical binary operation which takes two values of the set of $\mathbb{Z} / 2$ and applies the biconditional function which only returns 1 if both operands are **the same** and will otherwise return 0.

The operation is noted as $\iff$ throughout my work. `\iff` in LaTeX.

| Arg 1 | Arg 2 | Return |
| :---: | :---: | :----: |
|  $1$  |  $1$  |  $1$   |
|  $1$  |  $0$  |  $0$   |
|  $0$  |  $1$  |  $0$   |
|  $0$  |  $0$  |  $1$   |
*Truth table of bicon*

# Inversion of xor
Note that the truth values of $\iff$ are the exact same as $\otimes$ but negated.

# Decomposition of Bicon
See [[Implies#Decomposition of Implies|Decomposition of Implies]]
$x \iff y = (x \land y) \lor (\lnot x \land \lnot y)$
