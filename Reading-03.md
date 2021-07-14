# Class 3 Pre reading
Lists and keys
- Clarification: you can have a const that is the same as a prop because props are properties on the element object not reserved keywords declaired in JS.
- you can use map to itterate through an array and in the function render components.
- keys are needed for react to ID which items are changed.

Passing function in react
- you have to put a function that alters state in the component that the state is in.
-  

## Things I want to know more about
Clarification: you can have a const that is the same as a prop because props are properties on the element object not reserved keywords declaired in JS.
the Spread operator. i don't really think i understand it at all. 

## Command line and Code


Questions:
1. What does .map() return? 
   - A new array.
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
   - you can us {} to include javascript code within JSX.
3. Each list item needs a unique ID.
4. What is the purpose of a key?
   - to let react keep track of the items as the change. 


1. What is the spread operator?
   - it is (...) and is similar to a rest parameter.
2. List 4 things that the spread operator can do.
   - copy an array, uses math functions, combine objects, add to state in react.
3. Give an example of using the spread operator to combine two arrays.
   -  const array3 = [...array1, ...array2]
4. Give an example of using the spread operator to add a new item to an array.
   -const moreFood = [banana, apple, ...foodArray]
5. Give an example of using the spread operator to combine two objects into one.
   - obj1 = {}, obj2 = {}, newObj = {...obj1, obj2}


1. In the video, what is the first step that the developer does to pass functions between components?
   - he has to create a function wherever the state that we want to change is. 
2. In your own words, what does the increment function do?
   - the increment function looks at the state.people of the App component and maps throught them. For each person, it checks if the individual person object.name is equal to the name that is passed in, and if it is then it increments the count by 1. it then sets the state to the new array created by map().
3. How can you pass a method from a parent component into a child component?
   - you can use props. create a new prop that is equal to the function in the parent and then you can use this.props."whatever you called it" to call the function in the child.
4. How does the child component invoke a method that was passed to it from a parent component?
   - the method that was passed as a prop can be incoked with () and then pass in the parameters. 