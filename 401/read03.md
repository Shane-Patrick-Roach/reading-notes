# Read 03: Java Maps, primitives, and File I/O

## Java type system
---

### Java twofold type system

- primitive in Java consist of int, boolean etc...
- reference types as Integer, Boolean
- every primitve type corresponds to a reference type.
- Objects in Java are slower and have a bigger memory impact than their primitive analogs.


### Pros and Cons

- The decision what object is to be used is based on what application performane we try to acheive, how much memory we have, the amount of availbe memory and what default values should handle.

### How much memory?

- boolean - 1 bits
- byte - 8 bits
- short, char - 16 bits
- int, float - 32 bits
- long, double - 64 bits

#### For arrays

- single element arrays of primitive types are almost always more expensive than the corresponding reference type.


## Java Exceptions

---

### What is an exception?

- Java uses exceptions to handle errors and other exceptional events.
- an event that occurs during the exectution of a program that disrupts the normal flow of instructions.
- using excetions to manage errors has some advantages over traditional error-management techniques.

### How to catch an excetion

- Use of try, catch, and finally blocks
- chained exceptions and logging

## Scanning

---

### What is Scanning?

- Objects of type `scanner` are useful for breaking down formatted input into tokens and translating indivdual tokens according to their data type.
- By default a scanner uses white space to seperate tokens.
- Look at example on docs where they use scanning to read indivdual words in a texr file.


## Things I want to Know More About

---

### What is an arraylist?

To create a mutable and dynamic list, we caan use Java's Array list which allows us to

- Store object references as elements.
- Store elements of the same type.
- Access elements by index (just like arrays)
- Add elements
- Remove elements
- Use of generics rather than primitves.


## References and Citations

---

1. [Java Primitve versus Objects](https://www.baeldung.com/java-primitives-vs-objects)
2. [Exceptions](https://docs.oracle.com/javase/tutorial/essential/exceptions/index.html)
3. [Scanning](https://docs.oracle.com/javase/tutorial/essential/io/scanning.html)
