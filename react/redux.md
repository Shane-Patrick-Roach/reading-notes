## React Redux 

React redux is the official React UI bindings layer for Redux. It lets your React components read data from a Redux store, and actions to the store to update state.

React-Redux is conceptually pretty simple. It subscribes to the Redux store, checks to see if the data your component wants has changed, and rerenders your component. 


## Standard UI Update Cycle

1. Create a store
2. Subscribe to updates
3. Inside the subscription callback: Get the current state store, extract the data needed by this piece of UI, and updaate the UI with data.
4. If necesarry, render the UI with inital State.
5. Respond to UI inputs by dispatching Redux actions.
