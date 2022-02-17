# OOP

## Java Objects and classes in Object Oriented Programming

---

### What is an Object?

- An object is a software bundle of related state and behavior.
- Real world objects share two characteristics, they have stat and behavior.
- Consider modularity = The source code for an object can be written and maintained independently of the source code for other objects
- information hiding = By interacting only with an objects methods, the details of its internal implementation remain hidden from the outside world
- Code - reuse = If an object already exists, you can use that object in your program.
- Plugabilty and debugging ease = If a particular object turns out to be problematic, you can simply remove if from your application and plug in a different object as its replacement.

### What is a class?

- In the real world you will often find many objects of the same kind. 
- In object oriented programming, we say that your object is an instance of the class of objects known as what ever the thing is. 
- A class is basically a blueprint from which individual objects can be made.

### How do Decimals work?

- Every digit in a decimal number has a position, and the decimal point helps us to know which position is which.

### What is a base?

- The decimal Number System is also called "Base 10", because it is based on the number 10.

### What is are binary Numbers?

- binary numbers are just "base 2" instead of "base 10". so you start counting at 0, then 1, then you run out of digits.

## Things I want to know more about
---

### What is an absolute and relative path in the directory?

- An absolute path contains the full path from the root of the file system down to the file or directory it points to. 
- A relative path contains the path to the file or directory relative to some other path.

- A relative path is a path that points from one path (the base path) to a directory or file. The full path (the absolute path) of a relative path is derived by combining the base path with the relative path.

#### Example Relaative Path
`
Path projects = Paths.get("d:\\data", "projects");

Path file     = Paths.get("d:\\data", "projects\\a-project\\myfile.txt");
`

### What is a Hashmap?
- Is a part of Javas collection
- It stores data in (Key,Value) pairs, and you can access them by an index of another type.
- One object is used as a key (index) to another object(value)

#### Useful Methods for Hashmaps

- size()
- clear()
- remove()
- get()
- keySet() and values() to get either keys or values of the map.

## References and Citations
---

1. [Object Docs](https://docs.oracle.com/javase/tutorial/java/concepts/)
2. [Class Docs](https://docs.oracle.com/javase/tutorial/java/javaOO/classes.html)
3. [Binary, Hex and decimal number](mathsisfun.com/binary-decimal-hexadecimal.html)
4. [Resource for paths](http://tutorials.jenkov.com/java-nio/path.html#:~:text=An%20absolute%20path%20contains%20the,relative%20to%20some%20other%20path.)



