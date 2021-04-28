# Graph Data Storage

The common way to store graph is called Property Graph.

Popularity of graph db - https://db-engines.com/en/ranking_categories

* In the datastorage with schema they have standardized the SQL and now the [GQL](https://www.gqlstandards.org/) - [ISO STANDARD](https://gql.today/)

** There are implementations of the main db SQL

Opensource following the standard 
[Postgres](https://age.apache.org/) - https://www.youtube.com/watch?v=r4-b0Z99izA

Proprietary
[Oracle](https://docs.oracle.com/database/121/SPATL/what-is-oracle-spatial-and-graph.htm#SPATL440) - https://blogs.oracle.com/oraclespatial/graph-database-and-analytics-for-everyone

[Microsoft](https://docs.microsoft.com/it-it/sql/relational-databases/graphs/sql-graph-architecture?view=sql-server-ver15) - https://cloudblogs.microsoft.com/sqlserver/2017/04/20/graph-data-processing-with-sql-server-2017/

[SAP - HANA](https://help.sap.com/viewer/f381aa9c4b99457fb3c6b53a2fd29c02/1.0.12/en-US/7734f2cfafdb4e8a9d49de5f6829dc32.html)
- https://developers.sap.com/group.hana-aa-graph-overview.html

[Redis Graph](https://oss.redislabs.com/redisgraph/) - https://iamondemand.com/blog/redisgraph-a-fresh-graph-database-based-on-redis/

The query language is inspired a lot from [opencypher](http://www.opencypher.org/)

Here some examples of Many2Many query (in SQL we use bridge table) - we gain in code and performances

Here some examples of FriendOfAFriendQuery (FOAF) - we gain in code and performances

Here some examples of hybrid query - https://www.slideshare.net/openCypher/agensgraph-sql-and-cypher-integration
*** https://stackoverflow.com/questions/56173338/hybrid-query-example-in-agensgraph

The NoSQL (Schemaless) STANDARD DE FACTO - [Gremlin](http://tinkerpop.apache.org/) and [its evolution](http://tinkerpop.apache.org/docs/current/dev/future/) 

While the implementation for Property Graph in the NoSQL domain are the following:

Opensource Following the standard - Janus Graph on top of Cassandra....

Proprietary 

[Microsoft - Cosmos](https://towardsdatascience.com/getting-started-with-graph-databases-in-azure-cosmos-db-cbfbf708cda5)

[Amazon - Neptune](https://aws.amazon.com/neptune/?nc1=h_ls)

[SAP](https://www.orientdb.org/)


The query language - https://tinkerpop.apache.org/gremlin.html
