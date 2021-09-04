# Day 13 

CRUD is resource management
- database integration

REALTIME
- gaming for example

## Lecture - Rooms and Review

it is helpful to begin by getting everything connected then starting to make actions happen.

socket refers to the incoming connections or connecters to a given space. 
- a socket.emit will only respond to the single client that connected. 

setting up a room:
- on the namespace, set up a .on that has a socket.join(name) in it
- anyone that connects to that namespace can connect to that room by calling the emit of that .on()

### Messeging queue

process.argv = array of command line arguments
- this is an array of the words.
- the command needs to look like: node filename command

## Questions

How do we deploy with socket.io?

can two socket.io's talk to each other?

How does someone else join the room?

how do you get multiple vendors to only hear unique stuff for them? Shouldn't that happen in a name space or room? So how do you get a .on() or .emit to carry over to another name space or room?

how would we assign chores to specific children? 

Can we add new add more chores without disconnecting?

## Things I want to know more about

Platform development

OSI Model

# Assignment reading

Review, Research, and Discussion

1. What does it mean that web sockets are bidirectional? Why is this useful?
-communication can go both ways. This way a socket can both listen for and emit events. 
2. Does socket.io use HTTP? Why?
- socket.io is built on httpo but processes at the TCP level. This is for faster communication.
3. What happens when a client emits an event?
- it will trigger the event on the serveror in any ocrisponding rooms or namespaces. 
4. What happens when a server emits an event?
- the any client in the appropriate space that is listening for that event will respond.
5. What happens if a client “misses” an event?
- thanks to TCP the packet can be resent if there is data loss. If the event is truely not captured, then whatever chaining of events it would have caused would not happen.
6. How can we mitigate this?


Document the following Vocabulary Terms
- Socket: when a client connects to a server it becomes a socket on that server/namespace,room
- Web Socket: 
- Socket.io: a library of function to run web sockets.
- Client: any server that hooks up to the main server or hub.
- Server: the focau poiont of the events. 
- OSI Model: Open systems intercommunication model. It is the 7 layers of abstraction that the internet uses for communication between machines. 
- TCP Model: The 4th level of the OSI model. It is where data is packaged up to be sent back and forth. 
- TCP: transmition control protocol. This rules for computers to connect to the internet for communication. 
- UDP: user datagram protocol used for fast transmition of data when there isn't a concern for data loss. 
- Packets; the units that data is seperated into for transfer across the internet. 

Preview

1. Which 3 things had you heard about previously and now have better clarity on?
- TCP, OSI model. 
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
3. What are you most excited about trying to implement or see how it works?
- integration of socket.io into other api's.