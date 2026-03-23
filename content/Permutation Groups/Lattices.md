## Meet and Join

The meet of two points (a,b) in a lattice is the largest point, x, such that x <= a and x <= b. If two points are next to each other on a lattice usually they are not equal but don't necessarily relate.

The join is simply the opposite. It is the smallest of that which is greater or equal to two elements. Think of it like the supremum and infemum.

![[Pasted image 20241127094646.png]]

## Transitive Closure
> a lattice is formally a [[Partially Ordered Set]] so it's already transitive. thus taking the transitive closure doesn't do anything. However it may be relevant with regards to the drawings for example. Taking the transitive closure of a relation means to add all the edges which correspond to paths in the relation. See this picture is meant to describe a lattice. But if we interpret the picture out of context as relating only elements with arrows between them, then there is no arrow from {z} to {x. y. z}. If we included all these edges in the pitcure it would be messy and be not helpful given we know the relation is supposed to be transitive. Thus in the picture we only drew a relation whose transitive closure was the lattice we want

The representation provided lacks the implied edges of a transitive relation. This representation is called a Hasse Diagram.

## Nonexample

![[Pasted image 20241127100358.png]]
This is a partially ordered set which is not a lattice because join(2,3) is undefined. If a lattice is finite then it must have a max and min element. This need not be true of a poset.