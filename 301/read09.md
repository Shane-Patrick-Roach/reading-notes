# Reading 08


## Functional Programming Concepts

--- 

### What is functional programming?

- A style of building the structure and elements of computer programs
- Treats compuation as the evaluation of mathmatical functions and avoids changing-state and mutable data.

### What is a pure function and how do we know if something is a pure function?

A function is pure if it...

1. it returns the same result if given the same arguments (deterministic).
2. It does not cause any observable side effects.


### What are the benefits of a pure function?

- stable consistent, predictable
- Given the same parameters, pure functions will always return the same result.
- Easier to test

### What is immutability?

**Immutability** - ***Unchanging over time or unable to be changed.*** 

- When data is immutable, its state cannot be changed onces it is established.
- Everything after is creating a new object with a new value if you need to use an immutable object.


### What is Referential transparency?

- If a function consistently yeilds the same result for the same input, its is said to be **referentially transparent**
- WIN = `pure functions + immutable dataa = referential transparency`

## Videos

---

## Node JS Tutorial for Beginners #6 - Modules and require()

### What is a module?

- Essentailly just another JS file.

### What does the word ‘require’ do?

- to create a pathway to require a module. 

### How do we bring another module into the file the we are working in?

- use **require** on specific file you want to bring in the data.
- **export** must be used on module

### What do we have to do to make a module available?

- **export** (what ever you want to make avialbe)

## Things I want to Know more about

---

1. What is Node.JS? - as an asynchronous event- driven JS runtime, Node.js is  designed to build scalable network applications. Upon each connection, the callback is fired, but if there is no work to be done, node.js will sleep...zzzz..
2. HTTP is a first class citizen in Node.js, which is designed with streaming and low latency in mind. This makes node.js well suited for the founcdation of a web library or framework. 


## References/Citations
---
- [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)
- [Node JS Tutorial for Beginners #6 - Modules and require](https://www.youtube.com/watch?v=xHLd36QoS4k&ab_channel=TheNetNinja)
