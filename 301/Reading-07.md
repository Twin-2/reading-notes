# class 7 Pre reading

I was unable to access the first reading article due to not having a subscription to the NYT. The article is moved and no longer free to access.

Two computer can talk to each other easily. Multiple can even talk easily if all on the same server. But HTTP becomes a lot more helpful once you have a lot of computers on a lot of servers talking to each other. 

URL's are esentiall requests for direction and/or permission.

# Class 7 lecture
the front end is a consumer of the backend. The backend is a provider of info. 

What are other tools to talk with the backend?

A server needs to: capture a req, build a res, send res to client.
    - servers are not built based on a front end. 
    - a request needs to match the backend capture.

Server Model:
    - paper notes

Axios is a tool to make requests.

the server can be completely seperate from the client. **You do not need to have the front built before the back**

## Tools

node.js:
    - not ousing a browser.
    - REPL: read evaluate print Loop

EXPRESS.JS
    - gives us access to a bunch of guides

API vs web server
    - web servers give out data
    - API sends out infor that anothe client can use to program.
    - Our API can send a request to another API to get data to send back to our front end

Curl- comand line URL request

Postman: tool for making requests to a server
    - used for testing, making sure it can work.

Swagger inspector: tool for making requests to backend

in a URL the ? denotes a **query string**, which are key value pairs.
    - use req.query.___ name of the query key in the URL
    - req.query returns the whole query **object**
    

## Questions

1. Who is Roy Fielding?
    - The man who invented the first web server.
2. Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?
    - because of the architecture of the HTTP and the language of the url.
3. What is the HTTP protocol that Fielding and his friends created?
    - it is the language or interpritatio nof words that computers can use to talk to each other in a similar language. 
4. What does a GET do?
    - retrieves info from a location
5. What does a POST do?
    - adds info to a location
6. What does PUT do?
    - deletes or removes info from a location.
7. What does PATCH do?
    - a partial update of info.


## things I want to know more about.