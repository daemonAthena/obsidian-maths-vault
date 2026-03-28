A set is a collection of objects.

A set is a mathematical construction which must follow the following basic axioms
A set is notated by the following brackets $\{\}$ with objects separated by commas. It can also be represented by a variable, most often a capital letter $S=\{1,2,3\}$. 

If I say something is "in" a set, I use this symbol $\in$
See also [[Logical Operators]] ($\land,\lor,\Rightarrow,\iff$)
See also [[Quantifier]] ($\exists, \forall$)


# Set Operations
## Union
Denoted by $\cup$. It is the set which is a merging of two sets. Meaning
$\forall x$
$x,y \in X \cup Y \iff x \in X \lor x \in Y$

## Intersection
Denoted by a $\cap$. It is the set which only consists of elements contained in two sets. Meaning
$\forall x$
$x \in X \cap Y \iff x \in X \lor y \in Y$

# ZFC (Zermello-Fraenkel + Choice) Axioms

| \#  | Name                    | FOL                                                                          | Laymans Terms                                                                                                          |
| --- | ----------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| 1   | Axiom of extensionality | $\forall$ sets $X,Y$ and elements $x : (x \in X \iff x\in Y) \implies X = Y$ | If two sets have the same exact elements then they are equal                                                           |
| 2   | Axiom of pairing        | $\forall a,b \exists Z : (a,b \in Z )$                                       | given two elements there exists a set containing those elements                                                        |
| 3   | Axiom of subsets        |                                                                              | If you have a set and a rule, you can make a subset constructed from elements of the chosen set with that rule applied |
| 4   | Axiom of the sum set    |                                                                              | You can construct sets that are the the unions of multiple sets                                                        |
