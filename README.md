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


According to te defination of isomorphism, for two graphs to be isomorphic there must exist a one to one and onto function meaning a bijection function.  Now to prove that two graphs are not isomorphic if they do not have the same number of nodes let's consider two graphs G1 and G2. Let's say that G1 has 3 vertices and G2 has 4 fours vertices now for them to show a one to one function we need to be able to match every vertice in G1 to a unique vertice in G2. As we continue to do this, we will run out of vertices in G1 resulting in some vertices in G2 not matched up with any vertices. This does not prove the one to one function and the onto function resulting in the graphs to be not isomorphic. This is the same result when we consider 4 vertices in G1 and 3 vertices in G2. as we will run out of vertices in G2 for the vertices in G1 to be matched.

Reference:

https://www2.math.upenn.edu/~mlazar/math170/notes05-2.pdf
https://courses.grainger.illinois.edu/cs173/sp2024/ALL-lectures/Lectures/graphs1.html