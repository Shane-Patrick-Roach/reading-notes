# Document Store

A document store is centered around documents (XML, JSON, binary, etc), where document stores all informaation for a given object.

Document stores provide API's or a query language to query based on the internal strucutre of the document itself. 

Document stores provide high flexibility and are often used for working with occasionally changing data. 


## Key-value store

A key value store generally allows for O(1) reads and writes and is often backed by memory or SSD. Allow for storing of metadata with a value.

Is the basis for more complex system systems such aas a document store, and in some cases a graph database.


## Graph database

Each node is a recor and each aarc is a relationship between two nodes. Optimized to represent complex relationships with many foreign keys or many-to-many relationships.

They offer high performance for daata models with complex relationships, such as a social network. 
