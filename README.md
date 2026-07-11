# 🚀 JavaScript Learning Repository

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active%20Learning-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

# 📖 Overview

Welcome to my **JavaScript Learning Repository**! 🚀

This repository documents my journey of learning JavaScript through practical coding exercises, browser-based examples, logical programming problems, and interactive mini projects.

The repository starts with JavaScript fundamentals and gradually progresses toward functions, objects, DOM selection, event handling, modular programming, and browser-based applications.

The main goal is to build a strong JavaScript foundation for **Frontend Development, React.js, Node.js, and Full Stack Web Development**.

---

# 🎯 Learning Objectives

* Understand JavaScript fundamentals
* Practice variables and expressions
* Learn conditional programming
* Understand logical and comparison operators
* Explore JavaScript functions
* Learn objects and object references
* Understand destructuring
* Practice DOM selection
* Handle browser events
* Write reusable and modular code
* Build interactive JavaScript mini projects
* Improve logical thinking and problem-solving skills

---

# 🛠️ Technologies Used

## Languages

* JavaScript
* HTML5
* CSS3

## Development Tools

* Visual Studio Code
* Git
* GitHub
* Browser Developer Tools

---

# 📂 Repository Structure

```text
JavaScript/
│
├── Variables.html
├── boolean.html
├── logical operator.html
├── Ifalternative.html
├── truthyandfalsy.html
├── scope.html
│
├── jsinsidebody.html
├── jsusinglink.html
├── script.js
│
├── functions.html
├── Practice.html
│
├── object.html
├── Practicse7.html
│
├── metroTicket.html
├── Cricket.html
├── cricketgame.html
├── Criecketgame.html
│
└── README.md
```

---

# 📚 Topics Covered

## 🔹 JavaScript Fundamentals

Introduction to the basic building blocks of JavaScript.

### Concepts Covered

* JavaScript Syntax
* Statements
* Expressions
* Console Output
* Browser Alerts
* Comments
* Arithmetic Operations
* String Concatenation
* Template Literals

---

## 🔹 Variables & Expressions

Practice with JavaScript variables and mathematical expressions.

### Concepts Covered

* `let`
* Variable Declaration
* Variable Initialization
* Updating Variable Values
* Arithmetic Calculations
* Assignment Operators

### Assignment Operators

```javascript
m += 1;
m -= 1;
m *= 4;
m /= 4;
```

---

## 🔹 Boolean & Comparison Operators

Understanding Boolean values and comparisons.

### Concepts Covered

* Boolean Values
* Greater Than
* Less Than
* Equality
* Strict Equality
* Comparison Expressions

### Operators

```javascript
==
=== 
>
<
>=
<=
```

The examples also demonstrate the difference between:

```javascript
5 == '5'
```

and

```javascript
5 === '5'
```

---

## 🔹 Conditional Statements

Decision-making using JavaScript conditions.

### Concepts Covered

* `if`
* `else`
* `else if`
* Conditional Expressions

### Practice Examples

* Driving Eligibility Checker
* Age-Based Decisions
* Metro Ticket Discount Logic

---

## 🔹 Alternative Conditional Operators

JavaScript provides shorter alternatives for certain conditional operations.

### Ternary Operator

```javascript
let result = age > 18 ? 'Adult' : 'Kid';
```

### Guard Operator

```javascript
let finalAge = age || 18;
```

### Nullish Coalescing Operator

```javascript
let finalAge = age ?? 18;
```

---

## 🔹 Logical Operators

Logical operators are used to combine multiple conditions.

### Operators Covered

```javascript
&&
||
!
```

### Concepts Practiced

* AND Conditions
* OR Conditions
* NOT Operator
* Multiple Condition Validation

---

## 🔹 Truthy & Falsy Values

Understanding how JavaScript evaluates values inside conditional statements.

### Falsy Values

* `false`
* `0`
* `""`
* `null`
* `undefined`
* `NaN`

All other values are generally treated as truthy.

---

## 🔹 JavaScript Scope

Understanding variable accessibility.

### Concepts Covered

* Global Scope
* Block Scope
* Variable Accessibility
* Variable Lifetime

---

# ⚙️ JavaScript Functions

Functions help organize code into reusable blocks.

## Concepts Covered

* Function Declaration
* Function Calling
* Parameters
* Arguments
* Return Statements
* Default Parameters
* Function Reusability

### Example

```javascript
function sum(a, b) {
    let sum = a + b;
    return sum;
}

console.log(sum(3, 8));
```

---

## 🔹 Default Parameters

Example:

```javascript
function greeting(name = '') {
    console.log(`Namaste ${name} uncle`);
}
```

---

# 🧠 JavaScript Practice Problems

The repository contains several beginner-friendly programming exercises.

## Odd or Even Checker

Determines whether a number is odd.

```javascript
function isOdd(num) {
    let rem = num % 2;
    return rem == 1;
}
```

---

## Larger Number Finder

Returns the larger of two numbers.

```javascript
function larger(x, y) {
    return x > y ? x : y;
}
```

---

## Celsius to Fahrenheit Converter

Converts Celsius temperature to Fahrenheit.

### Formula

```text
°F = (9/5 × °C) + 32
```

---

# 📦 JavaScript Objects

The repository introduces JavaScript objects and object-oriented data representation.

## Object Creation

```javascript
let product = {
    company: 'Mango',
    price: 343,
    item_name: 'T-Shirt'
};
```

---

## 🔹 Accessing Object Properties

### Dot Notation

```javascript
product.company
product.price
```

### Bracket Notation

```javascript
product['company']
product['price']
```

---

## 🔹 Updating Object Properties

```javascript
product.company = 'Banana';
```

---

## 🔹 Deleting Object Properties

```javascript
delete product.company;
```

---

## 🔹 Object Methods

Objects can contain functions known as methods.

```javascript
let product = {
    company: 'Mango',
    price: 343,

    displayPrice: function() {
        console.log(`Price of the product is ${this.price}`);
    }
};
```

---

## 🔹 `this` Keyword

The `this` keyword refers to the current object.

```javascript
this.price
```

It is used to access properties of the object inside object methods.

---

## 🔹 Autoboxing

JavaScript automatically allows primitive values to temporarily behave like objects.

Examples:

```javascript
'This is JavaScript'.length

'This is JavaScript'.toUpperCase()

'This is JavaScript'.replace('This', 'It')
```

---

## 🔹 Primitive vs Object Reference

Primitive values are copied by value.

```javascript
let a = 5;
let b = a;
```

Objects are assigned using references.

```javascript
let x = { num: 5 };
let y = x;

x.num = 8;
```

Changes made through one reference can affect the same object.

---

## 🔹 Object Comparison

Objects are compared using references.

```javascript
let m = { pop: 'djf' };
let n = { pop: 'djf' };

console.log(m == n);
console.log(m === n);
```

Even if object properties contain the same values, separate objects have different references.

---

## 🔹 Object Destructuring

Object destructuring provides a shorter way to extract object properties.

```javascript
let product = {
    company: 'Mango',
    price: 343,
    item_name: 'T-Shirt'
};

let { company } = product;

let { price, item_name } = product;
```

---

# 🧪 Object Practice Exercises

Object-based exercises include:

* Creating Product Objects
* Object Reference Assignment
* Updating Object Properties
* Bracket Notation
* Object Destructuring
* Comparing Object References

### Example Product Object

```javascript
let product = {
    company: 'Myntra',
    price: 343,
    'item-name': 'Stripped Shirt',
    delivery_time: 'today'
};
```

---

# 🌐 JavaScript and HTML Integration

The repository demonstrates multiple ways to use JavaScript with HTML.

## Internal JavaScript

JavaScript written inside:

```html
<script>
    console.log('Hello JavaScript');
</script>
```

---

## External JavaScript

HTML:

```html
<script src="script.js"></script>
```

JavaScript:

```javascript
console.log('JavaScript loaded');
```

---

# 🖥️ Browser Console & Debugging

Browser console methods practiced:

```javascript
console.log()
console.warn()
console.error()
alert()
```

These methods help with debugging and understanding program execution.

---

# 🌳 DOM Selection

Introduction to selecting HTML elements using JavaScript.

```javascript
document.getElementById()

document.getElementsByClassName()

document.querySelector()

document.querySelectorAll()
```

### Examples

```javascript
document.getElementById('click');

document.querySelector('h1');

document.querySelectorAll('button');
```

---

# 🖱️ Event Handling

Basic browser event handling is implemented using button click events.

Example:

```html
<button onclick="alert('Good Morning')">
    Click
</button>
```

### Concepts Covered

* Button Events
* `onclick`
* User Interaction
* Browser Alerts

---

# 🎮 Mini Projects

## 🏏 Bat Ball Stump Game - Basic Version

A simple browser-based game where the user chooses:

* Bat
* Ball
* Stump

The computer randomly generates its move.

### Concepts Used

* Variables
* `Math.random()`
* Conditional Statements
* Template Literals
* Event Handling
* Alerts

---

## 🏏 Bat Ball Stump Game - Function-Based Version

The improved version separates the game logic into reusable functions.

### Functions Used

```javascript
generateComputerChoice()

getResult()

showResult()
```

### Improvements

* Reduced repeated code
* Reusable game logic
* Cleaner program structure
* Modular programming

---

## 🏆 Bat Ball Stump Game - Score Tracking Version

The advanced version introduces a score object.

```javascript
let score = {
    win: 0,
    lost: 0,
    tie: 0
};
```

### Features

* Tracks User Wins
* Tracks Computer Wins
* Tracks Tie Games
* Displays Current Score
* Uses Object Methods
* Uses Reusable Functions

### Score Method

```javascript
displayScore: function() {
    return `Won:${score.win}, Lost:${score.lost}, Tie:${score.tie}`;
}
```

### Concepts Used

* JavaScript Objects
* Object Methods
* Functions
* Conditional Logic
* Random Number Generation
* Event Handling
* Score Management
* Modular Programming

---

## 🚇 Metro Ticket Discount Calculator

A JavaScript program that calculates passenger discounts based on age and gender.

### Discount Rules

* Children below a specific age receive free travel
* Female passengers receive a discount
* Young passengers receive discounted fares
* Senior citizens receive concessions

### Concepts Used

* Variables
* Conditional Statements
* Logical Operators
* Template Literals
* Business Logic

---

# 🚀 How to Run

## Clone the Repository

```bash
git clone https://github.com/nigamkumar3435-spec/JavaScript.git
```

## Navigate to Repository

```bash
cd JavaScript
```

Open any `.html` file in your preferred browser.

### Examples

```text
Variables.html
boolean.html
functions.html
object.html
Practice.html
Practicse7.html
Cricket.html
cricketgame.html
Criecketgame.html
metroTicket.html
```

You can also use the **Live Server** extension in Visual Studio Code.

---

# 🧠 Concepts Learned

## JavaScript Fundamentals

* Variables
* Expressions
* Operators
* Template Literals

## Decision Making

* Boolean Values
* Comparison Operators
* Conditional Statements
* Ternary Operator

## Logical Programming

* Logical Operators
* Truthy & Falsy Values
* Nullish Coalescing
* Guard Operator

## Functions

* Function Declaration
* Parameters
* Arguments
* Return Values
* Default Parameters
* Reusable Functions

## Objects

* Object Creation
* Dot Notation
* Bracket Notation
* Object Methods
* `this` Keyword
* Object References
* Object Comparison
* Object Destructuring
* Autoboxing

## Browser Programming

* Console Methods
* Alerts
* DOM Selection
* Event Handling

## Programming Practices

* Modular Programming
* Code Reusability
* Logical Problem Solving
* Code Refactoring

---

# 💡 Skills Developed

* JavaScript Fundamentals
* Logical Thinking
* Problem Solving
* Function-Based Programming
* Object Manipulation
* DOM Basics
* Event Handling
* Browser Debugging
* Modular Programming
* Code Reusability
* Interactive Web Development

---

# 📈 Learning Progress

```text
JavaScript Basics
        ↓
Variables & Operators
        ↓
Boolean & Conditions
        ↓
Logical Operators
        ↓
Truthy & Falsy Values
        ↓
Scope
        ↓
Functions
        ↓
Practice Problems
        ↓
Objects
        ↓
Object References
        ↓
Object Destructuring
        ↓
DOM Selection
        ↓
Event Handling
        ↓
Interactive Mini Projects
```

---

# 🔮 Future Enhancements

The repository will continue expanding with:

* Arrays
* Loops
* Strings
* Advanced Objects
* JSON
* Local Storage
* Date Object
* Array Methods
* Higher-Order Functions
* ES6 Features
* Classes
* Modules
* Promises
* Async/Await
* Fetch API
* Form Validation
* Calculator App
* To-Do Application
* Weather Application
* Expense Tracker
* Quiz Application
* E-Commerce Cart
* API-Based Projects

---

# 🤝 Contributing

Contributions and suggestions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit your changes
5. Push the branch
6. Open a Pull Request

---

# 👨‍💻 Author

## Nigam Kumar

🎓 B.Tech – Computer Science Engineering
🏫 Indore Institute of Science and Technology, Indore

### Connect With Me

GitHub: https://github.com/nigamkumar3435-spec

LinkedIn: https://www.linkedin.com/in/nigam-kumar01

---

# ⭐ Support

If you found this repository helpful, consider giving it a ⭐ on GitHub.

Your support motivates me to continue learning, practicing, and building more JavaScript projects.

---

# 📜 License

This repository is created for educational and learning purposes.

Feel free to explore, learn from, and improve the code.

---

### 💻 "Mastering JavaScript one concept, one function, one object, and one project at a time." 🚀
