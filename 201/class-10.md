# Reading 10
---

- JavaScript book, Ch. 10, “Error Handling & Debugging”

- review of weeks concepts

## Ch. 10, “Error Handling & Debugging”

---

- Everyone makes errors when writing JS code.
- Learn how to mitigate issues when writing
- Use console and dev tools
- common problems
- handling errors

### Execution Context

- Global Context
- Function Context
- Eval Context


### Variable Scope

- Global Scope
- Function Level Scope

### The Stack

- The JS interpreter processes one line of code at a time. When a statement needs data from another function, it stacks the new function on top of the current task.

### Debugging Workflow

1. Where is the problem? - look at relevant error message, check how far teh script is running, and type of error.

2. What exactly is the problem? - When you have set break points you can see if the variables around them have the values you would expect them to, break down the parts of code into smaller chuncks. Call functions to see if they are returning what you want.

### Setting Breakpoints

- You can pause the execution of a script one any line using break points.
- If you set multiple breakpoints, you can step through them one by one to see where values change and a problem might occur.

### Handling Exceptions

1. Try
2. Catch
3. Finally

` try {
  // Try to exectute this code
} catch (exception) {
  // if there is an exeption, run this code
} finally {
  // this always gets executed
}`

### Summary

- Dubugging is the process of finding errors. It involves the process of deduction.
- Console helps narrow down the area in which the error is located.
- Js has 7 different error types, each creates its own error object.


## Review of weeks concepts 
---

### Variable Scope 

- The location where you declare a variable will affect where it can be used. If you declare inside a function, it can onle be used within the function. This is known as the variables scope.

### What is an object?

- Objects group together a set of variables and functions to crate a model of something you would recognize from the real world. IN an object variables and functions take on new names.
- variables are properties
- functinos are methods


### Creating many objects using constructor notation.
- Sometimes you will want several objects to represent similar things. Object Constructors can use a function as a template for creating objects. 
- You create instances of the object using a constructor function.
- 'new' keyword
