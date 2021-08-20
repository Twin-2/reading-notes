# Pre Class 4

## Questions

1. Name 3 advantages to Test Driven Development
    - faster writing of the code itself
    - less bugs in development
    - cleaner code
2. In what case would you need to use beforeEach() or afterEach() in a test suite?
    - when you are dealing with a server and memory these will allow each test to be independent.
3. What is one downside of Test Driven Development
    - You have to fully understand the testing model before you can write the tests. It can also take longer.
4. What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?
    - From my understanding, ES6 classes are simpler to use and follow. 
5. Why REST?
- From https://www.freecodecamp.org/news/benefits-of-rest/
    >REST aims to make caching easier. Since the server is stateless and each request can be processed individually, GET requests should usually return the same response regardless of previous ones and the session.


Term
- functional programming: strict structure where data is immutable. Great for large databases. Often used for front end dev.
- object-oriented programming (OOP): programming based on objects. data is more secure and also more mutable. Often used with Backend dev.
- class: a new type of object schema for ES6 that makes object constuctors easier.
- super: allows all props to be passed to child classes.
- this: referes to the parent object.
- Test Driven Development (TDD)
- Jest: testing engine
- Continuous Integration (CI): the ability to run tests, and as long as they are passing continuously have your code be merged. 
- REST: the verbs used for HTTP requests.
- Data Model

1. Which 3 things had you heard about previously and now have better clarity on?
    - SQL databases and their relationships. 
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    - testing, sequlize DB, especially with testing.
3. What are you most excited about trying to implement or see how it works?
    - TDD!!!! I still really want to shift this way but I am still finding myself not fully understanding the tests, so it's really hard to write them first. 

# Lecture day 4
'lib' folder
- first party helper tools, like **collections**

index files are where we set up our DB

we create relationshipos with key words.
- hasMany(otherModel, {foriegnKey: customerId, sourceKey: id})
- belongsTo 

## Collections
useinc class convention we create a collection that we can then use as an extension of all other files which are classes.



## Questions

throw new Error vs next('error')

expected class extends

## Things I want to know more about

SQL language. 

Collections