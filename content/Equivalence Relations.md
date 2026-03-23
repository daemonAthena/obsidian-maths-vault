
# Equivalence Relations

a relation $\sim$ is an equivalence relation if it satisfies the following properties
1. Reflexivity $x \sim x$
2. Symmetry $x \sim y \iff y \sim x$
3. Transitivity $x \sim y \land y \sim z \implies x \sim z$

Equivalence relations cleanly partition sets. [[Partition|Partitions]] and equivalence relations are equivalent.

# Congruence
Congruences exist to create **Quotient Algebras** which are sort of like building blocks to bigger algebras.

Congruences are Equivalence Relations which hold that for an algebra (applying to all operations)

if $a \sim b$ and $c \sim d$ then $a☿c \sim b☿d$

Partitions become their own algebras and steal an operation from the previous algebras. This is a quotient algebra.

E.X.
$\mathbb{Z}$ is a ring
The relation which makes two elements of $\mathbb{Z}$ equivalent if they are the same $mod2$ is a congruence. The quotient is $\mathbb{Z}mod2$. The partition has 2 blocks, the evens and the odds. 