# Graph Theory - Discrete Mathematics

------------------------------------------------------------------------------
White Belt - Theory about graphs
---------------------------------------------------------------------------

* Soft introduction to algorithms -- https://towardsdatascience.com/10-graph-algorithms-visually-explained-e57faa1336f3

* Other list of graph algorithms - https://docs.yworks.com/yfiles-html/dguide/analysis/index.html

## Path - Cycle Finding Algorithms

| Notation | Algorithm | undir - unweighted | dir - unweighted | undir - weighted | dir - weighted |                                                  
| ------------- | ------------- | -------------- | ------------- | ------------- | -------------- |
| BST | [Binary search tree](https://visualgo.net/en/bst?slide=1) | O(N) 
| | [Binary heap](https://visualgo.net/en/heap?slide=1) | O(N) 
| DFS | [Depth first search](https://visualgo.net/en/dfsbfs?slide=1) | O(V) + O(E) = O(V + E)
| BFS | [Breadth first search](https://visualgo.net/en/dfsbfs?slide=1) | O(V) + O(E) = O(V + E)
| SSSP | [Single Source Shortest Path](https://visualgo.net/en/sssp?slide=1) | O(V<sup>2</sup>) | O(E + V) |
| | All Pairs Shortest Path | | |
| | Eulerian cycle (path) - Chinese postman  | https://www-m9.ma.tum.de/graph-algorithms/directed-chinese-postman/index_en.html | https://www-m9.ma.tum.de/Allgemeines/GraphAlgorithmenEn |
| TSP | [Hamiltonian cycle - Traveling salesman](https://visualgo.net/en/tsp?slide=1) | O(V * (V - 1)!) = O(V!) |  O(V^2 * 2^V) |
| MST |  [Minimal Weight Spanning Tree](https://visualgo.net/en/mst?slide=1) 
| | Random Walk | | https://neo4j.com/docs/graph-data-science/current/alpha-algorithms/random-walk/ | https://isquared.digital/blog/2020-04-12-random-walk/

## Other Algorithms 

| Notation | Algorithm | T. C. undir - unweighted | T. C. dir - unweighted | T. C. undir - weighted | T. C. - dir - weighted |                                                  
| ------------- | ------------- | -------------- | ------------- | ------------- | -------------- |
| Residual Network - Augmenting Path | [Network Flow](https://visualgo.net/en/maxflow) | O(max_flow * E) | O(max_flow * E) |
| MCM | [Matching - Maximum Cardinality Matching](https://visualgo.net/en/matching?slide=1) |  |  O ( V <sup>2</sup> E ) |

## Centrality Algorithms -- https://towardsdatascience.com/notes-on-graph-theory-centrality-measurements-e37d2e49550a                                           

| Notation | Algorithm | Time complexity |                                                 
| ------------- | ------------- | -------------- |
| Page Rank | http://www.martingrandjean.ch/wp-content/uploads/2015/10/Gephi-introduction.pdf |
| Betweeness Centrality |  https://www.cl.cam.ac.uk/teaching/1213/L109/stna-lecture3.pdf| 
| Closeness Centrality | https://cambridge-intelligence.com/keylines-faqs-social-network-analysis/|
| Degree Centrality | https://towardsdatascience.com/graph-analytics-introduction-and-concepts-of-centrality-8f5543b55de3|
| Eigenvector Centrality | https://docs.yworks.com/yfiles-html/dguide/analysis/analysis-centrality.html|
| | https://www.lume.ufrgs.br/bitstream/handle/10183/122516/000971709.pdf?sequence=1|

## Community Detection Algorithms

| Notation | Algorithm | Time complexity |                                                 
| ------------- | ------------- | -------------- |
| Louvain | http://haithams.github.io/community_visualization/ |
| Label Propagation | |
| Weakly Connected Components | |
| K-1 Colouring | |
| [Graph Colouring](https://ahmedengu.com/VisuAlgo-GraphColoring/src/index.html) | https://www.slideshare.net/PriyankJain26/graph-coloring-48222920| https://www.geeksforgeeks.org/graph-coloring-applications/ |
| Triangle Count | | |
| Local Clustering Coefficient | | |
| Modularity Optimization | | |
| Strongly Connected Components | | |
| Speaker-Listener Label Propagation | | |


## Similarity Algorithms    

| Notation | Algorithm | Time complexity |                                                 
| ------------- | ------------- | -------------- |
| Node Similarity | | |
| K-Nearest Neighbors | | |
| Approximate Nearest Neighbors | | |
| Cosine Similarity | | |
| Euclidean Similarity | | |
| Jaccard Similarity | | |
| Overlap Similarity | | |
| Pearson Similarity | | |



## Link Prediction Algorithms 

| Notation | Algorithms |                                                    
| ------------- | ------------- |
| | http://ijera.com/papers/Vol2_issue6/DB26703707.pdf |
| | https://hpi.de/fileadmin/user_upload/fachgebiete/mueller/courses/graphmining/GraphMining-08-LinkPrediction.pdf |
| | https://www.hindawi.com/journals/mpe/2014/453546/ | 
| | https://www.researchgate.net/figure/Samples-created-using-Gephi-for-both-data-sets-before-and-after-link-prediction-a-10_fig2_311711865 |
| | http://arno.uvt.nl/show.cgi?fid=147418 |
| | https://linkpredictiontool.blogspot.com/ |
| | https://gitlab.fhnw.ch/marco.romanutti/gephi-plugins/tree/master/modules/LinkPrediction |



## Graph Embeddings Algorithms 
FastRP
GraphSAGE
Node2Vec


* https://www.cs.utexas.edu/~isil/cs311h/lecture-graph1b-6up.pdf
* http://www.math-cs.gordon.edu/courses/mat230/notes/graphs.pdf

Support : Discrete Mathematics - 
* https://faculty.atu.edu/mfinan/main2.pdf
* https://www.cis.upenn.edu/~jean/discmath-root-b.pdf
* https://web.stanford.edu/class/cs103x/cs103x-notes.pdf
* https://home.iitk.ac.in/~arlal/book/mth202.pdf
* https://www.cs.yale.edu/homes/aspnes/classes/202/notes.pdf
* http://discrete.openmathbooks.org/pdfs/dmoi-tablet.pdf


----- other sources ...

[Interactive - tutorial 2](https://d3gt.com/)

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
