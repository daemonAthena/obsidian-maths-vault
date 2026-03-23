
## Definition

A digraph is a set with a binary relation (set of ordered pairs made from elements in the set) on it. It is simpler than a group. In GAP digraphs will always be finite.

![[Pasted image 20241126142309.png]]

Like my polycule digraph which is very complicated and luna fruitlessly tried to model.

Category theory utilizes digraphs with edges labeled and can be composed 
(a->b->c => a->c)

Categories are to digraphs what semigroups are to sets. A category is a spicy digraph.

GAP can store a digraph in two ways like a python list vs a tuple. (mutable/immutable)

immutable digraphs are stored and can be given back immediately when queried. Attribute preservation is a compelling reason to use immutable data structures when possible.

You may be working with adjacency lists when inputting specific digraphs.



