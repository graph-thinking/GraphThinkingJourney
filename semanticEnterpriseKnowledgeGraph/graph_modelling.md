
# Graph Modelling - Triple Extraction

as shown here - http://corenlp.run/

We try to model all the knowledge around a domain with the maximum degree of granularity as a graph.

In natural language processing, open information extraction is the task of generating a structured, machine-readable representation of the information in text, usually in the form of triples or n-ary propositions (Source: Wikipedia).

Triple extraction may be manual or automatic
The automatic may be with pretrained model example openIE 
* https://stanfordnlp.github.io/CoreNLP/openie.html
* https://nlp.stanford.edu/software/openie.html
* https://github.com/philipperemy/stanford-openie-python

* https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/viewFile/9571/9523/
* https://pykeen.readthedocs.io/en/stable/
* https://towardsdatascience.com/a-gentle-introduction-to-graph-neural-network-basics-deepwalk-and-graphsage-db5d540d50b3
* https://arxiv.org/pdf/1801.08641.pdf
* https://github.com/thunlp/OpenKE

* https://analyticsindiamag.com/ernie-gets-what-bert-doesnt-making-ai-smarter-with-knowledge-graphs/
* https://medium.com/algoanalytics/entity-typing-and-relation-classification-for-knowledge-graph-building-using-ernie-efbf5aeacedb
* http://lzy.thunlp.org/publications/acl2019_ernie.pdf

Graph Sage - Node Embedding - http://snap.stanford.edu/graphsage/

* https://towardsdatascience.com/introduction-to-knowledge-graph-embedding-with-dgl-ke-77ace6fb60ef

To train a model with openKE -- 
* https://www.aclweb.org/anthology/D18-2024/
* https://github.com/thunlp/OpenKE
* https://nlp.csai.tsinghua.edu.cn/~lzy/publications/emnlp2018_openke.pdf
* https://towardsdatascience.com/introduction-to-knowledge-graph-embedding-with-dgl-ke-77ace6fb60ef
* http://139.129.163.161//
* https://arxiv.org/abs/2004.08532
* https://gitee.com/donfar/OpenKE
* https://www.amazon.science/blog/amazons-open-source-tools-make-embedding-knowledge-graphs-much-more-efficient
* https://aws.amazon.com/blogs/machine-learning/training-knowledge-graph-embeddings-at-scale-with-the-deep-graph-library/

ERNIE Classification - Google’s BERT and Baidu’s ERNIE language frameworks.
* https://medium.com/algoanalytics/entity-typing-and-relation-classification-for-knowledge-graph-building-using-ernie-efbf5aeacedb
* https://analyticsindiamag.com/ernie-gets-what-bert-doesnt-making-ai-smarter-with-knowledge-graphs/
* http://lzy.thunlp.org/publications/acl2019_ernie.pdf
* https://arxiv.org/pdf/1905.07129.pdf
* https://www.activestate.com/blog/bert-vs-ernie-the-natural-language-processing-revolution/

KEPLER - https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00360/98089/KEPLER-A-Unified-Model-for-Knowledge-Embedding-and

We segment a topic with a taxonomy 

The segmentation is extra is the taxonomy refers to the entity as a whole (for example for musical instruments extra taxonomy is to segment between clarinet, guitar etc...), while intra taxonomy is to segment pieces of a clarinet or of a trumpet.

A further classification is context of the item (for example a case fof a guitar).


The items are modelled with descriptive (image, short test description), categorical (status: used, new) and quantitative features (size, weigth, price).


Conventions:

to label the nodes we use CamelCase (example Products), to label the edges we use camelCase (example hasImage).
