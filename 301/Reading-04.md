# Class 4 Pre reading

[Back to menu](../README.md)

Conditional operator
- 'condition ? value if true : value if false'

forms have to update a state as that is where we have dynamic data in React.

So we have to make sure to have a setState method and any other methods must work through that.


# Class 4 Lecture Dynamic forms
package json hold meta info, automation scripts, and dependancies.

**Everything is a form** Login pages are forms, FB posts ar forms...

Purpose of forms: submit information. In react that would mean changing state. 

In reaqct you want to do two things with forms:
1. update state on submit
2. update state as the form is being changed. 

input type submit is a button that submits your form. 

you can set the form name to the same as the state name and then your setState function can look at the forme name to pick the state




## Things I want to know more about
Why do we need to update on submit with a form if we are already updating state as we change?

- numArray.sort((a, b) => a - b); // For ascending sort
- numArray.sort((a, b) => b - a); // For descending sort



## Questions
React Froms
1. What is a ‘Controlled Component’?
   - It is a component that has an event form in it and also controlls the state based on that form. 
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
   - We should update the state with each keystroke. This allows for the passing of the value more easily.
4. How do we target what the user is entering if we have an event handler on an input field?
   - I have no idea what this is asking and could not find anything in the reading that helped me understand this question.

The Conditional operator
1. Why would we use a ternary operator?
   - only one line of code to fulfil an if/else statement.
2. Rewrite the following statement using a ternary statement:
   -  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
  - x === y ? console.log(true) : console.log(false)