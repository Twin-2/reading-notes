# Lecture 7

## WQuestions

How can we verify if we are constantly creating new tokens? When do they get saved avs created? How long for?

My try catch didn't catch a sequelize error? I had to use an if/else statement instead.

## Questions

Review, Research, and Discussion

1. Write the following steps in the correct order:
- Register your application to get a client_id and client_secret
- Ask the client if they want to sign in via a third party
- Redirect to a third party authentication endpoint
- Make a request to a third-party API endpoint
- Receive authorization code
- Make a request to the access token endpoint
- Receive access token
2. What can you do with an authorization code?
- it allows us to create tokens for our users. 
3. What can you do with an access token?
- deligate acces to certain resources. the token can hold their 'role' or CRUD access level. 
4. What’s a benefit of using OAuth instead of your own basic authentication?
- we know it will work!

Document the following Vocabulary Terms
- Client ID: used by our application to talk to Oauth
- Client Secret: ussed to encode the token.
- Authentication Endpoint: the send off to the third part auth system to authenticate the user.
- Access Token Endpoint: gives us back a token. 
- API Endpoint: any endpoint for a server.
- Authorization Code: confirmation from a third party that the user is who they say they are. 
- Access Token: an encrypted string that hold information about the user. 
- Preview

Skim the following materials in preparation for the upcoming lecture. Note the following as you browse the material, and be prepared to participate in discussions during lecture

1. Which 3 things had you heard about previously and now have better clarity on?
- OAuth and it's implementation. Doesn't Auth0 work with OAuth?
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- testing.
3. What are you most excited about trying to implement or see how it works?
- i'm really excited to get more into bearer auth. 