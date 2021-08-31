# Lecture 8

## Code Review

package.json needs to be at root to be recognised by deploys
- 

index.js in root 

model/index: DB config



## ACL - action control list

these are assigning roles to CRUD actions

the info about the access is on the token

### UserModel
the userModel needs a 'role' property
- use Type ENUM to allow specific expectations for the strings
  - set a default

also needs 'capabilities'
- this is virtual
- our capabilities field is dynamic based off the role.
- uses a get(){} and returns an array of 'access' which ar CRUD actions. 

### Middleware 

middleware needs to check if the passed in capabilities is contained in the user

structure: have a wrapper function called permissions, that **returns** req,res,next




## Questions

xWhere does the token live on the UI?

Q: collection class (where and when) with a model that has functions on it. 
- line 14 is a fucntion, not a model. How does that work?
    - the function is returning the model.
- is this really necessary? Sequelize already has CRUD actions
    - its good lcean up but not necessary. It would be a good secondary level but not needed when first building. 

Q: Why Bearer if we are always just going to take it off? 
- we do use it. a good convention is to check if the auth type is basic or bearer or whatever.

Q: capabilities get added to the token?

<!-- Can we have access to demo code at class start time to be able to follow along with you? -->

how do we set the role?
- usually the admin would have this capability

how do these permissions come into play with testing?

## Things I want to know more about 

Permissions

error handling

testing for the new dynamic route structure. Can we make those tests dynamic to the user type? Or do we need to just test each different user suite with their own permission levels?

**router parameters** pro level shit
- works well for sinlge level resources.

## Lightbulb moments
propper CRUD actions connecting from requests to the crud actions. 

## Reading assignment Questions

In your reading notes page for this class, provide answers to the following prompts. Cite any external sources

1. When is Basic Authorization used vs. Bearer Authorization?
- basic auth is used to sign someone in. bearer auth is then used to access different areas of the site with a token. If that token is saved in a cookie, it would be possible to contitnue to use beaere auth to persist login across sessions by continuing login status.
2. What does the JSON Web Token package do?
- JWT allows for encoding of a token with user info on it. 
3. What considerations should we make when creating and storing a SECRET?
- it must always be kept secret. 

Document the following Vocabulary Terms
- encryption: the process of changing something into a completely random series of characters that do not have and relation to the original input. 
- token: a token is an encoded string that contains info about the user. 
- bearer: the user with a token.
- secret: a string used to further encode  a token.
- JSON Web Token: the service we use to encode tokens.

Skim the following materials in preparation for the upcoming lecture. Note the following as you browse the material, and be prepared to participate in discussions during lecture

1. Which 3 things had you heard about previously and now have better clarity on?
- dynamic error handling.
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- i just need more practice with writing tests. 
3. What are you most excited about trying to implement or see how it works?
- dynamic router params.