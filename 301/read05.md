# Reading 05





## React Docs - Thinking in React
---

### What is the single responsibility principle and how does it apply to components?

- A component sould ideaally do only one thing.
- if it keeps growing, break it down into small componments

### What does it mean to build a ‘static’ version of your application?

- a static version of your app uses props and no state at all. State is for interactivity.

### Once you have a static application, what do you need to add?

- Use state to add UI interactivity with your underlying data model.

### What are the three questions you can ask to determine if something is state?

1. is it passed in from a parent via props? If so, it proably isnt state.
2. Does it remain unchanged over time? If so, it probably isnt state.
3. Can you compute it baased on any other state or props in you component? If so, it isnt state.

### How can you identify where state needs to live?

- identify every compoent that renders something based on that state.
- find a common owner component
- either the common owner or another component higher up in the hierarchy should own the state.
- if you cant find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewher in the hierarchy above the common owner component.


## Higher-Order Functions

---

### What is a “higher-order function”?

- Functions that operate on other functions, either by taking them as arguments or by returning them ar called higher order functions.
- HOF allow us to abstract over actions, not just values.

### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

`
function greaterThan(n) {
  return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true
`


- returning if a number is greater than the number of n and returning a boolean.

### Explain how either map or reduce operates, with regards to higher-order functions.

- The **map** method transforms an array by applying a function to all of its elements and building a new array from the returned values. 
- The new array will have the same length as the input array, but its content will ahve been mapped to anew form by the function. 
- This works the same with **reduce** method in terms of higher order functions. 


## Things I want to know more about 

- practice using reduce method.
- practice conceptually with breaking down data into different compents to be used in a react application. 
- Where do we clarify state for each component?


## References/Citations
- [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
- [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)
