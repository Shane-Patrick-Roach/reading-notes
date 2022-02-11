# Introduction to Java



## Java is a object oriented language (OOP).
- Java objects are paart of so-called "Java classes"
- in java, every line of codde that can actually run needs to be inside a class. 


## Some concepts
- Java programs have atleast one class and one method();
- Java comments add helpful notes to readers
- Java is a compiled language => compiling catches mistakes in our code. Compilers transform code into an executable class.


### Primitive Data types in Java
- int, boolean, and double.
- ints hold positive numbers, negative numbers, and zero. They do not store fractions or numbers with decimals in them.
- The double primitive data type can help. double can hold decimals as well as very large and very small numbers.



### Functions

`
public class Main {
    public static void foo() {
        // Do something here
    }
}
`
- **static** means this method belongs to the class Main and not to a specific instance of Main. Which means we can call the method from a different class like that Main.foo().
- **void** means this method doesn't return a value. Methods can return a single value in Java and it has to be defined in the method declaration. However, you can use return by itself to exit the method.
