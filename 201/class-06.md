# Class 6 Reading

**Readings**

Understanding the problem domain is the hardest part of programming

What’s the difference between primitive values and object references in JavaScript?

From the Duckett JS book:

Chapter 3: “Object Literals” (pp.100-105)
Chapter 5: “Document Object Model” (pp.183-242)

## Understanding the problem domain is the hardest part of programming

---

- The problem domain is typically the hardest part about progamming.

If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

1. Make the problem domain easier
2. Get better at understanding the problem domain

## What’s the difference between primitive values and object references in JavaScript?
---

JavaScript currently supports eight different data types. This includes seven primitive value types and objects. Here’s the full list.

### Value types and objects of Javascript
1. Boolean
2. Null
3. Undefined
4. Number
5. BigInt
6. String
7. Symbol
8. Objects

### Mutable data types

-Arrays are mutable, meaning you can alter them directly.

### Immutable data types

- example, a string is immutable.
- If you need to get around this constraint you have to create a new string from the old one and reassign the word variable with that new value:

## Summary

- Many common data types such as an array, functions, and dates are object references under the hood. 
- Primitive values are immutable — they cannot be changed after being created. Object references, however, are mutable and can be changed.
- Developing a strong grasp of primitive values, object references, and mutability is a critical step in progressing past the beginner stages of JavaScript programming.


## Chapter 3: “Object Literals” (pp.100-105)

### What is an Object?

- Objects group together a set of variables and functions to create a model of something you would recognize from the real world. In an object, variables and functions take on new names. 
- In an object, variables become known as **properties**, and functions become known as a **method**

Literal Notation is the easiest and most popular way to create objects.(There are several ways to create objects).

## Chapter 5: “Document Object Model” (pp.183-242)

---

The document object model specifies how browsers should create a model of an html page and how JS can access and update the contents of the page while it is in the browser window.

### What is a DOM tree?

- As a browser loads a web page, it creates a model of that page. The model is called a dom tree, and it is stored in the browsers memory. It consists of four main types of modes.

1. Document node
2. Element nodes
3. Attribute node
4. Text Nodes

### What is a node?

- Each node is an object with methods and properties. Scripts access and update this DOM tree. Any changes are reflected in the browser.

### Accessing Elements

- DOM queries may return on element, or they may return a NodeList, which is a collection of nodes.

### Traversing the DOM

When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM.

- Traversing the DOM can be difficult because browsers add a text node whenever they come accross whitespace between elements.


### Attribute Nodes

- Once you have an element node, you can use other properties and methods on that element node to access and change its attributes.

### **Summary**

1. The browser represents the page using a DOM tree.
2. You can select elemnt nodes by their id or class attributes, by the tag name, or using CSS selector syntax
3. Whenever a DOM query can return more than one node, it will always return a NodeList.
4. An element node can contain multiple text nodes and child elements that are siblings of each other.
5. Chrome offers tools for viewing the DOM tree
6. DOM = ***Document Object Model***


