### Choosing the State Structure

1. **Single Source of Truth**: Keep each piece of state in one location within the application.
2. **Minimize Redundancy**: Avoid duplicating state across multiple components.
3. **Lift State Up**: Place state in a common ancestor to those components that need it.
4. **Keep State Local**: If only one component needs the state, it should be managed within that component.
5. **Encapsulate Complexity**: Use abstraction to manage complex state logic, keeping the interface simple.

### Passing State Deeply with Context

- **Problem Contexts Solve**: Contexts are designed to provide a way to pass data through the component tree without having to pass props down manually at every level.
- **Technique Before useContext**: Before using `useContext`, consider component composition or prop drilling as simpler alternatives for passing state.
- **Hook Complementing useContext**: The `useReducer` hook often complements `useContext` for managing more complex state logic within a context.