# Lecture 01

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

TDD - test driven development



## Questions

Is redux usable outside of React? - Yes.

do you need a way to stop the server? good idea but not necessary. In modern server testing it will stop in on it's own with the tools we will use. 

can we assign a variable to dotenv? Yes. but cleaner to just do it in one line

could we use a factory concept in the srver.js?