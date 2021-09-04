# Class 12

## Lecture

### Socket IO
socket lives on a port 
. but every thing happens at TCP

>Socket.IO is a JavaScript library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers. It has two parts: a client-side library that runs in the browser, and a server-side library for Node.js. Both components have a nearly identical API.

Name space:
- the large group that holds a lot of rooms
- io.of('/name') =  creates a new name space
- within the name space, you can .emit back to that name space or to ().emit back to the specific client

Room:
- can hold several clients
- can also be thought of as the different slack channels. 

socket.io-client: allow for main to connect with clients
- not a UI!!!


## Questions
would it want to connect to the global as well as the name space?

what is the difference between socket.on, namespace.on, and io.on?

## Things I want to know more about

web sockets

Net node module

# Assignment Questions
Review, Research, and Discussion

1. What is the benefit of transforming data into packets?
- easier to transport, faster to transport. If something goes wrong not everytihng is lost.
2. UDP is often refereed to as a connectionless protocol. Why is this?
- it doesnt require a 3 way handshake like TCP.
3. Can a socket server application have multiple socket connections?
- yes.
4. Can a socket connection application be connected to multiple socket servers?
- no
5. Can an application be both a socket server and a socket connection?
- Yes.

Document the following Vocabulary Terms
- Observer Pattern
- Listener: in the case of socket.io a listener is the .on() method. The same method is used in Node's EventEmmitter.
- Event Handler: For socket.io it is the method .emit(). This is where the method actually get called, or handled. 
- Event Driven Programming: building a program around triggering events. 
- Event Loop
- Event Queue: events that are added to the queue to be fired next.
- Call Stack: where functions are called on the v8 javascript engine. 
- Emit/Raise/Trigger
- Subscribe:
- database

Preview

1. Which 3 things had you heard about previously and now have better clarity on?
- OSI and TCP
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
3. What are you most excited about trying to implement or see how it works?
- implementation of socket into an api.
