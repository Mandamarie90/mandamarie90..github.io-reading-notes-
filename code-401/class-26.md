### What are the building blocks of a React app?
Components are the building blocks of a React app, as they allow you to split the UI into independent, reusable pieces.

### What is the difference between an HTML element and a React component?
An HTML element is a basic building block of a webpage, while a React component is a reusable piece of UI that can contain HTML, CSS, and JavaScript logic.

### What is JSX and why do we use it?
JSX is a syntax extension for JavaScript that looks similar to HTML and is used to describe what the UI should look like in a React app.

### Describe the process of embedding JavaScript expressions in JSX.
You can embed JavaScript expressions in JSX by enclosing them in curly braces `{}`.

### Does React or JSX have any special features for iteration or conditional logic?
Yes, React supports iteration using array methods like `map()` and conditional logic with JavaScript operators or ternary expressions within JSX.

### How does React know to respond to a user’s inputs?
React responds to user inputs by using event handlers that are attached to elements in the JSX.

### What word indicates that a React component manages data with a Hook?
The word `use`, as in `useState` or `useEffect`, indicates that a React component manages data with a Hook.

### How can two react components share data?
Two React components can share data by lifting the state up to their closest common ancestor and passing it down as props.

### Render and Commit
Rendering is the process where React builds a new virtual DOM and compares it with the previous one, and committing is when React updates the actual DOM to reflect the changes.

### What are the three steps of refreshing a React UI?
The three steps are rendering, reconciling, and committing.

### How do you trigger updates to a component after the initial render?
You trigger updates to a component by changing its state or props.

### Does React recreate DOM nodes on every rerender?
No, React updates only the necessary parts of the DOM using a process called reconciliation.

### After React has updated the DOM, what still needs to happen before the user sees the change?
The browser needs to repaint the screen to reflect the updated DOM changes.