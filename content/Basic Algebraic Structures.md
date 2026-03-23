# Algebra
$(\mathcal{S},☿,...)$
An **Algebra** is a set with any number of [[Operation|operations]] with any arities 
# Magma
A **Magma** is a set with a binary operation.
*an example of a magma*:
$(\emptyset,\cdot)$
# Semigroup
A **Semigroup** is a magma whose operation is associative.
# Monoid
A **Monoid** is a semigroup with a nullary operation which takes a value $e$. This element acts as the identity. $$e \cdot x = x \cdot e = x$$
# Group
A **Group** is a Monoid with **invertibility**. Meaning there is a unary operation called inversion that maps any element $x$ its **inverse** $\bar{x}$ such that 
$$x \cdot \bar{x} = \bar{x} \cdot x = e$$
To put it a different way, if $x$ exists in a group, it has an inverse $\bar{x}$ which satisfies the above equation.
# Ring
A **Ring** is a more complex group. It has 4 additional properties
1. It is a group with an additional binary operation (**Double Magma**) $(\mathcal{S},+,\cdot)$.
2. $(\mathcal{S},+)$ must be **commutative** 
3. The **distributive law** must hold for $(\mathcal{S},+,\cdot)$
4. $(\mathcal{S},\cdot)$ must be a semigroup
It follows from the property of rings that $0$, the additive identity, functions as a **destructor** in $\cdot$.
# Field
A **Field** is a more complex Ring. 
1. $(\mathcal{S},\cdot)$ is commutative
2. All elements in $(\mathcal{S},\cdot)$ except $0$ must have an inverse
3. $(\mathcal{S},\cdot)$ must have an identity noted as $1$.
