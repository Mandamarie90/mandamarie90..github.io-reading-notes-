#### What is functional programming?

A programming paradigm where programs are constructed by applying and composing functions. It emphasizes immutability, pure functions, and avoiding side effects.

#### What is a pure function and how do we know if something is a pure function?

A function that always produces the same output for the same input and has no side effects. We know if a function is pure if it doesn't rely on external state, doesn't mutate data, and always returns the same result for the same inputs.

#### What are the benefits of a pure function?

Easier testing, better code maintainability, improved readability, and improved concurrency due to lack of side effects.

#### What is immutability?

 A concept where once an object is created, its state cannot be changed. Instead of modifying existing objects, immutable data structures are created with modified values.

#### What is Referential transparency?

A property of pure functions where a function call can be replaced with its resulting value without affecting the program's behavior.

#### What is a module?

A reusable piece of code that encapsulates related functionality. It helps in organizing and maintaining code by breaking it into smaller, manageable units.

#### What does the word ‘require’ do?

Import modules or libraries into the current file. It allows access to functionality defined in other files.

#### How do we bring another module into the file the we are working in?

 Use the require keyword followed by the path to the module file to bring another module into the file we are working in.

#### What do we have to do to make a module available?

 Export its functionality using the module.exports or exports keyword in the module file. This allows other files to import and use the module.