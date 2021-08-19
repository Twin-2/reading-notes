
# Lecture 01

[Back to menu](../README.md)

CF vision - tech skills for a better life, for a better community, for a better world. 

CF mission- guide people from all backgrounds to change thier lives through fast-paced career focused education, to meet industry needs. 

> ## **Start thinking about your goals.**

## backend dev with Express

Git Actions
- CI and CD => continuous integration and deployment
- SQM => software quality management
- sits between deploy and repo
- other CI/CD systems: Travius CI, Cirlce CI...
- **set up first**
- yml is a config file

Impotant in a yml
- 'on: push/pull'
    - tell the CI when to run
- 'steps: '

Companies will have their own CI/CD pipielines

## Seting up a server
files needed: 
- index.js - entry point
- server.js -server
- _ _tests_ _  holds tests
- middleware file
- package json

## modules
- jest use to run tests
- supertest - in memory request system
- we modularize to allow testing. with server.js as the entry point if doesn't test.
 


REST - representational state transfer

## Middleware
code to take the 'req' and do something to it before passing it to thr route. 

you can use it to change the req object

include 'next' as a prop in the function

## Tests
assertions are methods that you run on your code to make sure it does what you want

use '.test.js' at the end of all files in your _ _tests_ _ file

descripe block is a method of jest
- describes the test suite (series of tests for a module)
- 'it' is a test
    - single or series of assertions
- 'expect' is used for each assertion

you **must** test things that work and things that do not work!


## Things i want to know more about 

TCP - event driven applications, real time applications

hooks in React

Context API

Redux - state management tool

TDD - test driven development. RGR => red green refactor



## Questions

Is redux usable outside of React? - Yes.

do you need a way to stop the server? good idea but not necessary. In modern server testing it will stop in on it's own with the tools we will use. 

can we assign a variable to dotenv? Yes. but cleaner to just do it in one line

could we use a factory concept in the srver.js?

1. Describe (in plain English) what Array.map() does
    - takes a group (array) of items and for each one it runs your function on them then creates a new group (array) of the output. 
2. Describe (in plain English) what Array.reduce() does
    - similar to array.map reduce looks at a group (array) and for each item will run a function on it. The difference is that rather than returning a new array, it can return the product of your function in any form or shape that you want.
3. Provide code snippets showing how to use superagent() to fetch data from a URL and log the result
    - answer for questions 3,4, and 5 is the [picture](https://www.npmjs.com/package/superagent)
4. With normal Promise .then() syntax
5. Again with async / await syntax


![superagent demo](https://user-images.githubusercontent.com/81482156/129644852-32ffa4cb-44e7-4a0b-a2f0-827ee5f22dbf.PNG)


6. Explain promises as though you were mentoring a Code 301 level student
    - a Promise is just that, a Promise, to give some data at a later point. When you use a promise, in order to 'cash-in' on that promise, you need to use the syntax '.then' to open the Promise as resolved or '.catch' to poen the Promise as rejected. 
7. Are all callback functions considered to be Asynchronous? Why or Why Not?
    - yes, in javascript. Since javascript is single threaded, a callback function goes to the call stack and then gets run after all the other code is finished working, essentially making it asynchronous. 
