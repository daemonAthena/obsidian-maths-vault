**Isomorphism** is a powerful tool in mathematics. It can be used to demonstrate that two things share the same properties without having to individually prove it for both of them (e.g. associativity).

To prove two algebras are **Isomorphic** the following must be satisfied for two algebras, $(X,☿)$ and $(Y,\oplus)$:
	There exists a **bijective** function $f:X \to Y$ such that $$f(x_{1}☿x_{2}) = f(x_{1})\oplus f(x_{2})$$for all $x_{1},x_{2} \in X$.


# Multiple Magma Case
If it is known that
1. $(\{0,1\},\iff) \cong (\{0,1\},\otimes)$ under $f$
2. $(\{0,1\},\lor) \cong (\{0,1\},\land)$ under $g$
Then
if $f = g$, $(\{0,1\},\iff,\lor) \cong (\{0,1\},\otimes,\land)$

So in otherwords, if we want to show that two multimagmas are isomorphic, We need to show that there exists a single isomorphism which satisfies the transformation of all magmas in the two multimagmas. (I encourage you to be lazier with this knowledge)

Lunas way: If we want to show two algebras are isomorphic we need to show there exists a single bijection which preserves all operations of the algebras.

# Model Theory Proof
There is a proof which shows this is true for all first order statements and any two algebras.
See https://www.math.toronto.edu/weiss/model_theory.pdf

## High Level Explanation
An isomorphism is effectively a renaming of all elements in an algebra therefore it is intuitively obvious that the properties should hold. There are many examples such as boolean and, boolean or.
> Cecil is good at computer science. There exists an isomorphism between Lilith and Cecil, so obviously Lilith is good at computer science.

