
Going forward the set $\{0,1\}$ will be referred to as "Boolean Logic"
# Magmas
## $(\{0,1\},\lor)$
Boolean logic under the **or** operation
1. is a semigroup
2. is a monoid, and the identity is $0$
3. is not a group since $1$ has no inverse

## $(\{0,1\},\land)$
Boolean logic under the **and** operation
1. **Boolean and** has an **[[Isomorphism]]** with **Boolean or** by way of the function that applies the "Not" unary operation to the input.
2. Identity element is $1$ as it is what $0$ maps to in the isomorphism

## $(\{0,1\},\Rightarrow)$
Boolean logic under the **implies** operation
1. is not a semigroup :( since it is not associative

## $(\{0,1\},\otimes)$ 
Boolean logic under the **xor** operation
1. Is a semigroup
2. is a monoid
3. is a group since all elements are invertable

## $(\{0,1\},\iff)$
Boolean logic under the **biconditional** operation (also called iff for if and only if)
1. There exists an **Isomorphism** between boolean xor and boolean iff therefore they share the same properties

# Rings/Double Magmas

We can combine different binary logic groups and semigroups to get ring candidates and analyze them. 
## $(\{0,1\},\otimes,\lor)$
Boolean logic under xor, or
1. Is NOT a ring since not all elements distribute

## $(\{0,1\},\otimes,\land)$
Boolean logic under xor, and
1. Is a Ring!
	1. Distributive property holds for all elements
	2. $(\{0,1\},\otimes)$ is commutative
2. Is a Field!
	1. $(\{0,1\},\land)$ is commutative
	2. All elements of $(\{0,1\},\land)$ excluding the $\otimes$ identity, $0$, ($0 \land 0 \not\equiv 1$) have an inverse.
	3. We already showed $(\{0,1\},\land)$ has an identity!
## $(\{0,1\},\iff,\lor)$
Boolean logic under iff, or
1. Is isomorphic to $(\{0,1\},\otimes,\land)$ since 
	1. $(\{0,1\},\iff) \cong (\{0,1\},\otimes)$
	2. $(\{0,1\},\lor) \cong (\{0,1\},\land)$
	3. And they have the same isomorphism, $f(x) = \lnot x$

# Variety Generation
The standard algebra used to generate the [[Varieties|variety]] of Boolean Algebras is
$\mathbb{B} = (\{0,1\},\otimes,\land,\lnot,0)$
	We've included $\lnot$ and $0$ because it is important to include ALL operations when talking about varieties.

Some important laws of the variety of Boolean Algebras are:
1. All the laws that apply to rings
2. AND is Idempotent, $A \land A = A$ 
3. AND's identity is $\lnot 0$
4. $A \otimes A = 0$

## Finite Algebras of $\mathbb{B}$
### $\mathbb{B} \times \mathbb{B}$
$(\{(0,0),(0,1),(1,0),(1,1)\},\otimes,\land,\lnot,0)$

### Homomorphic Images of  $\mathbb{B} \times \mathbb{B}$
1. $(\{0,1\},\iff,\lor,\lnot,1)$ is an isomorphism so its basically the same algebra
2. $\mathbb{B}$ using [[Projections]]
3. The Trivial Algebra $\mathbb{B}^0$ $(\{a\},\otimes,\land,\lnot,0)$ in otherwords $a = a$

Every finite boolean algebra is like this. There is no boolean algebra with 3 elements. Ternary logic is incompatible with Boolean algebra. (This is a separate non trivial theorem). You can do it using Legranges theorem to demonstrate why $\mathbb{B}$ is a subset of all algebras in this variety so it must have an even number of elements except the trivial one.

## Infinite Algebras of $\mathbb{B}$
### $\mathbb{B}^\mathcal{I}$ where $\mathcal{I}$ in infinite
The set is 

There may be countable subalgebras
