# Graph Theory - Discrete Mathematics (Industry domain unrelated)

------------------------------------------------------------------------------
White Belt - Theory about graphs
---------------------------------------------------------------------------
* Graph Structure
* Paths
* Trees
* Networks and flows
* Eulerian and Hamiltonian graphs
* Coloring problems
* Connectivity

## White Belt Glossary and Notation

| Terms  | Symbol |                                                         
| ------------- | ------------- |                                          
| Graph | G = (V,E) |                                                    
| Set of Vertex | V(G) = {v1,v2,...,v5} |
| Vertex j | v<sub>j</sub> |
| Set of Edges | E(G) = {e1,e2,...,e6} |
| Edge k | e<sub>k</sub> = (v<sub>j</sub>,v<sub>i</sub>) |
| Ajacency Matrix | |
| Ajacency List | |
| A graph G′ = (V′,E′) is a subgraph of a graph G = (V,E) | |
| Simple Graph| |
| Degree of a vertex v | d(v) |
| Isolated vertex v | d(v) = 0 |
| Complete Graph | K<sub>n</sub> |
| k-regular graph | |
| bipartite graph |
| complete bipartite graph | K<sub>n1, n2</sub> |
| walk | | 
| trail | | 
| path | | 
| walk / trail closed | | 
| cycle | |
| digraph | | 
| edge in digraph (s source node) (t terminal node) | e = (v<sub>s</sub>,v<sub>t</sub>) | |
| v has an in-degree | d<sub>in</sub>(v) |
| v has out-degree | d<sub>out</sub>(v) |
| acyclic graph | |
| u and v in a digraph are strongly connected | |
| connected components | |
| tree | | 
| forest | |
| eccentricity | ε(u) = max<sub>v∈V</sub> d(u,v) | 
| radius | rad(G) = min<sub>u∈V</sub> ε(u) |
| diameter | diam(G) = max<sub>u∈V</sub> ε(u) | 
| center of a graph G | the set of nodes in V of minimal eccentricity |
| leaf l of a tree T |  d(l) = 1 |
| Graph is planar | |
| Network | digraph N = (V,E) with a s source node (d<sub>out</sub>(s) > 0) and a t terminal node (d<sub>in</sub>(t)>0) - for each edge capacity c(e) > 0 |
| Flow | f : V<sup>2</sup>→ R<sup>+</sup> is associated with each edgee= (u,v) |
| Total Flow | F(N) | |
| Cut of a network | |
| Capacity of a cut | |
| Residual network | |
| Augmenting path | |
| k-coloring of a graph G = (V,E) | f : V → 1,...,k such that f(v<sub>i</sub>) !=f(v<sub>j</sub>) if (v<sub>i</sub>,v<sub>j</sub>) ∈ E
| Chromatic number | χ(G) |
| Independent or stable set | S |
| Independence number | α(G) |

## White Belt Algorithms and Notation

| Terms  | Symbol | Link |                                                        
| ------------- | ------------- | ------- |
| Depth first search | DFS | https://visualgo.net/en/dfsbfs?slide=1 |
| Breadth first search | BFS | https://visualgo.net/en/dfsbfs?slide=1 |
| Shortest Path | SSSP | https://visualgo.net/en/sssp?slide=1 |                                                   
| Minimal Spanning Tree | MST ||
| Network Flow | | https://visualgo.net/en/maxflow |
| Perfect matching | | |
| Graph Colouring | | |
| Eulerian cycle (path) - Chinese postman  | | | 
| Hamiltonian cycle - Traveling salesman | | |



Support : [Book](https://www.maths.ed.ac.uk/~v1ranick/papers/wilsongraph.pdf) -- [Videos](https://www.youtube.com/channel/UCV8tyRakGZuXUwD-wYH1yGg) -- [Slides](http://www.hamilton.ie/ollie/Downloads/Graph.pdf) -- [Interactive - tutorial](https://visualgo.net/en) -- [Interactive Graph Colouring tutorial](https://ahmedengu.com/VisuAlgo-GraphColoring/src/index.html)



----- other sources ...

[Interactive - tutorial 2](https://d3gt.com/)

[Interactive - tutorial 3](https://graphonline.ru/en/)

https://erkal.github.io/kite/


we refer to the glossary ...

* https://www.tutorialspoint.com/graph_theory/

* https://study.com/academy/topic/graph-theory-lesson-plans.html

* https://cs.bme.hu/fcs/graphtheory.pdf


* https://www.coursera.org/learn/graphs



* others video - https://www.youtube.com/playlist?list=PLeIMaH7i8JDiRA4fK9QmjvDSZKBJDyxpc

Sarada Herke - https://www.youtube.com/playlist?list=PLoJC20gNfC2gmT_5WgwYwGMvgCjYVsIQg

* https://medium.com/brandons-computer-science-notes/graph-theory-3bd99b24fa2a

* https://medium.com/basecs/a-gentle-introduction-to-graph-theory-77969829ead8

* https://en.wikipedia.org/wiki/List_of_graph_theory_topics



* https://www.youtube.com/channel/UCV8tyRakGZuXUwD-wYH1yGg
* https://www.coursera.org/learn/graphs




* https://medium.com/tebs-lab/graph-theory-table-of-contents-97ccc62b09a6

* https://medium.com/tebs-lab/introduction-to-graph-theory-956929dcda50


* http://mathworld.wolfram.com/topics/GraphTheory.html



* http://home.ku.edu.tr/mudogan/public_html/Introduction%20to%20Graph%20Theory%202E%20-%20West.pdf


! Graph Theory Lessons 
* https://study.com/academy/topic/graph-theory-lesson-plans.html
* https://study.com/academy/lesson/introduction-to-graph-theory.html
* https://jeremykun.com/2011/06/26/teaching-mathematics-graph-theory/


* https://towardsdatascience.com/an-introduction-to-spark-graphframe-with-examples-analyzing-the-wikipedia-link-graph-67e58c20a107
* https://www.datacamp.com/community/tutorials/networkx-python-graph-tutorial
* https://www.analyticsvidhya.com/blog/2018/09/introduction-graph-theory-applications-python/
