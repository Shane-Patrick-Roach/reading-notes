# Reading 10




## Understanding the JavaScript Call Stack
---


### What is a ‘call’?
-The call stack is primarily used for function invocation (call)
- The call stack is single, functions exectution can only be done one at a time.
- Call stack is **synchronous**
- What is a call stack? a call stack is a data structure that uses LIFO.

### How many ‘calls’ can happen at once?
- Once call at a time.

### What does LIFO mean?

- ****(LIFO)=Last in First out**** principle to temporily store and manage function invocation (call).


### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

`
function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction();
`

- The output would then be 
1. Hello from firstFunction
2. The end from secondFunction


### What causes a Stack Overflow?

-  A stack overflow occurs when there is a recursive function (a function that calls itself)
- The browser will throw a (maximum call size exceeded) Which means a stack overflow.

## JavaScript error messages

---

### What is a ‘refrence error’?

- This error occurs when you try to use a variable that is not declared.

### What is a ‘syntax error’?

- This occurs when you have something that caannot be parsed in terms of syntax.
- Example - try to parse an invalid object using JSON.parse


### What is a ‘range error’?

- This will occur when you try to manipulate an object with some kind of length and give it an invalid length.


### What is a ‘type error’?

- This occurs when you the typrs of data you are trying to use or access are incompatible. 
- Like trying to accdess a property in an undfined type of variable.


### What is a breakpoint?

- A method of debigging JS code. Something like a console log or debugger statement can be used to see where the error is occuring in the lifecycle. 


### What does the word ‘debugger’ do in your code?

- the debugger statement invokes any availble debugging functionality. Such as setting a breakpoint. 


## Things I want to Know more about

---

- What is temporary Storage within a data structure?
- More on Try...catch = statement marks a block of statements to try and specifies a response should an exception be thrown.


## References/Citations
---
- [Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/)
- [JavaScript error messages && debugging](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)
