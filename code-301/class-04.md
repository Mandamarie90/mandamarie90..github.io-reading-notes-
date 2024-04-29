
#### What does .map() return?

The .map() function in JavaScript returns a new array by applying a function to each element of the original array.

#### If I want to loop through an array and display each value in JSX, how do I do that in React?

#### Each list item needs a unique ____. 

Each list item needs a unique key.

#### What is the purpose of a key?

The purpose of a key in React is to provide a unique identifier for each element in a list. When rendering lists of elements, React uses keys to efficiently update and re-render the components. Keys help React identify which items have changed, been added, or been removed, optimizing performance and preventing unexpected behavior.

### The spread operator

#### What is the spread operator?

The spread operator in JavaScript allows iterable elements like arrays, strings, or objects to be expanded into individual elements. It's commonly used for copying, combining, and spreading elements in an easy and concise manner.

#### List 4 things that the spread operator can do.

Copying arrays or objects.
Combining arrays or objects.
Adding new items to arrays or objects.
Passing multiple arguments to functions.

#### Give an example of using the spread operator to combine two arrays.

const array1 = [1, 2, 3];
const array2 = [4, 5, 6];
const combinedArray = [...array1, ...array2];
console.log(combinedArray);

#### Give an example of using the spread operator to add a new item to an array.

const oldArray = [1, 2, 3];
const newItem = 4;
const newArray = [...oldArray, newItem];
console.log(newArray); 

#### Give an example of using the spread operator to combine two objects into one.
const obj1 = { a: 1, b: 2 };
const obj2 = { c: 3, d: 4 };
const combinedObject = { ...obj1, ...obj2 };
console.log(combinedObject);

#### In the video, what is the first step that the developer does to pass functions between components?

The first step that the developer does to pass functions between components is to define the function in the parent component.

#### In your own words, what does the handleClick function do?

In the video, the handleClick function is a callback function that is triggered when a button is clicked. It updates the state of the component, changing the value of the isOpen state variable from false to true.

#### How can you pass a method from a parent component into a child component?

To pass a method from a parent component into a child component, you can pass the method as a prop to the child component.

#### How does the child component invoke a method that was passed to it from a parent component?
The child component can invoke a method that was passed to it from a parent component by accessing the method through props and then calling it with the necessary arguments. For example, if a method named handleClick is passed from the parent to the child component as a prop named onClickHandler, the child component can invoke it like this: this.props.onClickHandler().