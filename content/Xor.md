Xor is a logical binary operation which takes two values of the set of $\mathbb{Z} / 2$ and applies the "exclusive or" function which only returns 1 if both operands are different and will otherwise return 0.

The operation is noted as $\otimes$ throughout my work. `\otimes` in LaTeX.

| Arg 1 | Arg 2 | Return |
| :---: | :---: | :----: |
|  $1$  |  $1$  |  $0$   |
|  $1$  |  $0$  |  $1$   |
|  $0$  |  $1$  |  $1$   |
|  $0$  |  $0$  |  $0$   |

*Truth table of Xor*
Note that this is an inversion of $\iff$
# Decomposition of Xor
see also [[Biconditional#Decomposition of Bicon|Decomposition of Biconditional]]
$x \otimes y$ = $\lnot(x \iff y)$ = $(x \lor y) \land \lnot(x \land y)$ = $(x \lor y) \land (\lnot x \lor \lnot y)$

# Cancellative Property ❓

Xor is a fascinating operation because for any elements $a,b \in S$, 
$$b \otimes a \otimes a = b$$
This is because in the monoid $(\{0,1\},\otimes)$, you have that $e = 0$ and $\forall a \in \{0,1\} : a \otimes a = 0$

This principle abides by the [[Law]] requirements therefore any [[Varieties|Variety]] with $\otimes$ exhibits this. This is why we see it in [[Binary Numbers]] at scale and in programming.