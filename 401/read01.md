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



## Java programming variables

### Instance variables (Non Static Fields)

- Non static fields are also known as instance variables because their values are unqiue to each instance of a class.

### Class variables (Static Fields)

- This tells the compiler that there is exactly one copy of this variable in existance, regardless of how many times that class has been instantiated.
- Key word `final` could be added to indicate that the number never changes.

### Local variables

- the syntax for declaring a local variable is similar to declaring a field.
- not accesable to the rest of the class.

### Parameters

- the `args` variable.
- always classified as "variables" not "fields"



## What is an Expression?

- A construct of made up variables, operators, and method invocations.
- Evaluate to a single value.


## What is a statement?

- Statements are roughly equivalant to sentences in natural languages. 
- Forms a complete unit of execution.

## Blocks

- A block is a group of zero or more statements between balanced braces and can be used anywhere a single statement is allowed.

## Control Flow

- Statements inside your source file are generally executed from top to bottom, in order they appear.
- Control flow statements break up the flow of execution by employing decision making, looping, and branching, enabling your program to conditionally execute particular blocks of code.

## What does it mean to compile code?

- short answer... computers basically understand everything in terms of binary 1's or 0's. Since humans dont want to be writing code that way, we made higher order landguages for humands to more easuly understand such as Java or C#. 
- But after the humans write the code we basically have to tranlate back to a language that the computers can understand.
- Just because code compiles does not mean it works. Its like how 3+4 <5 that has the right form, but is false. 


## Things I want to know more about

- What are the big differences between java and javascript?
- Will C# eventually overtake Java as it accumulates more human experience?


## Recources and Documentation

1. [Java Docs](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/index.html)
2. [Good Reddit Thread on Compiling](https://www.reddit.com/r/explainlikeimfive/comments/233dq5/eli5_what_does_it_mean_to_compile_code/)
3. [Java Spreadsheet](https://www.dummies.com/article/technology/programming-web-design/java/java-for-dummies-cheat-sheet-207676)
