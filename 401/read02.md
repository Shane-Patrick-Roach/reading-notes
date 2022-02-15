# Read 02 Java loops and imports


## Packages and Imports

---

### What is a package in Java?

- Java classes can be grouped together in packages. 
- A package name is the same as the directory name which contains the .java files.
- You declare packages when you define your Java program.

`
The statement order is as follows. Comments can go anywhere.

Package statment (optional).
Imports (optional).
Class or interface definitions.
`

### What are some common imports?

- There are 166 packages containing 3279 classes and interfaces in Java.

## Loops

---

To execute a statement or a group of statements repeatedly - using loops

### Intro to loops

1. for loop

2. while loop
3. do-while loop
`
int i = 0;
do {
    System.out.println("Do-While loop: i = " + i++);
} while (i < 5);
`
4. for each loop


## Things I want to know more about
#### How do you declare an object in java?

---

- unlike primitves, objects creation is a bit more complex. 
- We trigger the initialization using the ***new*** keyword. This in return, invokes a constructor and initialzes the object in memory
- example constructor
`public User(String name, int id) {
    this.name = name;
    this.id = id;
}
`
- use constructor to create a User object with initial values for its properties.
`User user = new User("Alice", 1);`



## Resources/Citations
--- 

- [Java Imports and packages](https://perso.ensta-paris.fr/~diam/java/online/notes-java/language/10basics/import.html)
- [Java loops](https://www.baeldung.com/java-loops)
