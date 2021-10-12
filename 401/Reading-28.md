# Lecture 28

useEffect( callback, condition to run)

- the condition ot run must be an array and they whatever you want to listen for chaning is inside that array.

if you do not pass in a condition it will exceute for **any** condition (aka on render)

you can pass in an empty array to make the effect will only run once. (aka componentDidMount)

## Assignment

Review, Research, and Discussion
In your reading notes page for this class, provide answers to the following prompts. Cite any external sources

1. Why do we not need more .html pages in a multi-page React app?

   - React only renders a single html page. It uses things like a browser router component to change which components or pages are rendered at any one time. But the react loads a single html file into the browser that has ALL of the html for all pages.

2. If we wanted a component to show up on every page, where would we put it and why?
   1. Outside the `<BrowserRouter/>`. This way it is not dependant on the router. I would also consider putting in on the index.js with the rendered app.
   2. ~~Inside the `<BrowserRouter />`, outside a `<Route />~~
   3. ~~Inside a `<Route />`~~
3. What does routing do with the components that were rendered when a new route is requested.
   - it allows for only some components to be rendered at a time or under certain conditions.
4. What does props.children contain?
   - props.children holds what ever child content is within the tags of the parent element.
5. How do useState() and this.setState() differ?
   - use state is for a functional component and set state is for a class component.

Document the following Vocabulary Terms

- State Hook: allows for setting of state in a functional component.
- Mounting and Un-Mounting: in the context of a component, it is when it renders to the page.
