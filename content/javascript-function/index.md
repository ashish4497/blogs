---
title: "JavaScript Function"
description: "FUNCTION"
date: "2020-02-29T08:10:17.234Z"
categories: []
published: true
canonical_link: https://medium.com/@ak8393267/javascript-function-c43d24ed41ed
redirect_from:
  - /javascript-function-c43d24ed41ed
---

### FUNCTION

Imagine you live in a village without tap water. To get water, you need to take an empty bucket, head to the well in the middle of the village, draw water from the well and head back home. You need to draw water from this well multiple times a day.  
It’s difficult to say “I’m going to take an empty bucket, go to the well, draw water and bring back home” every time you explain what you’re doing. To shorten it, you can say you’re going to “draw water”. And we have created a function. Functions always return something. If there’s no return a statement, then the result is undefined. The basic structure of function

```
function functionName(parameter) {
 statement;
}
```

### DECLARING FUNCTION

```
Function is a keyword of javascript
FunctionName is the name of the function
Parameter is used to assign the value to the function
```

### USING FUNCTION

### The example of using the function

```
function sum (a,b) {
  return a+b ;
}
sum (12,8); 

// return the addition of a and b 

20 // output
```

### FUNCTION AS EXPRESSION

In a Javascript, The function expression had stored in a variable, the variable is used as a function. Functions do not need function names. They are always called with a variable name. The example of function as an expression

```
var multiplacation = function(a,b) {
  return a*b;
}
sum(2,3) 

//return the multiplacation of a and b 

 6 //output
```

### ANONYMUS FUNCTION

A Function Expressions defines a named or An anonymous function that has no name. The anonymous function is created at runtime. The function operator can be used anywhere that it’s valid to use an expression. The anonymous function starts with ‘var’

### The example of Anonymus function

```
var anon = function() { 
 console.log ('I am anonymous');
}
anon();

I am anonymous 
// output
```

### Arrow Functions

Arrow functions make our code easier and simplify. using arrow functions, we avoid having to type the function keyword, return keyword, and curly brackets.  
**Basic Syntax**

```
1) const multiplyES6 = (x, y) => x * y;


2) const multiplyES6 = (x, y) => { 
     return x * y; 
   };
```
