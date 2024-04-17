[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/AtNXzL3S)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Answer: 
Let graph $A$ have vertices $(1, 2, 3, 4)$ and let graph $B$ have vertices $(a, b, c)$.\
Now if we have a bijection where $f: V_1 \rightarrow V_2$\
we can have $f(1) = a, f(2) = b, f(3) = c, but it is not possible for f(4) to map to one vertex in graph $B$ that is not already mapped to another vertex.\
In this case, we do not actually have a bijection, because not all elements in graph $A$ can map to exactly one element in graph $B$.\
This would prove true for all cases of graphs of different sizes, proving that by definition, graphs with different numbers of nodes cannot be isomorphic.
