# Web App Security

## Many to Many Relationships

--- 

### A Typical Example

- Example of Many to Man relationship between two entities employee and project.
- In this scenario any given employee can be assigned to multiple projects and a project may have multiple employees working for it.

### Model Class 

- In order to map a many-to-many association, we use the @ManyToMany, @JoinTable and @JoinColumn annotations.
- The @ManyToMany annotation is used in both classes to create the many-to-many relationship between the entities.
- This association has two sides i.e. the owning side and the inverse side.
- The @JoinColumn annotation is used to specify the join/linking column with the main table.

## What I want to know more about

- When you plug into the internet you are assigned an IP address.
- A server has an IP address to access it.
- Browser makes requests to server and server responds to browser.
- We place CSS style sheets in the beginning of the HTML document because we want it to load before and tell the content how it should look.

## Resources/Citations

---

- [Many to Many](https://www.baeldung.com/hibernate-many-to-many)
