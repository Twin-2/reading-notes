# Class 6
[Back to menu](../README.md)

Bearer auth and basic auth. from scratch.

Today is basic auth -> sign up and sign in

Auth has not changed in 10 years. 

## WRRC review (time: up to 9:22)
Sign up
- when sign up, username and password are attatched to req.body
- save req.body to the DB as the user. 
- Just like other req and DB save but now we have to use middleware to encrypt the password

sign in
- req with US and PW -> encode as base64(US:PW) string
- they live on req.authorization @ 'Basic ______'
- take PW, un-encode, compair with DB password, if same then sign in. 

## BCrypt
salt: the amount of encryption that hashes something. 5 is a good standard. 

always encrypt passwords and credit card info

## Tools
BCrypt (windows bcrypt)
- hash and compare methods. 

Base-64 encoding and decoding
- will happen on the front end to have some low level security

pg
- to talk to an SQL DB

sequalize
- same ab pg

## Questions 

Middleare or hook (beforeCreate)? Why not both?!?!

wouldn't you not want to send back the hashed password or would that not matter?

when will we get into the 11 steps of auth? or is that just relating to 3rd party auth?

# Post-lecture 

## Questions

In your reading notes page for this class, provide answers to the following prompts. Cite any external sources

1. Explain what a “Singleton” is (in Computer Science terms)
- it is a class that can only be instanciated once.
2. Explain how the Singleton pattern can be used with Node 3. modules, specifically with classes
- if we have a class that we onle ont to initiate once and then add to that same isntance of the class without makin new ones, then a singleton is great.
3. If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?


Document the following Vocabulary Terms
- Router Middleware: middleware that is specific to a single route.
- Dynamic Module Loading: loading the program before the libraroes. Can help protect the library from unauthorized access and allow the program to choose between different libraries. 
- Singleton Pattern:it is a class that can only be instanciated once.
- CRUD -> REST Method Matches
- Mock Testing: creating a simulation of your routes on a virtual machine so that you do not actually interacto with your DB.
- Preview


Skim the following materials in preparation for the upcoming lecture. Note the following as you browse the material, and be prepared to participate in discussions during lecture

1. Which 3 things had you heard about previously and now have better clarity on?
- how bcrypt is better than other hashing prgrams and how it keeps your password safe. 
- Oauth was not designed for you to sign in, it is designed for 3rd party auth
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- data protection and encryption.
3. What are you most excited about trying to implement or see how it works?
- Oauth to compaire it to auth0
