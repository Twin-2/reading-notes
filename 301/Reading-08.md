# Class 8 Pre reading

All API's need to consisder 2 factors:
- Platform independace from a specific client
- Service evolution

RESTful API's
- designed around resources
    - a resources is any object or data that can be access by the client
- each resource has an **identifyer** or URI
- clients interact with a server by exchanging representations of resources
- REST API's are stateless.

URI's shouldn't get more complicated than collection/item/collection



## Questions

1. What does REST stand for?
    - Representational State Transfer
2. REST APIs are designed around a ____.
    - resources
3. What is an identifer of a resource? Give an example.
    - a URI.  example 'http://localhost:3000'
4. What are the most common HTTP verbs?
    - get, put, post, delete, patch
5. What should the URIs be based on?
    - nouns
6. Give an example of a good URI.
    - collection/item/collection
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
    - It would ba an API that exposes a large number of small resources. This uses mutliple requests and slow down your web page. 
8. What status code does a successful GET request return?
    - 200
9. What status code does an unsuccessful GET request return?
    - 404
10. What status code does a successful POST request return?
    - 201
11. What status code does a successful DELETE request return?
    - 204

# Class 8 lecture

dotenv holds and accesses project specific files


You will need to use axios on the backend to make requests to any other 3rd party 

We can use function declarations ouside the 'app.get' to rename the (req,res)

It's better to aggragate at the server not the client. 

the last route in your server (for now) will handle errors
- app.get('*', (req,res) => {res.status(404).send('not found')})

short cicuiting: if somethings exists then continue
- use && to run a chunk of code as long as the first part is true 



## Things i want to know more about
When I'm usinga  web page, what are new webpages and what are RESTful API responses?

How do you find and access all those other API's and databases? is there documentation out there (where?) that i can look at to figure out the end points of the routes?