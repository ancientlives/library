### GitHub - Data Mining

A few notes on options and tools for data mining GitHub 
[Russell, Matthew. "Mining GitHub: Inspecting Software Collaboration Habits, Building Interest Graphs, and More." In 'Mining the Social Web: Data Mining Facebook, Twitter, LinkedIn, Google , GitHub, and More', 448. 2nd ed. O'Reilly Media, 2013.]

#### Contents
* [Property graph](#toc-pg)
* [Ego graph...](#toc-eg)
* [Graph operations](#toc-go)
* [Centrality measures](#toc-cm)
* [Interest edges](#toc-ie)
* ["Follows" edges](#toc-fe)
* [Graph's state](#toc-gs)
* [Centrality measures](#toc-cm)
* [Starred repositories](#toc-sr)
* [Exploring graph updates](#toc-egu)
* [Nodes for programming languages](#toc-nprog)
* [Sample queries for a graph](#toc-sqg)
* [Visualistion of social network](#toc-visual)

##### <a name="toc-pg"></a>Constructing a trivial property graph
Graphs offer a natural abstraction for modeling many real world phenomena.
Graphs are also particularly apt for the representation of data during 
experimentation and analysis, in particular compared to relational databases etc...

*Property graphs*
A property graph is a data structure that represents entities with *nodes* and 
relationships between entities with *edges*. Each vertex has a unique identifier,
a map of propertites, which are defined as standard key/value pairs, and a collection of edges.

Edges are also unique in connecting nodes, can be uniquely identified, and can also 
contain properties.

A *digraph* is so-called because its edges are directed, which need not be the 
case unless the direction of the edge is rooted in meaning for the modeled domain.

eg:        X ----------> Y

With Python, we can use NetworkX to represent such property graphs. Install NetworkX as follows,

`pip install networkx`

        

##### <a name="toc-eg"></a>Constructing an ego graph of a repository and its stargazers

##### <a name="toc-go"></a>Introducing some handy graph operations

##### <a name="toc-cm"></a>Calculating degree, betweenness, and closeness centrality measures...

##### <a name="toc-ie"></a>Adding additional interest edges to the graph...

##### <a name="toc-fe"></a>Exploring the graph's "follows" edges

##### <a name="toc-gs"></a>Snapshotting (pickling) the graph's state to disk

##### <a name="toc-cm"></a>Applying centrality measures to the interest graph

##### <a name="toc-sr"></a>Adding starred repositories to the graph

##### <a name="toc-egu"></a>Exploring the graph after updates with additional starred repositories

##### <a name="toc-nprog"></a>Updating the graph to include nodes for programming languages

##### <a name="toc-sqg"></a>Sample queries for the final graph

##### <a name="toc-visual"></a>Graph visualisation of the social network for an interest graph
