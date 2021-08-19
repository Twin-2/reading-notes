
[Back to menu](../README.md)

# Warm up with CSS
CSS: use 'vw' for sizing, especially with text.
- 'display-inline block' for lining things up.
- use Flex-box for structuring.

# React state and Props

## Create-react-app command
- create react app is a starting point for scaffolding
- the most important file in node.js is 'package.json'
  - hold dependancies; needed files for the program to run.
  - each itme would need to be individually downloaded if not running create-react-app
- node modules
  - everything gets installed into node_modules
  - each module that you install has it's own modules that needed to be installed... all that goes into nde_modules
  - running 'npm i' looks in 'package.json' and installs all the node_modules
## React

**React is not the thing you put on the internet**.

React uses JSX to create HTML and JS that is put on the internet.

Public directory
- react is a 'single page application aarcitecture' a SPA architecture
  - **there is only 1 index.html**
  - showing a 'new page' just shows a new part of the code
  - the page is only loaded once allowing it to be much faster

Src file
- css files
  - has a tool that allows you to use css

**you do not need to 'import react' if you are not using classes**
**react only reloads state and props areas**

Components with state and props  
- use 'constructor(props){ super(props;)}'
  - super(prop) allows for adding state
  - always use this to ad props and state
- state
  - every component **of the same name** has it's own state
  - state is an internal data management for this component
  - state is like an object that we can add properties to
    - this.setState({'what state': 'how you want to update state'}
    - set state creates a 'new state' that react holds in memory. It does not update the original state which you should never do. 
  - you do not need to use () to call a function in react
- props
  - props is an immutabel structure that allows us to pass info into a component. (time stamp 10:43)
  - pass props when the compnent is called. '\<Child name ="" />'

Bootstrap time stamp 11:30
- frontend css framework
- to use bootstrap you need to 'npm i bootstrap' and 'npm i react-boostrap'
- you also need core bootstrap library
- 'react-bootstrap ' is components
- to import from react-boostrap us {} around the name.
- to use bootstrap in any component you need to import the react-bootstrap **and** the bootstrap file 




# Command lines/specific code lines
  - npm i
  - create-react-app
  - npm run build: 'build' an HTML index file that can be put online.
  - touch to add a new file

