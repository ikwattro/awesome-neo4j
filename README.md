# Awesome Neo4j [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome [Neo4j](http://neo4j.com/) resources.

Inspired by the `awesome-*` trend on GitHub.

The goal is to build a categorized community-driven collection of very well-known resources.

Sharing, suggestions and contributions are always welcome!

Thanks to all [contributors](https://github.com/FylmTM/awesome-neo4j/graphs/contributors).

## Tools

### Connectors

#### Java

- [neo4j-jdbc](https://github.com/neo4j-contrib/neo4j-jdbc) - Neo4j JDBC driver
- [neo4j-ogm](https://github.com/neo4j/neo4j-ogm) - Object-Graph Mapping Library for Neo4j
- [spring-data-neo4j](https://github.com/spring-projects/spring-data-neo4j) - Provides support to increase developer productivity in Java when using the neo4j graph database

#### Ruby

- [neo4jrb](https://github.com/neo4jrb/neo4j) - An active model wrapper for the Neo4j Graph Database for Ruby
- [neography](https://github.com/maxdemarzi/neography) - A thin Ruby wrapper to the Neo4j Rest API

#### Python

- [py2neo](https://github.com/nigelsmall/py2neo) - Py2neo is a comprehensive toolkit for working with Neo4j from within Python applications or from the command line.
- [neomodel](https://github.com/robinedwards/neomodel) - An Object Graph Mapper (OGM) for the neo4j graph database, built on the awesome py2neo.

#### PHP

- [neo4jphp](https://github.com/jadell/neo4jphp) - PHP wrapper of the Neo4j REST interface
- [NeoEloquent](https://github.com/Vinelab/NeoEloquent) - A Neo4j ORM - Based on Eloquent
- [NeoClient](https://github.com/neoxygen/neo4j-neoclient) - A PHP HttpClient for the Neo4j ReST API with MultiDB Support

#### Other

- [node-neo4j](https://github.com/thingdom/node-neo4j) - Neo4j graph database driver (REST API client) for Node.js
- [Neo4jClient](https://github.com/Readify/Neo4jClient) - .NET client binding for Neo4j
- [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang
- [neocons](https://github.com/michaelklishin/neocons) - A feature rich idiomatic Clojure client for the Neo4J REST API
- [RNeo4j](https://github.com/nicolewhite/RNeo4j) - Neo4j Driver for R

### Shell

- [cycli](https://github.com/nicolewhite/cycli) - A Command Line Interface for Cypher.
- [neo4j-shell-tools](https://github.com/jexp/neo4j-shell-tools) - A bunch of import/export tools for the neo4j-shell

### Benchmarking

- [neoprofiler](https://github.com/moxious/neoprofiler) - Neo4J database profiling utility

### Deployment

- [docker-neo4j-cluster](https://github.com/ekino/docker-neo4j-cluster) - Up & Running Neo4j cluster in no time
- [docker-neo4j](https://github.com/neo4j-contrib/docker-neo4j) - Container for Neo4j 2.2 Community Edition

### Bolt

- [neo4j-java-driver](https://github.com/neo4j/neo4j-java-driver) - [ALPHA] Java driver for Neo4j binary protocol
- [neo4j-python-driver](https://github.com/neo4j/neo4j-python-driver) - [ALPHA] Python driver for Neo4j binary protocol
- [neo4j-javascript-driver](https://github.com/neo4j/neo4j-javascript-driver) - [ALPHA] JavaScript driver for Neo4j binary protocol

### Development

- [structr](https://github.com/structr/structr) - Graph Application Platform based on Neo4j
- [GraphAware Neo4j Framework](https://github.com/graphaware/neo4j-framework)- GraphAware Framework speeds up development with Neo4j by providing a platform for building useful generic as well as domain-specific functionality, analytical capabilities, (iterative) graph algorithms, etc.

### Cypher

- [cypher-dsl](https://github.com/neo4j-contrib/cypher-dsl) - A Java DSL for the Cypher Query Language and an optional Query DSL mode
- [cypher-vim-syntax](https://github.com/neo4j-contrib/cypher-vim-syntax) - Very basic Vim syntax for Cypher

### Extensions

- [spatial](https://github.com/neo4j-contrib/spatial) - Neo4j Spatial is a library of utilities for Neo4j that faciliates the enabling of spatial operations on data.
- [graphify](https://github.com/Graphify/graphify) - Graphify is a Neo4j unmanaged extension used for document and text classification using graph-based hierarchical pattern recognition.
- [neo4j-warmup](https://github.com/graphaware/neo4j-warmup) - Simple library that warms up Neo4j caches with a single REST call
- [neo4j-uuid](https://github.com/graphaware/neo4j-uuid) - GraphAware Runtime Module that assigns a UUID to all nodes in the graph transparently
- [neo4j-timetree](https://github.com/graphaware/neo4j-timetree) - Java and REST APIs for working with time-representing tree in Neo4j
- [neo4j-reco](https://github.com/graphaware/neo4j-reco) - Neo4j-based recommendation engine module with real-time and pre-computed recommendations.
- [neo4j-noderank](https://github.com/graphaware/neo4j-noderank) - GraphAware Timer-Driven Runtime Module that executes PageRank-like algorithm on the graph
- [neo4j-algorithms](https://github.com/graphaware/neo4j-algorithms) - Custom graph algorithms for Neo4j with own Java and REST APIs
- [neo4j-changefeed](https://github.com/graphaware/neo4j-changefeed) - A GraphAware Framework Runtime Module allowing users to find out what were the latest changes performed on the graph
- [neo4j-tx-participation](https://github.com/jexp/neo4j-tx-participation) - This is a Neo4j Server Extension to make Neo4j REST-API participate in transactions started by the transactional Cypher endpoint.

### Other

- [neoclipse](https://github.com/neo4j-contrib/neoclipse) - Neoclipse is a tool to view, edit and explore Neo4j databases.

## Resources

[List of good Neo4j articles](ARTICLES.md)

### Learning

- [Getting Started with Neo4j](http://neo4j.com/graphacademy/online-course/)
- [Neo4j in Production](http://neo4j.com/graphacademy/online-course-prod/)
- [Neo4j Koans](https://github.com/jimwebber/neo4j-tutorial) - A koan-style tutorial in Java for Neo4j

### Bolt

- [bolt-howto](https://github.com/nigelsmall/bolt-howto) - How to Build a Neo4j Bolt Protocol Driver

### Books

- [Graph Databases](http://graphdatabases.com/) - The Definitive Book on Graph Databases and Introduction to Neo4j
- [A Programmatic Introduction to Neo4j](http://www.amazon.com/Programmatic-Introduction-Neo4j-Jim-Webber/dp/0321902904) - [NOT YET BEEN RELEASED]
- [Neo4j High Performance](https://www.packtpub.com/big-data-and-business-intelligence/neo4j-high-performance/)
- [Learning Neo4j](https://www.packtpub.com/big-data-and-business-intelligence/learning-neo4j-graph-databases) - Run blazingly fast queries on complex graph datasets with the power of the Neo4j graph database

### Miscellaneous

- [Neo4j's Idea board](https://trello.com/b/2zFtvDnV/public-idea-board)
- [Hardware Sizing Calculator](http://neo4j.com/hardware-sizing-calculator)

# License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Dmitry Vrublevsky](https://github.com/FylmTM) has waived all copyright and related or neighboring rights to this work.
