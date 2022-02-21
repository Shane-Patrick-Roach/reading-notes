# Inheritance and Interfaces, OOP continued.



## What is inheritance?
--- 

### Overview 
- A java class can inheit fields and methods from another class.
- Each class requires its own file, but only one class in a Java package needs a main() method.
- Child classes inherit the parent constructor by default, but its possible to modify the constructor using **super()** or override it completly.
- Javas OOP principle of polymorphisim means you can use a child class object like a member of its parent class, but also give it its own traits.
- You can overrid the parent class methods in the child class useing @Override keyword.
- Its possible to use objects of different classes that share a parent class together in an array or Arraylist.

### Super Classes

- The idea of inheritance is that objects in the realworld can be reduced to a generalized model than branched out into more detailed on well defining subclasses. 
- For example, think of a Bicycle. A bicycle can be further broken down into Mountain Bike, Road Bike, and Tandem Bike. Java allows you to do this by creating a sueprclass.
- All objects can have a superclass and unlimited amount of subclasses.
- Use keyword `extends` to create a subclass.

## What is an Interface?

---

- Objects define their interaction with the outside world through the methods they expose. 
- In its most common form an objects interface is a group of methods with empty bodies. An example of a bicycle interface could be changeGears(), pedal(), brake().
- Use `implements` keyword to attach the interface to the objects. The compiler will now require those methods.
- Overview - implementing interfaces allows classes to become more descriptive about the behavior it promises to provide. 


## Things I want to know more about?

---

### What is recursion?

- A function that calls itself.
- Think of Tom and the dragon story of only being able to analyze the first number in a list. Repeating until list is empty.
- Must always have a base case to know when the function should end.

## Resources/Citations

---

- [OOP Docs](https://docs.oracle.com/javase/tutorial/java/concepts/)
- [Interfaces and Inheritance](https://docs.oracle.com/javase/tutorial/java/IandI/index.html)
