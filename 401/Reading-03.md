# Pre Reading class 3
[Back to menu](../README.md)

Express Router
- increases modularization.
- the router can almost be thought of like a factory that we can set multiple times so we can have several sets of routs that are much easier to manage. 
    - ex: app.use('/app', router), app.use('/APIs', router)
    - now we have two sets of routes at .../app/... and .../APIs/...

## Questions
1. Name 3 real world use cases where you’d want to change the request with custom middleware
   1. Authenitcation
   2. to help integrate multiple systems with one UI
   3. restrict authorization
2. True or false: The route handler is middleware? True. From the reading it seems to at least act like middleware as it has a callbackfunction that is executed to modify the data. 
3. In what ways can a middleware function end the process and send data to the browser? Using next(). In express if anything is passed in as an argument to the next function then the path is sent to the error handler not the rest of the route path. 
4. At what point in the request lifecycle can you “inject” middleware? at the beginning, when the server gets it but before it processes it. 
5. What can cause express to error with “Request headers sent twice, cannot start a second response” 

## Terms
- Middleware: in expres middleware is code that modifies the request object before it is processed by the server. In general, it is code that runs between two events to modify data.
- Request Object: What is sent from the UI to the server.
- Response Object: what is sent from the server back tot the UI.
- Application Middleware: middleware that has a global scope and effects the entire server. an example is a function on a global route. 
- Routing Middleware: middleware that effects a specific route.
- Test Driven Development: the concept of beginning your development with creating tests and then building your code around those tests. 
- Behavioral Testing: 

## Preview

1. Which 3 things had you heard about previously and now have better clarity on?
    1. middleware
    2. Routes, sorta. this reading gave me some new thoughts and ideas about route structure.
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    ## **testing of middleware**
3. What are you most excited about trying to implement or see how it works?
    - More middleware!!! and this new route structure with the router!

# Lecture 3

the main purpose of the module.exports on the server is to make the server testable.  

we always want to mock the test for server and DB so we don't fill it with fake info

DB config
- examples of config files: yml, json,...
- create a script to run the config files
- sequelize(install globally) -> is like mongoose and sqlite3 -> is like Mongo
- models in sql are like schemas in mongo

Postgress is the 'dialect' used to hold our DB.

Models in sequelize
- .define sets up a table with that name
- defining types in the model you have to use the sequelize datatypes
- allowNull is like require

## Questions

are we using the new express version withthe router?

what docs are you getting it from?

update person: findByIdAndUpdate why not filtering?

postgres update: the examples in class do not line up with the examples in the link provided.


# Things I want to know more about

TDD - i do not feel that I understand it well enough to actually do it. 

3rd party middleware (morgan)

npm scripts

node environmental variables.

