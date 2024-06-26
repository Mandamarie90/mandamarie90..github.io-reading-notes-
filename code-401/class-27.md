### Thinking in React

1. **Break the UI into a component hierarchy**: Identify components and arrange them in a hierarchy.
2. **Build a static version**: Create a non-interactive version using props to pass data.
3. **Identify the minimal state**: Determine the least amount of state needed for your application.
4. **Identify where your state should live**: Find the common ancestor component that should own the state.
5. **Add inverse data flow**: Implement callbacks to allow child components to update the state in their parent components.

### State: A Component’s Memory

A local variable isn’t sufficient for managing a React component because local variables don’t trigger re-renders when they change.

### useState Hook

The argument to the `useState` hook is the initial state value, and the two parts of its return array are the current state value and a function to update that state.

### Accessing State from Another Component

Component A can access state from Component B by lifting the state up to their closest common ancestor and passing it down as props.