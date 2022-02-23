# OOP Design

## Dont Repeat yourself
---

### What does it mean to not repeat yourself?

Principle of software design, in which you simplify your data and decrease redundancy by using abstractions or other daata normalization techniques.

### What is the rule of three?

When similar code is repeaated more than two times you should reduce the reduncdancy.

Duplication in code is a bad practice, that makes it harder to maintain. If someone new has to work with a redundanct code base, it will be very costly to make changes.

## MVP
---

### What is, "You arnt going to need it" principle?

A programmer should not add functinoailty until it is deemed absolutly neccesaary.

### What is MVP?

An MVP stands for Minimal Viable Product. This is a version of a product that implements just enough features to make it usable and testable bu early customers. So then you can take in feedback and make the desired changes.

#### Purposes

1. Be able to test a product hypothesis with minimal resources.
2. Accelerate learning.
3. Reduce wasted engineering hours.
4. Base for other products.
5. Start branding as soon as possible.



## Things I want to Know More About
---

### Whats an Abstract Class?

- An abstract class is a blueprint for subclasses that have the must have the properties and methods of the abstract class.
- You cannot include the body of a method in an abstract method, these must be defined in the subclasses.
- For example, an abstract ANIMAL class. Then all the subclasses would be specific animals like, Mammal, Bird, Reptile...

### Whats an Interface?

- A contract that you make with each class that uses the interface saying you must do this thing, but you have to say what it does.

### Whats the difference between abstract methods and interfaces?

- A class can have as many interfaces as you want.
- A class can only implement one abstract class.
- All Variables declared in an interface are `static` and `final`.


### What is a Call Stack?

- A call stack is a data structure that inplements the LIFO principle. (LAST IN FIRST OUT)
- Big O is constant time making them very useful for certain applications.



## Resources and Citations
---

[Rule of Three]('https://en.wikipedia.org/wiki/Rule_of_three_(computer_programming'))

[Abstract Classes]('https://www.youtube.com/watch?v=HvPlEJ3LHgE')

