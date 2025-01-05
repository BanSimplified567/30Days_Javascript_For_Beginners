# 30 Days of JavaScript for Beginners

Welcome to my **30 Days of JavaScript for Beginners** program! This project represents the knowledge and skills I've gained during my first two years of learning how to code as a beginner. It's not entirely complete, but I wanted to share my journey and progress with you.

## Table of Contents

1. [Getting Started with JavaScript](#getting-started-with-javascript)
2. [JavaScript Conditionals](#javascript-conditionals)
3. [JavaScript Functions](#javascript-functions)
4. [JavaScript Scope](#javascript-scope)
5. [JavaScript Arrays](#javascript-arrays)
6. [JavaScript Loops](#javascript-loops)
7. [JavaScript Iterators](#javascript-iterators)
8. [JavaScript Objects](#javascript-objects)
9. [JavaScript Classes](#javascript-classes)
10. [JavaScript Modules](#javascript-modules)
11. [JavaScript Promises](#javascript-promises)
12. [JavaScript Async-Await](#javascript-async-await)
13. [JavaScript Requests](#javascript-requests)
14. [Tips and Tricks for Beginners](#tips-and-tricks-for-beginners)

---

## 1. Getting Started with JavaScript

Learn the basics of JavaScript, including what it is, how it works, and how to set up your development environment. Topics covered include embedding JavaScript in HTML, using the browser console, and writing your first JavaScript program.

```js
//Console

// => Hello world!
console.log('Hello world!');

// => Hello QuickRef.ME
console.warn('hello %s', 'QuickRef.ME');

// Prints error message to stderr
console.error(new Error('Oops!'));

```

```js
//Variables
let x = null;
let name = "Tammy";
const found = false;

// => Tammy, false, null
console.log(name, found, x);

var a;
console.log(a); // => undefined


```

```js
//Strings
let single = 'Wheres my bandit hat?';
let double = "Wheres my bandit hat?";

// => 21
console.log(single.length);

```

```js
//Arithmetic Operators
5 + 5 = 10     // Addition
10 - 5 = 5     // Subtraction
5 * 10 = 50    // Multiplication
10 / 5 = 2     // Division
10 % 5 = 0     // Modulo

```

```js
//Comments

// This line will denote a comment

/*
The below configuration must be
changed before deployment.
*/



```

```js
//Assignment Operators
let number = 100;

// Both statements will add 10
number = number + 10;
number += 10;

console.log(number);
// => 120


```

```js
//String Interpolation
let age = 7;

// String concatenation
'Tommy is ' + age + ' years old.';

// String interpolation
`Tommy is ${age} years old.`;


```

```js
// let Keyword
let count;
console.log(count); // => undefined
count = 10;
console.log(count); // => 10


```

```js
//const Keyword
const numberOfColumns = 4;
const fullname = "Jade Ivan Bringcola";
const knownAs = "Ban Ban";
const age = 22;

// TypeError: Assignment to constant...
numberOfColumns = 8;


```

---

## 2. JavaScript Conditionals

Understand how to make decisions in your code using conditional statements like `if`, `else if`, `else`, and `switch`. Control the flow of your program based on different conditions.

```js
//if Statement
const isMailSent = true;

if (isMailSent) {
  console.log('Mail sent to recipient');
}

```

```js
//Ternary Operator
var x=1;

// => true
result = (x == 1) ? true : false;

```

```js
```

```js
```

```js
```

```js
```

```js
```

```js
```

```js
```

```js
```

---

## 3. JavaScript Functions

Explore how to define and use functions to create reusable blocks of code. Learn about function expressions, function declarations, and arrow functions.

---

## 4. JavaScript Scope

Dive into the concept of scope to understand variable accessibility. This includes global, local, block, and function scopes, along with an explanation of `let`, `const`, and `var`.

---

## 5. JavaScript Arrays

Master the use of arrays for storing collections of data. Learn about accessing elements, and using array methods like `push()`, `pop()`, `map()`, `filter()`, and more.

---

## 6. JavaScript Loops

Understand how to repeat actions in your code using loops such as `for`, `while`, `do...while`, and `for...of`. Learn when and how to use each type of loop.

---

## 7. JavaScript Iterators

Iterators simplify working with collections of data. Learn how to use methods like `forEach()`, `map()`, `filter()`, and `reduce()` for efficient iteration.

---

## 8. JavaScript Objects

Discover how to create, modify, and use objects. Understand object properties, methods, object literals, and the role of `this` in JavaScript.

---

## 9. JavaScript Classes

Learn about classes, which provide a blueprint for creating objects. Understand constructors, methods, inheritance, and the `super` keyword.

---

## 10. JavaScript Modules

Organize your code into reusable chunks with modules. Learn how to create modules and use `import` and `export` statements effectively.

---

## 11. JavaScript Promises

Promises allow you to manage asynchronous operations. Learn how to create, resolve, and chain promises, as well as handle errors using `.catch()`.

---

## 12. JavaScript Async-Await

Simplify working with promises using `async` and `await`. Learn how these keywords make asynchronous code more readable and easier to debug.

---

## 13. JavaScript Requests

Handle HTTP requests using the `fetch()` API or libraries like Axios. Learn to send GET and POST requests and process JSON data efficiently.

---

## 14. Tips and Tricks for Beginners

Explore practical advice for new developers, including debugging techniques, efficient coding practices, and common pitfalls to avoid.

---

Happy coding! 🚀

Feel free to explore each topic and practice using the examples and exercises provided.

## Cloning the Repository

If you'd like to clone this repository, please check in with me first to confirm it's okay. Once you have my permission, you can follow these steps:

1. Open your terminal.
2. Run the following command to clone the repository:

   ```bash
   git clone https://github.com/BanSimplified567/30Days_Javascript_For_Beginners.git
