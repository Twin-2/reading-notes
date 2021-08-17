# Pre reading Class 2

NPM: think of it like a huge GameStop for devs. If you want a tool, it's probably already out there. 

TDD- test driven development. The process of first building a test, then writing the code. 
- this reminds me of the first shift to server first development. 
- make sure to run tests **frequently**
- 

## Questions
1. What’s the difference between PUT and PATCH?
    - Put replaces the original data point with the new data, PATCH only modifies poart of that datapoint. 
2. Provide links to 3 services or tools that allow you to “mock” an API for development like json-server
    -Posatman, Mirage, OpenAPI
3. Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?
    - get: Swagger-> 404 APIDoc-> 404
    - post 204
    - put 405
    - delete 204
4. Compare and contrast SOAP and ReST

1. Which 3 things had you heard about previously and now have better clarity on?
    - CI/CD, TDD. 
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    - HTTP requists and their appropriate errors. 
3. What are you most excited about trying to implement or see how it works?
    - TDD. I see real potential here to improve my code development to write cleaner code faster.

## Terms

Web Server - a server, or backend, that is able to comunicate with the web. Uses restful verbs to communicate. 

Express - a web framework for Node.js. 

Routing - directing users to different information on a server which is then sent back to the UI. 

WRRC - web requesr response cycle. 