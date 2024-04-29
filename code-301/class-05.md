#### What is the single responsibility principle and how does it apply to components?

he single responsibility principle states that a component or module should have only one reason to change. In the context of components, this means that each component should ideally have a single responsibility or task. For example, a button component should focus solely on rendering a button and handling button-related interactions, such as clicks. This principle ensures that components are focused, modular, and easier to maintain, as they encapsulate specific functionality without unnecessary complexity.

#### What does it mean to build a ‘static’ version of your application?

Building a "static" version of an application means creating a fixed user interface without any dynamic behavior or interactivity.

#### Once you have a static application, what do you need to add?

Once you have a static application, you need to add dynamic behavior and interactivity to make it functional and responsive to user input.

#### What are the three questions you can ask to determine if something is state?

- Does it change over time?
- Can it be passed as props from a parent component?
- Does it depend on user input or interaction?

#### How can you identify where state needs to live?

You can identify where state needs to live by considering which components require access to and control over the state, and determining if the state should be shared among multiple components or localized to a specific component.

#### What is a “higher-order function”?

A higher-order function is a function that either takes another function as an argument or returns a function as its result.

#### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

In line 2 of the `greaterThan` function, it defines a function `check` which takes a parameter `y`, and returns a Boolean value indicating whether `y` is greater than the value `n` captured by the outer function.

#### Explain how either map or reduce operates, with regards to higher-order functions.

Both map and reduce are higher-order functions.

- map takes a function as an argument and applies it to each element of an array, returning a new array with the transformed values.

- reduce takes a function as an argument along with an initial value, and applies that function to each element of an array, accumulating a single result.