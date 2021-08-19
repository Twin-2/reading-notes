# Class 12 Pre reading

[Back to menu](../README.md)

using SQL you can produce complex relations by combining the id's from multiple tables.

## Questions
NoSQL
1. What kind of data is a good fit for an SQL database?
- complex or hierarchical data
2. Give a real world example
- orders or product lists.
3. What kind of data is a good fit a NoSQL database?
- data that needs to be querries a lot.
4. Give a real world example.
- users
5. Which type of database is best for hierarchical data storage?
- SQL
6. Which type of database is best for scalability?
- MongoDB.

SQL
1. What does SQL stand for?
    - structured Query language
2. What is a realational database?
    - a database that works on certain assumptions to work with SQL.
3. What type of structure does a relational database work with?
    - tables
4. What is a ‘schema’?
    - which data can go in which field or the titles for the columns. so you must set the number of columns from the beginning and then it cannot go over that. 
5. What is a NoSQL database?
    - MongoDB is one example.
6. How does it work?
    - collections with documents inside. There is no schema, so each Document can have very different shapes.
7. What is inside of a Mongo database?
    - instead of tables there are collections and instead of schema's you have documents.
8. Which is more flexible - SQL or MongoDB? and why.
    - MongoDB because it doens't have schema's so the data layout can change. 
9. What is the disadvantage of a NoSQL database?
    - no relations. No schema so not every item has all the same data.

# Class 12 Lecture
Today marks the move into true full stack dev.

rather than use a cache for memory we are going to use MongoDB

REST => GET, POST, PUT, DELETE
- for server to client talk

CRUD is for server <-> DB talk
- Create (POST), Read (GET), Update (PUT), Delete (DELETE)
- most modern wbsites are CRUD.
    - FB, Instagram, WordPress, are. Discord/Slack are not


## Tools

MongoDB:
- Object based database
- non relational system

mongoose lets us to to MongoDB in javascript

methods:
- .save
- .find({}) or .findById
- .findByIdAndUpdate
- .findByIdAndDelete
- specific documentation: mongoose methods, 

## Mongo Shell
Access with 'mongo' command line
- show dbs -> use ___
- show collection
- 'use' will switch db
- db.(name).find().pretty() will print out the collection

## Backend with Mongo
Models:
- DB model is a blue print for how to store data and the shape of your data
- **also called a schema**

structure:
- pull in mongoose
- set a schema with new mongoose.Schema({})
    - this is where you set the structure of the data
    - you can make items required or not
    - using 'new' has implications
- export with mongoose.model(name, nameSchema)

conection to a DB:
- pull in mongoose
- mongoose.connect(URI to DB, options)
- create options
    - mongooseOptions = {fdlksdfaglkjaih}


## Things i want to know more about
the Query languages themselves that we use to access these data. 

where do we find the syntax for mongoose?

can you further extrapolate the structure of each item?