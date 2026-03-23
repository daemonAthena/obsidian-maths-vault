
## How to Parse

![[Pasted image 20241125153002.png]]

When we have a permutation we can write it compactly by writing all the cycles in how numbers are assigned to each other.

(1,3,5,2,8)(4)(6,7) => there are 3 separate cycles each assigning the number listed to the next in the cycle. A cycle of only one number implies that a number is assigned back onto itself and the number at the end of the cycle loops back around to the beginning.

Sometimes we don't bother writing down the 1-cycles because they can just be inferred by absence.

## Composing Permutations

It is common for GAP to use f * g as g(f(x)) but some authors interpret it the standard way for math which is f(g(x)). We will use the GAP notation.

|                           | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   |
| ------------------------- | --- | --- | --- | --- | --- | --- | --- | --- |
| (1,2)                     | 2   | 1   | 3   | 4   | 5   | 6   | 7   | 8   |
| (1,2,3,4,5,6,7,8)         | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 1   |
| (1,2) * (1,2,3,4,5,6,7,8) | 3   | 2   | 4   | 5   | 6   | 7   | 8   | 1   |
In disjoint cycle notation (1,2) * (1,2,3,4,5,6,7,8) = (1,3,4,5,6,7,8) (2)

Weird that a 2-cycle * and 8-cycle is a 7-cycle (not always true)

> Note that when an element is 1 cycle in the first permutation it ends up just copying the destination of the second.

All permuations have inverses by group property. Inverting them in DJC notation is easy because it's just (1,2)^-1 = (2,1).

