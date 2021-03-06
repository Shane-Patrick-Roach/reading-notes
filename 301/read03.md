# Reading 03


## React Docs - lists and keys
--- 

### What does .map() return?

.map returns a new array from the input array and does something to it. 

### If I want to loop through an array and display each value in JSX, how do I do that in React?


- You would create a new arrary using .map and create a list item for each element in the array.
- Then you would include each list item within a ul and render it to the DOM.
- usually you would render lists inside a component.


### Each list item needs a unique ____.

Each list item needs a unique key.


### What is the purpose of a key?

- A **Key** is a special string attribute you need to include when creating lists of elements.
- Keys help React identify which items have changed, added or removed.
- Keys should be given to the elements inside the array to give the elements a stable identity

## The Spread Operator
--- 

### What is the spread operator?
The spread syntax "spreads" the array into seperate arguments

### List 4 things that the spread operator can do.
- Copying an array
- Concatenating or combing arrays
- Using Math functions
- Adding an item to a list
- Adding to state in React
- Combinging Objects

### Give an example of using the spread operator to combine two arrays.

```
[...["ððððĪŠð"]] // Array [ "ððððĪŠð" ]
[..."ððððððĨ°ððĪĐ!"] // Array(9) [ "ð", "ð", "ð", "ð", "ð", "ðĨ°", "ð", "ðĪĐ", "!" ] 

const hello = {hello: "ððððĪŠð"}
const world = {world: "ððððððĨ°ððĪĐ!"}

const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "ððððĪŠð", world: "ððððððĨ°ððĪĐ!" }
```


### Give an example of using the spread operator to add a new item to an array.

``` 
const fewFruit = ['ð','ð','ð']
const fewMoreFruit = ['ð', 'ð', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "ð", "ð", "ð", "ð", "ð" ]

```

### Give an example of using the spread operator to combine two objects into one.

```
const objectOne = {hello: "ðĪŠ"}
const objectTwo = {world: "ðŧ"}
const objectThree = {...objectOne, ...objectTwo, laugh: "ð"}
console.log(objectThree) // Object { hello: "ðĪŠ", world: "ðŧ", laugh: "ð" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("ð".repeat(5))}}
objectFour.laugh() // ððððð
```



## What I want to Know more about

- I want to review more of the concepts that we have gone over this week. 
- What is a component? Compenents let you split the UI into independent reusable pieces, and think about eaach piece in isolation. Conceputally, compnents are like JS functions. The accept inputs(props) and return React elements desicribing how they should appear on screen




### In the video, what is the first step that the developer does to pass functions between components?

He adds a new function to pass an object and knows which person to increment when the button is clicked.

### In your own words, what does the increment function do?

creates a new array based on the people. If a person is clicked than it updats the counter. 


### How can you pass a method from a parent component into a child component?

You invoke it within the declared method.

### How does the child component invoke a method that was passed to it from a parent component?

You add to the child object with a .this inside the object creator




## References/Citations

1. https://reactjs.org/docs/lists-and-keys.html
2. https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab
