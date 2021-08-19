# 301 Top Sumarized notes

[Back to menu](../README.md)

## Week 1: React

**React** is a tool to build UI or User Interface, the stuff you see when you open an app or go to a web page

React uses a conept called **components** to breack up data. In coding terms you can think of them like big objects or functions. You can also think of them like lego building blocks, but instead of 2x2's or 2x4's they are seperate parts of the UI. 
- each component should only do **one thing**
- an example of this is Facebook. The whole page is one component, then each post would be another component inside that one, then the space that actually holds the text might be another, and the like buttons are another, and so on...
 
 Component style architecture allows for some very easy building, as each component is **resuable**. For example, once you havea like button you for Facebook, you could use that same like button in Instagram.

 Each component has **properties** or **props** which can be used to pass information from one to the next. 
- props are **static** and do not change. They can be passed aroung but not reassigned.

 Each component also has **state** which is a unique property to that component. State is dynamic and can be changed.
 - you can use state to make components interactive. Since it is dynamic we can change it and manipulate it. 
 - we change state with a unique function called '**setState**'

 ### Advanved topic:
 You can use props to **pass** state. Meaning, if you create a 'setState' function in a parent component, and then pass that function as a prop to a child component, when we use that function on the child it will pass up the chain to set state on the parent. 

## Week 2: Server

The server is the **backend** of web design. 

Servers are responcible for taking in infomration from the UI or **frontend** and then either storing it or using it to send back what has been asked for. 
- in their simplest form, API's talk between computers to pass information around

Roy Fielding was the man who made the first web server and created the concept of web communication.  
- from his work we now use **RESTful** verb to talk between computers
- these are the 4 main types of commands that computers send back and forth they are:
    - GET -> send back some information
    - Post -> create new information into the database
    - PUT -> Update information that is already there
    - Delete -> take away information from the database

An API or **Application Programming Interface** is a set of code that can talk to another computer usingR RESTful verbs
- An API is usually connected to a **database** of information.
- When we send a RESTful command to an API it will respond with the appropriate response.

There are a lot of API's out there that you can use! One simple on is the national weather service. they have a huge collection of information that you can ask for (GET) and thier server will send that back to you.

### Advanced Topic:
An API should also process any data you are trying to get. So if you ask for weather information your server can go get a HUGE file and give that back to you, or it can **filter** out to just the data you want, like the high and low temp and sky contitions. This will improve frontend performance. 

## Week 3: Data Storage

Databases are just stores of **information**

We can store information in a **cache** for temporary use but that wont last from user to user. 

By using a database we can create a log, or memory, of unique data from our users.
- as example is your Facebook profile. It holds all your picture, information about you and all your posts. This information is all held ona  database.

Our front end is where we can **input** information that then gets sent to our backend, which then saves it to our database

Our frontend could also request data from the database **OR** another API's database

## Authentication

Now that we have a front end, backend server, and a database, we might want to allow each user of our application to save unique information.

To do this we need to use **Authentication** and **Authorization**
- Authentication is confirming you are who you say you are
- Authorization is choosing what information you can access once you have been authenticated.

Authentication allows for unique users to a website.

With unique users you can save unique data to your database for each person that they can come back to.
- once again think of Facebook. You have a profile that is **yours**. you can go to a firends profile but you can't edite their relationship status.
- You have been **Authenticated** into Facebook so they know you are you. Now you can post ans see your firneds.
- You are not **Authorized** to edit your friends profile. You can post but not change things like relationship status.