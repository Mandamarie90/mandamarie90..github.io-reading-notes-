#### What is a ‘call’?

refers to invoking or executing a function.

#### How many ‘calls’ can happen at once?

Only 1 call

#### What does LIFO mean?

LIFO stands for Last In, First Out. It's a principle where the last item added to a stack is the first one to be removed.

#### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.


|       |
|_______|  ->  foo()
|  foo  |  ->  bar()
|_______|  ->  baz()
|  bar  |
|_______|
|  baz  |
|_______|


#### What causes a Stack Overflow?

the call stack exceeds its maximum size due to excessive recursion or deeply nested function calls.

#### What is a ‘reference error’?

A 'reference error' occurs when trying to access a variable that is not declared or is out of scope.

#### What is a ‘syntax error’?

A 'syntax error' occurs when there's a mistake in the structure of the code, violating the language's grammar rules.

#### What is a ‘range error’?

A 'range error' occurs when trying to operate on a value outside the acceptable range, such as accessing an array index that doesn't exist.

#### What is a ‘type error’?

A 'type error' occurs when trying to perform an operation on a value of the wrong type, such as calling a method on an undefined variable.

#### What is a breakpoint?

A breakpoint is a point in your code where execution will pause so you can inspect the state of the program during debugging.

#### What does the word ‘debugger’ do in your code?

A 'debugger' is a tool that helps developers find and fix errors in their code by allowing them to inspect variables, step through code execution, and set breakpoints for pausing execution at specific points.