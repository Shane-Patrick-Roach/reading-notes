# Stacks and Queues

## What is a Stack?
- A stack is a data structure that consists of nodes. Each node references the next node in the stack, but does not refernce its previous.
- Follows LIFO, first in last out, structure.
- Think of a stack of books.
- Really cool because when it is implemented correctly it is an O(1) operation.



## What is a queue?
- Very similar to Stacks but the opposite.
- Follows FILO, first in last out.
- Think of a line of people waiting forsomething.
- Really cool because when it is implemented correctly it is an O(1) operation.


## Things I want to know more about

### Generics

- Generics offer the ability to have one class and have many types. 

- Example if you have a printer class that takes in a value. But you sometime you want to pass in different types of data. Declaring it a generic class by useing a common signature of  `<T>`. 

- We have already used generics with somethings like an Array list. 

- When declaring a generic, you can also specify if it has a super class. Such as `<T extends Animal>` Also known as a **Bounded Generic**.

- This also works with methods. 

- You can use a wildcard `<?>` in which you can pass in any type.

## Resources/Citations

- [Stacks and Queues](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/stacks_and_queues.html)
