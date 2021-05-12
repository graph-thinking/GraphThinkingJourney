
# Graph Terminology - https://visualgo.net/en

* [Glossary on Graph Theory](https://en.wikipedia.org/wiki/Glossary_of_graph_theory_terms)

| Symbol | Terms  | Comments |                                                         
| ------------- | ------------- | ----------------- |                                          
| G = (V,E) | Graph |                                 
| V(G) = {v1,v2,...,v5} | Set of Vertex  | The vertices u and v are called the end vertices of the edge (u,v) |                    
| v<sub>j</sub> | Vertex j | If two edges have the same end vertices they are Parallel |
| | An edge of the form (v,v) is a loop | 
| E(G) = {e1,e2,...,e6} | Set of Edges | |
| e<sub>k</sub> = (v<sub>j</sub>, v<sub>i</sub>) | Edge k | 
| Ajacency Matrix | |
| Ajacency List | |
| A graph G′ = (V′,E′) is a subgraph of a graph G = (V,E) | |
| Simple Graph| |
| d(v) | Degree of a vertex v | |
| d(v) = 0 | Isolated vertex v | | 
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


*  
*  
*  
*  A Graph is simple if it has no parallel edges and loops
*  A Graph is said to be Empty if it has no edges. Meaning E is empty
*  A Graph is a Null Graph if it has no vertices. Meaning V and E is empty
*  A Graph with only 1 Vertex is a Trivial graph
*  Directive - undirective - digraph
*  Edges are Adjacent if they have a common vertex. Vertices are Adjacent if they have a common edge
*  The degree of the vertex v, written as d(v), is the number of edges with v as an end vertex. 
*  By convention, we count a loop twice and parallel edges contribute separately
*  Isolated Vertices are vertices with degree 1. d(1) vertices are isolated
*  A Graph is Complete if its edge set contains every possible edge between ALL of the vertices
*  A Walk in a Graph G = (V,E) is a finite, alternating sequence of the form ViEiViEi consisting of vertices and edges of the graph G
* A Walk is Open if the initial and final vertices are different. A Walk is Closed if the initial and final vertices are the same
*  A Walk is a Trail if ANY edge is traversed atmost once
*  A Trail is a Path if ANY vertex is traversed atmost once (Except for a closed walk)
*  A Closed Path is a Circuit – Analogous to electrical circuits''



# Graph Properties 

* A graph with odd vertex ... cannot be eulerian ...
