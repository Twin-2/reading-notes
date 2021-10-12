# Lecture

## ACL

We can have ACL at both ther server level and client side ACL

create a seperate component that holds the **context** of authorization..

- first keep track of isLoggedIn
- second keep track of what you canDo
  - pull in user capabilities from the user, compair that to a prop on the component
- third okToRender for each component
  - must be a && statement to check that the user is logged in and they have the matching capability

  You can use the react-if component When to condtitionally render **ANYTHING**
  