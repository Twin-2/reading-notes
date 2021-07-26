# Pre class 10 reading

Authorization is dificult to manage in todays technology where people might need to bounce back and forth between multiple application needing idividual sign ons.

OpeN Authorization (oauth) allows users to log on once and acces multiple areas of content.

>[Authentication](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html) is the process of a user/subject proving its ownership of a presented identity, by providing a password or some other uniquely owned or presented factor. 

>[Authorization](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html) is the process of letting a subject access resources after a successful authentication, oftentimes somewhere else.


## Questions

OAuth:
1. What is OAuth?
    >[OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html) is an open-standard authorization protocol or framework that describes how >unrelated servers and services can safely allow authenticated access to their >assets without actually sharing the initial, related, single logon credential. In >authentication parlance, this is known as secure, third-party, user-agent, >delegated authorization.
2. Give an example of what using OAuth would look like.
- using your google account to log into another website
3. How does OAuth work? What are the steps that it takes to authenticate the user?
    1. Web1 connects to web2 on behalf of the user providing the users verified identity
    2. web2 generates a 1-time token and secret unique to this transaction
    3. web1 gives gives token and sevret to the users client software.
    4. client software presents the token and secret to theur authorization provider (could be second site but may not be)
    5. If not authenticated, client must authenticate. Then clilent is asked to approve the authorization to second website.
    6. user approves transactionat web1
    7. user is given approved access token
    8. user gives approved token to web1 
    9. web1 gives access token to web 2 as proof of authentication on behalf of user.
    10. web2 lets web1 access site on behalf of user
    11. user sees completed transaction
4. What is OpenID?
- OpenID is similar to OAuth but differes in that it provides authentication not authorization.

Authorization flow:
1. What is the difference between authorization and authentication?
- authORIZation is gaining or giving access. AuthENTication is prooving you are who you say you are.
2. What is Authorization Code Flow?
- it exchanges an Authorization code for a token and is the process that OAuth uses to authorize users. 
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
- similar to above but uses a Proof Key for code exchange.
4. What is Implicit Flow with Form Post?
- this OAuth but only if the application is unable to securely store user data. It also uses ony an ID token.
5. What is Client Credentials Flow?
- used for machine to machine communication where there are nto users present. Authorizes and authenticate app not the user.
6. What is Device Authorization Flow?
- used for authorizing devices to an internet group/service.
7. What is Resource Owner Password Flow?
- this is true username and passwork sign on.

### Things i want to know more about

