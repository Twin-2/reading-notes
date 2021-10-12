# Lecture

## Action

Just an object literal

- type: string
- payload: any data
- sometimes we might just have type without payload (get)

### Action creator

a function that returns an action

actions are **dispatched** to reducers

## Reducer

a pure function with a switch case

- switch cases for each action TYpE

evaluates each action type and returns a new state based on the action.

## Store

single source of truth

holds all state

has memory kinda like git history

## Flow

action is called by reducer, which stores to store

## React-redux

Provider component with prop of store

## Set up

npm i redux, react-redux, redux-devtools-extension

We'll need an index file to set up the store and configure redux

**import composeWithDevTools from redux-devtools-extensions**

mapStateToProps function

- allows us to have props that are the different aspects of state.

## Things I want to know more about

curried functions

**thunk**

## Questions

What are our categories and products?

How should the file structure for redux break out?

map dispatch to props
