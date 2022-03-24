# Android: Rooms


## What is Room?
--- 

- Apps that handle non-trivial amounts of data can benefit from persisting data locally.
- Persist data locally so users can still access offline.
- The room persistence library provides an abstraction layer over SQLite to allow fluent DB access while harnessing the full power of SQLite.
- Benefits include; Compile-time verification of SQL queries, Convenience annotations that minimize repetitive and error-prone boilder plate code, and streamlined db migration paths.

### How to use ROOMs?

- To use Room in your app, add the following dependencies to your app's build.gradle file.

### Primary Componenets of room

1. The database class - holds the db and serves as the main access point for the underlying connection to your apps persisted data.
2. Data entities - represent tables in your DB
3. Data access objects - provides methedos that your app caan use to query, update, insert, and delete data in the DB.


### How to define data in your entities

- When you use the Room persistence library to store your app's data, you define entities to represent the objects that you want to store. Each entity corresponds to a table in the associated Room database, and each instance of an entity represents a row of data in the corresponding table.
- You define each Room entity as a class that is annotated with @Entity. A Room entity includes fields for each column in the corresponding table in the database, including one or more columns that comprise the primary key.

### How to define relationships between objects

- Because SQLite is a relational database, you can define relationships between entities. Even though most object-relational mapping libraries allow entity objects to reference each other, Room explicitly forbids this.
- In Room, there are two ways to define and query a relationship between entities: you can model the relationship using either an intermediate data class with embedded objects, or a relational query method with a multimap return type.

### How to access data in Room DAO

- When you use the Room persistence library to store your app's data, you interact with the stored data by defining data access objects, or DAOs. 
- Each DAO includes methods that offer abstract access to your app's database. At compile time, Room automatically generates implementations of the DAOs that you define.
- Room provides convenience annotations for defining methods that perform simple inserts, updates, and deletes without requiring you to write a SQL statement. Example `@Insert`, `@Update`, `@Delete`.








## Resources/Citations

- [Rooms](https://developer.android.com/training/data-storage/room)
- [Rooms: Defining Data](https://developer.android.com/training/data-storage/room/defining-data)
- [Rooms: Defining Relationships](https://developer.android.com/training/data-storage/room/relationships)
- [Rooms: Accessing Data](https://developer.android.com/training/data-storage/room/accessing-data#java)
