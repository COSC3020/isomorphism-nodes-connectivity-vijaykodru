[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ppBU16qM)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


To prove that if two graphs A and B have the same number of nodes and are completely connected, they must be isomorphic we start by the definition. According to the definition of isomorphism, for two graphs to be isomorphic, there must exist a bijection—a one-to-one and onto function—between their vertices. This means that every vertex in one graph uniquely corresponds to a vertex in the other graph. 

Given, A = {V1, E1} and B = {V2, E2} be two graphs with the same number of nodes n. Both graphs are completely connected, meaning that each node in A is connected to n-1 other nodes through edges in that same graph, and the same is true for graph B. 

That said if we take any vertex in Graph A we can always find a corresponding vertex in graph B in any permutation. This is because all the nodes are connected to each other in both the graphs making it true that we always find a bijection between them. 

For any node in graph A there exists a unique corresponding node in graph B meaning that for any node u in V1, there exists a counterpart node in V2, 

$u$ $\in$ $V_1$, $f(u)$ $\in$ $V_2$ is unique

this applies to any permuted pair of edges

$(u , v)$ $\in$ $E_1$ , there exists a matching edge $(f(u) , f(v))$ $\in$ $E_2$ 

The above satisfies isomorphism. This is because both graphs have the same number of nodes and are fully connected. Thus, we can establish a one-to-one and onto function (bijection) between the vertices of graphs A and B proving that they are isomorphic.

Therefore, by satisfying the conditions of isomorphism having the same number of nodes and being completely connected—graphs A and B must be isomorphic.

Reference:

https://www2.math.upenn.edu/~mlazar/math170/notes05-2.pdf 

https://courses.grainger.illinois.edu/cs173/sp2024/ALL-lectures/Lectures/graphs1.html

isomorphism-nodes-connectivity-Dhruv8806

isomorphism-nodes-connectivity-swilso59-1
