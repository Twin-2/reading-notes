# Class 5 Pre reading

[Back to menu](../README.md)

Always identify the single source of truth. 

Use a white board aproach and follow the logic of the data and structure flow

**Build a static model first**

# CLass 5 lecture
We are using React to build components that manipulate our UI. 

Up to now we have only been front end.

The last week has been to understand the **basic** building of react components. 

## Code Review
Day 1 
- components and framework
- we used create-react-app
  - scafold tool
- comp structure, class convention, and arrow functions. 
- JSON = javascript object notation
- MERN = Mondo DB, Express, React, Node.js
   - LAMP = Linix, apache, mysqn, php (old way to do it)

Day 2
- component architecture

Day 3
- State is mutable, props is immutable
- 


## Lab
Argon library

React uses rounting to "move pages"

Route is a react comp. It has a path and comp that will be rendered.

This lab is about jumping into an already built react app.


## Things I want to know more about
Can/How do you pass straight data as a prop that is not a state?
If i loop through some data to create a new array, how would i pass that new array to a child? It wouldn't need stat would it?
Jessica's question: can it access each idividual state? or would we need each setstate?


## Questions

1. How would you break a mock into a component heirarchy?
   - literally drawing blocks around each part to turn them into components.
2. What is the single responsibility principle and how does it apply to components?
   - each component should do one 'thing' if is stars growing break it up.
3. What does it mean to build a ‘static’ version of your application?
   - make all the components and use hard coded data. no state.
4. Once you have a static application, what do you need to add?
   - State! and you need to decide where is should go. 
5. What are the three questions you can ask to determine if something is state?
   - [From the reading](https://reactjs.org/docs/thinking-in-react.html)
   > 1. Is it passed in from a parent via props? If so, it probably isn’t state.
   > 2. Does it remain unchanged over time? If so, it probably isn’t state.
   > 3. Can you compute it based on any other state or props in your component? If so, it isn’t state.
6. How can you identify where state needs to live?
   - [For each piece of state in your application:](https://reactjs.org/docs/thinking-in-react.html)
    >Identify every component that renders something based on that state.
    >Find a common owner component (a single component above all the components that need the state in the hierarchy).
    >Either the common owner or another component higher up in the hierarchy should own the state.
    >If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state >and add it somewhere in the hierarchy above the common owner component.


