# Lecture State Hooks

Testing:

- backend is TTD, Front end is BDD

- You do not start testing from the beginning. You usually end up going through QA before testing.

1. How:

   - import the whole react library
   - import from @testing-library/reactsting: render, fireEvent, waitFor, screen.

2. When:

   - often after QA

3. What:

   - no describe block.
   - it is the same a sit.
   - screen.getByTestId looks for a 'data-testid' attribute.

Setting state: `const [click, setClick] = useState(0);`

- you have to import useState from react to have access to useState method.
- you can call an expression within a 'setState' method.
  - for example, you can use a boolean statement within the function call to change a boolean state.

**use superagent for making HTTP requests**

## Questions

## Things I want to know more about

passing/reusing sass variables

look up RTL (react testing library) for methods.

pretty print

## Assignment

Review, Research, and Discussion
In your reading notes page for this class, provide answers to the following prompts. Cite any external sources

1. How does React differ from vanilla JS/HTML/CSS?
   - react is a library for UI development. It allows you to combine html and javascript on one file making for easier code writing. React then internally compiles all that code down to html and javascript thatthe browser can read.
2. What is the primary difference between a function component and a class component?
   - A class componenet extends the React component object. A functional component is just a function that can use react methods that are brought in.

Document the following Vocabulary Terms

- Functional Components: a component that is a function rather than a class. There are many advantages around less code that you have to write.
- Children / Child Components: a child componenet is any component that is rendered inside another.
