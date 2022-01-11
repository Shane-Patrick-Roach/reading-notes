# Read 02 - Introduction to React and Components
---

sources of info: 
- [React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)


## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

the render potentiall happens before the componentDidMount

## What is the very first thing to happen in the lifecycle of React?

- the Mounting phase occurs
- when compnent is created and inserted into the DOM 

## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

1. Constructor
2. render
3. react updates
4. componentdidmount
5. componentwill unmount

## What does componentDidMount do?

- This method is invoked after a component is mounted. IF you need to load anything using a network request or initialize the DOM, it should go here. 
- Good for setting up subscriptions




## What types of things can you pass in the props?

You pass initial information such as a counter start inside of the props. Props are like a function in which you want the application to initially render too. 

## What is the big difference between props and state?

State is used when you need to keep track of something the user has done. Something that is dynamic. 

## When do we re-render our application?

Everytime the state has changed. 


## What are some examples of things that we could store in state?

- a value within a form
- a counter


## Things I want to know more about

- I want to learn more about how to incorporate state into your react applications 




## Cited Sources

- https://www.youtube.com/watch?v=IYvD9oBCuJI&ab_channel=WebDevSimplified
- https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093
- https://react-bootstrap.github.io/
