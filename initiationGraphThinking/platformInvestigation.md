# Platform inspired by [Neo4j platform](https://neo4j.com/blog/graph-algorithms-in-neo4j-neo4j-graph-analytics/)

![alternative text](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/plantuml/plantuml-server/master/src/main/webapp/resource/test2diagrams.txt)


![alternative text](http://www.plantuml.com/plantuml/proxy?cache=no&src=/https://raw.github.com/graph-thinking/graphAnalytics/blob/main/test.txt)



Platform: 
* Postgres GQL + Age → Docker - https://age.apache.org/
* https://www.postgresql.org/about/news/announcing-the-release-of-apache-age-030-2160/
* https://www.youtube.com/watch?v=9ruT8UjKKDc
* https://hub.docker.com/r/sorrell/agensgraph-extension-alpine
* Jupyter
* Scraping 
* Not linear Ingestion 
* Graph Data Storage - Not linear Storage - Schemafull (SQL) - GQL - Standard 
* Graph Data Storage - Not linear Storage - Schemaless (NoSQL) - Gremlin - Standard de facto
* Not linear Retrivial 
* Not linear Processing

Tools:

[Gephi Beginner](http://derekgreene.com/slides/derekgreene_gephi_slides.pdf) - 

* example of report results with sigmajs - http://mlg.ucd.ie/networks/politics-uk.html
* example of report results with d3js - http://bruce.sauls.net/d3/LesMis.html

* [1st tutorial](https://gephi.org/users/quick-start/)
* [2nd tutorial](https://gephi.org/users/tutorial-visualization/)

Tutorial Import data 
* https://research.bowdoin.edu/digital-computational-studies/digital-computational-studies/excel-data-and-gephi-data-laboratory/

Tutorial Related #############################################################
* SNA - Facebook - Facebook Graph Api - apps.facebook.com/netvizz/

Ways to find out information from your graph - to express in your report: 

########### Traditional Manipulation ###########################

############# Filter #################
Example : click the "Filters" tab on the right
Expand the "Attributes" folder
Double-click the "Equal" folder
Drag “sex” down to the “Queries” below.
Click the "Filter" button

############## Color ##################
Example : select a "partition" (categorical) node variable from your data. 
the variable called "State"
Click on "Partition"
Click on "Nodes"
Choose "State" from the drop down
Click "Apply"

########### Less Traditional Manipulation - Geometry ###########

############## Layout ##################
Gephi adjusts the nodes and edges in the network by the layout feature. It prioritizes different properties of the network.

############## Size ####################
Resize nodes uniformly
Click on the selection box icon on the left vertical toolbar
Draw a box around all nodes to select them all
Click on the diamond icon on the left vertical toolbar
Click on a node, then drag the mouse up and down to increase and decrease the size

Resize nodes according to a numerical variable
Click on the "Ranking" tab
Click on "Nodes"
Select a variable (e.g., Degree) from the drop down
Choose a minimum and maximum size as a range for the size of the nodes
Click the "Apply" button


######## Graph Statistics ##############
Example : Click the Statistics tab on the right hand side
Run the “modularity” statistic as a first example. 
This creates a new way to view your graph. It also populates a new cell in your data laboratory.
Click into the “Appearance” tab on the left-hand side. Under “nodes” click “modularity class” in the “Partition” tab.

Color your nodes by community
Once you've calculated modularity, we can color nodes according to their communities. Go to the Partition pane (on the left side of the Gephi window) and click on the little Refresh icon. From the dropdown window, select Modularity Class. 

#########################################
Excel for graph thinker : Gephi.org
To install on linux use - jdk - https://adoptopenjdk.net/?variant=openjdk8&jvmVariant=hotspot
#########################################

[Gephi Advanced](http://www.martingrandjean.ch/wp-content/uploads/2015/10/Gephi-introduction.pdf) 

* https://www.slideshare.net/Cloud/sp1-exploratory-network-analysis-with-gephi
* https://www.slideshare.net/digitalmethods/netvizz-netvizz-dmi13

Graph Data  ##########################################################

Gephi Graph Data Format
https://gephi.org/users/supported-graph-formats/
 
In particular 
a lof of info gexf example : le miserables --- http://networkrepository.com/lesmis.php
few info two CSVs : https://gist.github.com/futureperfect/2096812
also TSV - tabular ....

Folder - graph dataset
https://dhs.stanford.edu/gephi-workshop/sample-graph-data/
https://github.com/gephi/gephi/wiki/Datasets
http://networkrepository.com/

Your own CSV Graph Data preparation - tutorial 
http://humnviz.blogs.bucknell.edu/files/2015/11/Data-Preparation-for-Gephi.pdf
https://seinecle.github.io/gephi-tutorials/generated-html/importing-csv-data-in-gephi-en.html

##############################################################################

* https://www.youtube.com/watch?v=gcfAT8aMxuQ
* https://hub.packtpub.com/creating-network-graphs-gephi/
* https://github.com/gephi/gephi-plugins/pull/212
* https://eight2late.wordpress.com/2015/12/02/a-gentle-introduction-to-network-graphs-using-r-and-gephi/
* https://medium.com/@615162020027/centrality-and-community-detection-in-macaque-rhesus-brain-networks-with-gephi-0-9-2-ed62cb4d0cf8
* https://www.youtube.com/watch?v=dSx5_PjaWVE


 networkx and gephi - 
 * https://medium.com/analytics-vidhya/implement-louvain-community-detection-algorithm-using-python-and-gephi-with-visualization-871250fb2f25
 * https://github.com/gephi/gephi/issues/2129
 * https://perso.uclouvain.be/vincent.blondel/research/louvain.html
 * https://arxiv.org/pdf/1708.00977.pdf
 * https://meta.wikimedia.org/wiki/Research:Community_visualization_using_Gephi
 * https://dbs.uni-leipzig.de/file/edbt-demopaper.pdf

As python and excel - or excel macro --- visual basic we have python and gephi ---       
* https://github.com/totetmatt/GephiStreamer  
* https://github.com/samuelegervasio/Gephi-python-module 
* https://jsideas.net/creating-an-edge-list-for-gephi-with-python/   
* https://westgrid.github.io/trainingMaterials/materials/gephi/         
* https://pypi.org/project/GraphiPy/ 
* https://stackoverflow.com/questions/35936991/how-to-create-gephi-network-graphs-from-python
                      
Yellow Belt - Cytoscape - https://enrichmentmap.readthedocs.io/en/latest/CreatingNetwork.html
                          https://apps.cytoscape.org/apps/with_tag/clustering
                          https://apps.cytoscape.org/apps/with_tag/sequencesimilarity
                          https://efi.igb.illinois.edu/efi-est/tutorial.php
                          http://www.cgl.ucsf.edu/cytoscape/cluster/clusterMaker.shtml
                          http://www.cgl.ucsf.edu/Outreach/Workshops/NIH-Oct-2012/Cytoscape/Analysis%20and%20Visualization%20of%20Biological%20Networks%20with%20Cytoscape%20v6.pdf
                          https://cytogedevo.compbio.sdu.dk/


python library [Networkx](https://networkx.org/)


Open Network Data: 
* https://towardsdatascience.com/getting-started-with-network-datasets-92ec54958c07
* Network Data Sets - https://kateto.net/2016/05/network-datasets/
* http://networksciencebook.com/translations/en/resources/data.html
* https://networkdata.ics.uci.edu/resources.php
* http://konect.cc/

