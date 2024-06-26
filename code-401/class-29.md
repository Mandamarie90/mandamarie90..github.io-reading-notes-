Sure, here are the answers to the questions in Markdown:

### Extracting State Logic into a Reducer

**What is the motivation for adding a reducer?**
- A reducer centralizes state logic, making complex state updates easier to manage and debug.

**What are actions in the context of a reducer? How are they different than setting state directly?**
- Actions are objects that describe the type of state change. They are dispatched to the reducer to update the state, instead of directly setting it.

**What common list operation is useReducer named for, and why?**
- useReducer is named after the "reduce" operation, which processes a list of items to produce a single cumulative result, similar to how a reducer function processes actions to produce a new state.

**When should you switch from useState to useReducer?**
- Switch to useReducer when state logic becomes complex or when multiple state transitions depend on each other.