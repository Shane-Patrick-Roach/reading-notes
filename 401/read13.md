# Related Resources and Integration Testing

## Working with Relationships in Sping
---

### One to One Relationship

- Define two `@entity` classes. Using `OneToOne` annotaation. The association is owned by the Library end of the association in the provided example.
- We must be careful to have different names for each associaation resources. Otherwise we will encounter a JsonMappingException.

### The Repositories

- In order to expose these entities as resources, create interfaces for each of them, by extending the CrudRepository interface.

### One-To-Many Relationship

- A one to many relationship is defined using the @OneToMany and @ManyToOne annotations and can have the optional@RestResource annotation to customize the associataion resource.

### Many-To-Many Relationship

- A many to many relaationship is defined using @ManyToMany annotation, to which we can add @RestResource.

## Integration Testing in Spring
---

- Integration testing plays an important role in the applicaation development cycle by verifying the end to end behavior of a system.
- Learn to write MVC test framework to write and run integration tests that test controllers without explicitly starting a Servlet container.

### Enable Spring in Tests With JUNIT5 

- JUnit 5 defines an extension interface through which classes can integraate with the Junit test.
-`@ExtendWith` annotation to test our classes and specifying the extension class to load.

### How to write an integraation test in Spring

- perform() - will call a GET request method, which returns ResultActions.
- andDo(print()) - will print the request and response.
- andExpect() - will expect the provided argument. 


## Things I want to know more about
---
### Persisting Data JPA

1. Add an `entity` annotation
2. Add an ID and annotatate it with `@Id`
3. Add a default constructor if one is not present.
4. Make a repository interface with the class to put in the db along with the ID type.
5. Create methods with this syntax: Then add into controller, with `@Autowired` annotation. 
6. Autowire an instance of the controller.

### What is a Restful API?

### What is MVC?

- The MVC is an architectural pattern that seperates the application into three main logical components. Model, View, and Controller.
- Each of them are built to handle specific development aspects of an application.
- MVC is one of the most frequently used industry standard web development framework to create scalabe and extensible projects.

### What are design patters?

## Resouces/Citations
---

- [Spring Data Rest Relationships](https://www.baeldung.com/spring-data-rest-relationships)
- [Integration Testing](https://www.baeldung.com/integration-testing-in-spring)
