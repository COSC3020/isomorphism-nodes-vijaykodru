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

For G1 and G2  to be isomorphic, there must exist a one to one and a onto function meaning a bijection to exists between them. For the one to one function to exist we should be able to uniquley map every vertice in G1 to G2. And for the onto function we must be able to map every vertice in G1 to G2. Now lets say that G1 has n number of vertices and G2 has m number of vertices and n > m. if we start mapping vertices from G1 to G2, we will eventually run out of vertices in G2 because m is less than n making the graphs not one to one because some of the vertices in G1 will be matched to vertices in G2 that are already matched previously. On the other hand if we consider G1 with n vertices and G2 with m vertices where n < m. This will result in running out of vertices in G1 because n is less than m leaving some vetices in G2 to be matched to already match vertices previously. Both the scenarios result in a onto function but not a one to one function making no bijection exists between the graphs. 

Therefore by the above proof we can say that two graphs are not isomorphic if they do not have the same number of nodes.

Reference:

https://www2.math.upenn.edu/~mlazar/math170/notes05-2.pdf

https://courses.grainger.illinois.edu/cs173/sp2024/ALL-lectures/Lectures/graphs1.html

isomorphism-nodes-IshitaPatel18