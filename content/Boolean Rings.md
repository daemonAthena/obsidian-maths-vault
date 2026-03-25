Boolean Rings are an [[Basic Algebraic Structures#Algebra|Algebra]] $(S,\otimes,\land)$ with two binary operations which satisfy the following axioms:
# Axioms

| \#     | Name                                           | FOL                                                                         |
| ------ | ---------------------------------------------- | --------------------------------------------------------------------------- |
| 1.     | Closure under addition                         | $\forall a,b \in S: a\otimes b \in S$                                       |
| 2.     | Associativity under addition                   | $\forall a,b \in S : (a \otimes b) \otimes c = a \otimes (b \otimes c)$     |
| 3.     | Commutativity under addition                   | $\forall a,b \in S : a \otimes b = b \otimes a$                             |
| 4.     | Identity element under addition                | $\exists 0 \in S : \forall a \in S: a \otimes 0 = a = 0 \otimes a$          |
| 5.     | Closure under product                          | $\forall a,b \in S: a\land b \in S$                                         |
| 6.     | Associativity under product                    | $\forall a,b \in S : (a \land b) \land c = a \land (b \land c)$             |
| 7.     | Identity element for product                   | $\exists 1 \in S : \forall a \in S: a \land 1 = a = 1 \land a$              |
| **8.** | **Idempotence of product**                     | $\forall a \in S : a \land a = a$                                           |
| 9.     | distributive property of product over addition | $\forall a,b,c \in S : a \land (b \otimes c) = a \land b \otimes a \land c$ |

You will note that the thing which distinguishes a boolean ring from others is idempotence of the product. 
