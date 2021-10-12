# Class 16

## Lecture: AWS

AWS is great for scalability!

Elastic BeanStock: similar to Heroku/Netlify

- We can make 2 things: Environments and Applications.
- eb create: creates an environment
- eb init: creates an application

Express statis

- app.use(express.static('./public))
- used to set up static elements for view

## AWS Pit falls

## Tools

AWS SDK

- software development kit
- pull in different services to make instances of them.

AWS CLI

- used for global command line prompts

EB CLI

- allows us to directly upload to beanstock
- need to have an 'npm run start' command in the package json

## things I want to know more about

app.use(express.static('./public))

## Questions

Environment vs application?

- multiple of each.
- environments are things like stagging, QA, dev, and deploy
- you can plug multiple apps and each might need to be plugged into different environments.

## Review, Research, and Discussion

In your reading notes page for this class, provide answers to the following prompts. Cite any external sources

1. Describe the Web-Request-Response-Cycle

    - a client (could be a UI or a server) sends a request object to a server (could be the API for the server or another API). The server then does whatever it needs to with the request and sends back a response.
2. Explain what a “server” is, as it relates to the WRRC

    - a server is an API. It's job is to take in information from a source, process it, maybe modify it, maybe get more information from a 3rd party API, then send back a responce.
3. What does it mean to “deploy” an application?

    - deploying means to set up the API on a web page so that it won't be running on just your local machine and others can access it.
