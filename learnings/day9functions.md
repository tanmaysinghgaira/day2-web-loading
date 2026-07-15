# JavaScript Functions

## What is a Function?

A function is a reusable block of code that performs a specific task. Instead of writing the same code multiple times, we can place it inside a function and call it whenever needed.

## Why Do We Use Functions?

- Reduce code duplication
- Improve readability
- Make code easier to maintain
- Break large programs into smaller parts
- Reuse logic whenever required

## Function Syntax

```javascript
function greet() {
    console.log("Hello World");
}
```

Calling the function:

```JavaScript
greet();
```

## Function with Parameters

Parameters allow us to pass values into a function.

```JavaScript
function greet(name) {
    console.log("Hello " + name);
}

greet("Tanmay");
```

## Function with Return Value

A function can return a value using the `return` keyword.

```JavaScript
function add(a, b) {
    return a + b;
}

let result = add(10, 20);
console.log(result);
```

## Function Expression

A function can also be stored in a variable.

```JavaScript
const multiply = function(a, b) {
    return a * b;
};

console.log(multiply(4,5));
```

## Arrow Function

Arrow functions provide a shorter syntax.

```javascript
const square = (num) => {
    return num * num;
};
```

Short form:

```JavaScript
const square = num => num * num;
```

## Types of Functions

- Named Function
- Anonymous Function
- Function Expression
- Arrow Function
- Callback Function

## Scope

Variables declared inside a function are available only inside that function.

```javascript
function test() {
    let message = "Hello";
    console.log(message);
}
```

## Benefits

- Reusable code
- Easy debugging
- Better organization
- Modular programming
- Cleaner projects

## Summary

Functions are one of the most important features of JavaScript. They help developers write reusable, organized, and maintainable code. Every modern JavaScript application uses functions extensively.
