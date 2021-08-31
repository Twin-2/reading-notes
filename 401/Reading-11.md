# Class 11:L Events in Node.js

## Tools
socket.io - real time engine

TCP : one step down from HTTP

1st party modules

faker npm

## Lecture
OSI model: 
- the layers of abstraction of the internet
- at the base, it is wires transporting electricity

node.js **EventEmitter**
- this allows us to create out own events
- steps:
    - register: .on(word, callback Function)
    - fire: .emit(word)

### Events
require from the node module. no install needed.

.on creates and event
- we can assign any work to the event
- we can build any function to be called on the event

.emit fires an event
- we pass in the word form an evetn that we maede and emit connects to the .on event

you can require without needing a const and it pulls in the whole file. 

## Questions

Queue: how is next supposted to work?
- how do you itterate over a queue

Gina: can you explain the relationship thing with the tables?


where does pg fit into what we are doing with sequelize?

Brian, can we take some time to look at the sequelize docs?

does it matter where we set the interval?

'tell the driver' is that the emits and ons

## Things I want to know more about
OSI

TCP

first party node moduels

setInterval: over the course of given time, do function

## Reading assignment

Review, Research, and Discussion

1. Why is access control important?
- keeps content safe and allows for more complex applications
2. Describe an application that would need access control.
- a blog, any sort of social media platform, and company website where the owner would want to add, edit or delete content that the users can then go see.
3. What is a role used for?
- usually just reading content. 
4. Why is role based access control more scalable than discretionary or mandatory access control?
- i assume it's easier to have default user types. 

Document the following Vocabulary Terms
- Authorization: allowing acces to certain content
- Role Based Access Control: access granted to certain CRUD actions based on a user 'roll' 
- Capabilities: what we define those roles as

Skim the following materials in preparation for the upcoming lecture. Note the following as you browse the material, and be prepared to participate in discussions during lecture

