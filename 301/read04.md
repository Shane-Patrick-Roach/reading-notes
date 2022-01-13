# Reading 04

## React Docs - Forms
--- 

### What is a ‘Controlled Component’?

- Then the React component that renders a form also controls what happens in that form on subsequent user input.
- An input form element whose value is controlled by React in this way is called a “controlled component”.
- Single source of truth in React

### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

React will always make the displayed value = this.state.value. Since the function handle runs on every keystroke, the displayed value will update as the user types.


### How do we target what the user is entering if we have an event handler on an input field?

using the following code

`
handleChange(event) {
    this.setState({value: event.target.value});
  }
`

then inside the label element
`

<input type="text" value={this.state.value} onChange={this.handleChange} />
`


## The Conditional (Ternary) Operator Explained
--- 

### Why would we use a ternary operator?

- to write one line of card instead of multiple
- to maximize big O


### Rewrite the following statement using a ternary statement:

`
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
`

to ternary

`
x === y ? 'true' : 'false;
`


--- 
## What I want to Know more about

- Practice using forms
- Practice using ternary 
- More practice with conditional rendering such as lab 3 but with forms


## References/Citations
- [React Docs - Forms](https://reactjs.org/docs/forms.html)
- [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff?gi=b4ae7a084ed5)
