# Class 6 Pre reading

### Node.js
[Node is](https://www.sitepoint.com/an-introduction-to-node-js/):
> JavaScript runtime built on Chrome’s V8 JavaScript engine.

The Chrome V8 engine
- it is what compiles JS down to machine code for your computer to read.
- Node, being built on this, can run on any computer to translate between JS and machine code.

Insatlling node
- you can use a version control to run multiple versions of Node.
- [Look Here](https://www.sitepoint.com/quick-tip-multiple-versions-node-nvm/) for more info on version control

Node
- you can use node to run JS directly in your command line. 
- Node supports ES6
- npm" Node Package Manager
  - npm i -g for global install
  - you can also install locally.
- 'node_modules' holds all libraries that are needed to run your program. 
  - npm install within the root folder will install all node_modules

Node and the Server
- node allows for higher performance and can help to stop site crashes by its single threaded, event driven nature
- node combines callbackf functions into server requests to keep a single thread going. 

**Node is best for apps that want some real-time interaction**

### Pair Programming
Pair programming is essentially: two programmers working on a project together

How does it work?
- two roles: the Driver and the Navigator
  - Driver: the one with hands on the keyboard.
  - [Navigator](https://www.codefellows.org/blog/6-reasons-for-pair-programming/) uses words to guide the Driver but doe snot directly touch the computer

Why do it?
- helps with learning a language through 4 methods:
   1. Listening
   2. Speaking
   3. Reading
   4. Writing

Reasons to use it:
1. Greater efficiency
    - may take longer but the quality is better saving time and money with bug fixes.
    - easier to catch errors as they are written than as a big
    - improves team skills
2. Engaged collaboration
    - easier to stay on task with an accoutability partner
    - encourages asking for help
3. Learning from your fellow students
    - yuo get to see how others think which will give you new ideas
4. Social skills
    - imporve your communication and other social skills by having to work with others.
5. Job interview rediness
    - many applications will involve pair programming
6. Work environment readiness
    - most work environments use pair programming so you might as well get used to it now!


## Questions
Node.js

1. What is node.js?
   - Node is a javascript runtime built onthe Chrome V8 engine.
2. In your own words, what is Chrome’s V8 JavaScript Engine?
    - The Chrom V8 engine is how chrome turns javascript into binary for your computer to read.
3. What does it mean that node is a JavaScript runtime?
   - It means that Node takes in javascript and outputs infor for your computer to run.
4. What is npm?
   - the Node Package Manager.
5. What version of node are you running on your machine?
   - v14.17.0
6. What version of npm are you running on your machine?
   - 7.19.1
7. What command would you type to install a library/package called ‘jshint’?    
    - for global install i would use 'npm i -g jshint'
8. What is node used for?
    Literally anything. But it is best suited for apps that want a real-time interaction.

Pair Programming
1. What are the 6 reasons for pair programming?
    - Greater efficiency, engaged collaboration, learning from your fellows, social skills, job interview readiness, work environment readiness.
2. In your experience, which of these reasons have you found most beneficial?
    - efficency and learning from others. I have already learned a lot of CSS which was my weakest skill coming into CF. I have also benefitted from being able to ask for help sooner and more regularly. If they don't know then i quickly turn to TA's.
3. How does pair programmng work?
    - Two people work together to produce code faster and more accurately through communication and collaboration. 


# Class 6 Lecture
We are going to talk about what the internet is ans how it works so that we can apply code to make things happen.

## What is the internet?
Client: request or give info
- not ALWAYS the front end. It could be your back end requesting info from another server
Server: serve or give info

CLient server architecture
- HTTP protocol: hypertext transfer protocol

Requests: an object with the following parts
- method: restful methods
  - Get, Post (save), Put (something you want to change), ot Delete
- body
  - mostly involves Post and Put.
  - 
- headers
  - like the package JSON
  - META info: authorization, keys, cookies, IP info...
  - Authorization and authentication

Response
- status: did this work or not
    - 200: that worked, 404: not found, 500: server error...
- Body: The data. The thing yuo get back.
- Header: more meta info

API: aplication programming interface
- and interface that helps you program
- **web** API's help us get data on the internet

HTTP status codea can be found at http.cat

Tody we come into asyncronus programminng
- 

Promise is an object with 3 states
- resoveled = .then
- rejected = .catch
- pending = while waiting

axios is a request tools

superagent is Brian's favorite

## Building a front end that can talk to a backend
In our react app we need state that we will modify to input data to send to the server.

NPM i axios

create a method of our class that actually runs the request

Every API structures the request different

anatomy of a URL (look it up)
- '?' seperate query strings or key value pairs

process.env = in React these are dev specific and hiden from others.

you often have to install dotenv  




## Things I want to know more about
API's.

The concept of a server. There is so much on the back end that is all theoredical and I can't see so it is hard for me to understand. I am a very visual learner so I think this topic will be hard for me. 

Where is the Server? The cloud?

Is a query the same as the req/res cyyle that we talk about?
- very similar but it is different