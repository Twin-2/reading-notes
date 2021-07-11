# Reading Notes
Code Fellows reading notes

## Code 301 - *Intermediate Software Development*
> Nothing worth doing is ever easy ~Theadore Roosevelt

### Day 1

#### Pre reading on React
immutability- not changing the original values of objects/arrays, instead creating a new array with the new values.
  this creats better usability.
  
components = large building blocks of code.

state = instance of each component.

class =

call variables in JSX by using {}. You can put any JS in {}.

if an element is empty, use '/' to close it right away. Or you can have children inside it. Ex:

> const element = "\<img src={user.avatarUrl} />;"
> const element = (\<div> \<h1>Hello!</h1> \<h2>Good to see you here.</h2> \</div>);

elements are the smallest compnent of react. think of them like objects.

**Think about how the UI should look at any one poipnt, not how you want to change it.**

The simplest form of a component is a function.

**All react compnets must act like pure functions with respect to their porps.**

Changing a react function to a react class:
1. Create an ES6 class, with the same name, that extends React.Component.
2. Add a single empty method to it called render().
3. Move the body of the function into the render() method.
4. Replace props with this.props in the render() body.
5. Delete the remaining empty function declaration.

- Mounting and unmounting: the first rendering to the DOM is mounting and taking it off the DOM is unmounting.
  - componentDidMount(), componentWillUnmount().

### React Handling Events

Event listeners are typed in camel case in JSX

It is important to "bind" this in callback function so that this is not undefined. Use this._____.bind

### Lists and Keys

Put the keps in the map() function.

### Thinking in React

When building apps in react, start by building a **static** model. then add interactibility later. 
  - Do not use state for the static model, use only props instead

When building large products, start at the bottom.

When building small projects, start at the top.

Strategy for identifying where state should go:
- Identify every component that renders something based on that state.
- Find a common owner component (a single component above all the components that need the state in the hierarchy).
- Either the common owner or another component higher up in the hierarchy should own the state.
- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.









## Things I want to know more about
syntax and structure of react compnents. I feel that I am missing something on the syntax. I don't know how to identify what is a keywork.
Which elements are the props? Is it text after render?
Do all components extend React.component?
