#### Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
The render
#### What is the very first thing to happen in the lifecycle of React?

The very first thing that happens is the initialization. 

#### Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
constructor
render
componentDidMount
React Updates
componentWillUnmount
#### What does componentDidMount do?
 Fetches data or sets up interactions.

#### What types of things can you pass in the props?

In props, you can pass data such as strings, numbers, arrays, objects, functions, or even React elements.

#### What is the big difference between props and state?

The big difference is that props are passed into a component from its parent and remain immutable within the component, while state is managed internally by the component and can be changed over time.

#### When do we re-render our application?

We re-render our application when there's a change in the component's state or props.

#### What are some examples of things that we could store in state?

- User input data
- UI state (e.g., toggles, visibility)
- Fetching data from APIs
- Tracking changes in component's internal state