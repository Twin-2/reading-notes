# Class 13 pre reading

## Questions

1. In your own words, describe what each group of status code represents:
- 100’s = info about the request and what will be tried to fix it
- 200’s = it worked!
- 300’s = being redirected to where the resource now is.
- 400’s = client errors, you send the wrong thing.
- 500’s = server erros, the backend code messed up
2. What is a status code 202?
    - accepted
3. What is a status code 308?
    - permanent redirect
4. What code would you use if an update didn’t return data to a client?
    - 204
5. What code would you use if a resource used to exist but no longer does?
    - 308
6. What is the ‘Forbidden’ status code?
    - 403

Restful API with node.js

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
    - so that we can use any database location not just the local host
2. What is middleware?
    - code that runs when the server gets a request but before it gets passed to the routes
3. What does app.use(express.json()) do?
    - allows us to get data as json data
4. What does the /:id mean in a route?
    - the : identifies a parameter
5. What is the difference beween PUT and PATCH?
    - patch only updates teh data that is passed.
6. How do you make a defalut value in a schema?
    -  default: _____ within the object of the schema
7. What does a 500 error status code mean?
    - internal server error
8. What is the difference between a status 200 and a status 201?
    - 201 means successful creation and is more specific than 200.

## Things I want to know more about

