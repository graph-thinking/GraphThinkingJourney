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

## White Belt Glossary and Notation - https://visualgo.net/en

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

## Algorithms and Notation

| Path Finding Algorithms | Notation |                                                   
| ------------- | ------------- |
| [Depth first search](https://visualgo.net/en/dfsbfs?slide=1) | DFS |
| [Breadth first search](https://visualgo.net/en/dfsbfs?slide=1) | BFS |
| [Shortest Path](https://visualgo.net/en/sssp?slide=1)| SSSP |                                                   
| [Minimal Spanning Tree](https://visualgo.net/en/mst?slide=1) | MST |
| [Network Flow](https://visualgo.net/en/maxflow) | | 
| [Matching - Maximum Cardinality Matching](https://visualgo.net/en/matching?slide=1) | MCM |
| [Graph Colouring](https://ahmedengu.com/VisuAlgo-GraphColoring/src/index.html) | | 
| Eulerian cycle (path) - Chinese postman  | | 
| [Hamiltonian cycle - Traveling salesman](https://visualgo.net/en/tsp?slide=1) | TSP |  

Yellow Belt - Gephi - https://gephi.org/users/quick-start/
                      https://gephi.org/users/tutorial-visualization/
                      https://gephi.org/tutorials/gephi-tutorial-quick_start.pdf
                      http://derekgreene.com/slides/derekgreene_gephi_slides.pdf 
                      https://www.youtube.com/watch?v=gcfAT8aMxuQ
                      https://hub.packtpub.com/creating-network-graphs-gephi/
                      https://github.com/gephi/gephi-plugins/pull/212
                      https://eight2late.wordpress.com/2015/12/02/a-gentle-introduction-to-network-graphs-using-r-and-gephi/
                      https://medium.com/@615162020027/centrality-and-community-detection-in-macaque-rhesus-brain-networks-with-gephi-0-9-2-ed62cb4d0cf8
                      https://www.youtube.com/watch?v=dSx5_PjaWVE
 networkx and gephi - https://medium.com/analytics-vidhya/implement-louvain-community-detection-algorithm-using-python-and-gephi-with-visualization-871250fb2f25
                      https://github.com/gephi/gephi/issues/2129
                      https://perso.uclouvain.be/vincent.blondel/research/louvain.html
                      https://arxiv.org/pdf/1708.00977.pdf
                      https://meta.wikimedia.org/wiki/Research:Community_visualization_using_Gephi
                      https://dbs.uni-leipzig.de/file/edbt-demopaper.pdf
                      
Yellow Belt - Cytoscape - https://enrichmentmap.readthedocs.io/en/latest/CreatingNetwork.html
                          https://apps.cytoscape.org/apps/with_tag/clustering
                          https://apps.cytoscape.org/apps/with_tag/sequencesimilarity
                          https://efi.igb.illinois.edu/efi-est/tutorial.php
                          http://www.cgl.ucsf.edu/cytoscape/cluster/clusterMaker.shtml
                          http://www.cgl.ucsf.edu/Outreach/Workshops/NIH-Oct-2012/Cytoscape/Analysis%20and%20Visualization%20of%20Biological%20Networks%20with%20Cytoscape%20v6.pdf
                          https://cytogedevo.compbio.sdu.dk/

| Centrality Algorithms | Notation |                                                   
| ------------- | ------------- |
| Page Rank | http://www.martingrandjean.ch/wp-content/uploads/2015/10/Gephi-introduction.pdf |
| Betweeness Centrality |  https://www.cl.cam.ac.uk/teaching/1213/L109/stna-lecture3.pdf| 
| Closeness Centrality | https://cambridge-intelligence.com/keylines-faqs-social-network-analysis/|
| Degree Centrality | https://towardsdatascience.com/graph-analytics-introduction-and-concepts-of-centrality-8f5543b55de3|
| Eigenvector Centrality | https://docs.yworks.com/yfiles-html/dguide/analysis/analysis-centrality.html|
| | https://www.lume.ufrgs.br/bitstream/handle/10183/122516/000971709.pdf?sequence=1|

| Community Detection Algorithms | Notation |                                                   
| ------------- | ------------- |
| Louvain | http://haithams.github.io/community_visualization/ |
| Label Propagation | |
| Weakly Connected Components | |
| K-1 Colouring | |

| Similarity Algorithms | Notation |                                                   
| ------------- | ------------- |

Green Belt

| Link Prediction Algorithms | Notation |                                                   
| ------------- | ------------- |
| | http://ijera.com/papers/Vol2_issue6/DB26703707.pdf |
| | https://hpi.de/fileadmin/user_upload/fachgebiete/mueller/courses/graphmining/GraphMining-08-LinkPrediction.pdf |
| | https://www.hindawi.com/journals/mpe/2014/453546/ | 
| | https://www.researchgate.net/figure/Samples-created-using-Gephi-for-both-data-sets-before-and-after-link-prediction-a-10_fig2_311711865 |
| | http://arno.uvt.nl/show.cgi?fid=147418 |
| | https://linkpredictiontool.blogspot.com/ |
| | https://gitlab.fhnw.ch/marco.romanutti/gephi-plugins/tree/master/modules/LinkPrediction |

Support : [Book](https://www.maths.ed.ac.uk/~v1ranick/papers/wilsongraph.pdf) -- [Videos Sarada Herke](https://www.youtube.com/playlist?list=PLoJC20gNfC2gmT_5WgwYwGMvgCjYVsIQg) -- [Slides](http://www.hamilton.ie/ollie/Downloads/Graph.pdf)



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
