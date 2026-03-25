Implies is a logical binary operation which takes two values of the set of $\mathbb{Z} / 2$ and applies the "implies" function which only returns 0 if True implies False.

The operation is noted as $\Rightarrow$ throughout my work. `\Rightarrow` in LaTeX.

| Arg 1 | Arg 2 | Return |
| :---: | :---: | :----: |
|  $1$  |  $1$  |  $1$   |
|  $1$  |  $0$  |  $0$   |
|  $0$  |  $1$  |  $1$   |
|  $0$  |  $0$  |  $1$   |
*Truth table of Implies*

# Decomposition of Implies
It is well know that $x \Rightarrow y = \lnot x \lor y$.
This can easily be verified as they share the same truth table.