# Spring RESTful Routing & Static Files


## How do you access data with JPA?

### Define a Simple Entity
- `@Entity` indicates that it is a JPA entity. 

### Create Simple Queries
- Spring Data JPA focuses on using JPA to store data in a relational database. Its most compelling feature is the ability to create repository implementations automatically, at runtime, from a repo interface.

### Create an Application Class
- Spring Initilizer creates a simple class for the application. 

### Build an executable JAR
- You can run the application from the command line with Gradle or Maven. You can also build a single executable JAR file that contains all the necessary dependencies, classes , and resources and run that. 

### Summary of process
- Succesfully made a simple application that uses Spring Data JPA to save objects to and fetch them from the database, all without writing a concrete repository implmenetaion. 


## Spring Data Repos

- Crud Repository => provides CRUD functions
- PagingAndSortingRepository => provides methods to do pagination and sort records.
- JpaRepository provides JPA related methods such as flushing the persistence contect and delete records in a batch.

### CrudRepository

- Save
- findOne
- findAll
- count
- delete
- exists

### PagingAndSortingRepository

When using Pageable, we create a pageable object with certain properties and weve to specify at least.

1. Page Size
2. Current Page Number
3. Sorting

### JPARepository

- findall
- findall(...)
- save(...)
- flush
- saveAndFlush()
- deleteInBatch

### Downsides of Spring Data Repositories

- We have to be careful to not expose these internal implementation details.
- We expose a complete set of persistence method at once.

## Resources/Citations

- [Spring guide: Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)
- [CrudRepository, JpaRepository, and PagingAndSortingRepository in Spring Data](https://www.baeldung.com/spring-data-repositories)
