# Stack implementation in JavaScript
A stack is a structure of sequential and ordered elements.

A stack is based on the principle of last in first out (LIFO).

## Constructor Summary
Creates an empty stack. 

## Method Summary
Method | Description
--- | ---
`push()` | Pushes an item onto the top of the stack.
`pop()`  | Removes the item at the top of the stack and returns that item as the value of this function.
`peek()` | Looks at the item at the top of the stack without removing it from the stack.

```javascript
const Stack = require("@tdd-with-maris/javascript-stack");

const stack = new Stack();

stack.push(7);

stack.push(42);

stack.peek();
// => 42

stack.pop()
// => 42

stack.peek();
// => 7
```

