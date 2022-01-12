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
[...["😋😛😜🤪😝"]] // Array [ "😋😛😜🤪😝" ]
[..."🙂🙃😉😊😇🥰😍🤩!"] // Array(9) [ "🙂", "🙃", "😉", "😊", "😇", "🥰", "😍", "🤩", "!" ] 

const hello = {hello: "😋😛😜🤪😝"}
const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }
```


### Give an example of using the spread operator to add a new item to an array.

``` 
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

```

### Give an example of using the spread operator to combine two objects into one.

```
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂
```



## What I want to Know more about

- I want to review more of the concepts that we have gone over this week. 
- What is a component? Compenents let you split the UI into independent reusable pieces, and think about eaach piece in isolation. Conceputally, compnents are like JS functions. The accept inputs(props) and return React elements desicribing how they should appear on screen


## References/Citations

1. https://reactjs.org/docs/lists-and-keys.html
2. https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab
