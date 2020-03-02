---
title: "Variables And Data Type in JavaScript"
description: "Variable is a container that stores the value or data. Variable is created and declared by using the var, let, and const keyword. for e.g"
date: "2020-02-19T15:34:28.297Z"
categories: []
published: true
canonical_link: https://medium.com/@ak8393267/variables-and-data-type-in-javascript-c2f9b0126c48
redirect_from:
  - /variables-and-data-type-in-javascript-c2f9b0126c48
---

Variable is a container that stores the value or data. Variable is created and declared by using the var, let, and const keyword. for e.g

`var x = 5;`

We have declared the variable (x) to assign the data (5) with a single equal sign. The variable is only declared using var, let, and const.

### Variable naming

There are two rules on JavaScript variables. when the variable name contains multiple words we can use camelcase.

1.  The name must contain only letters, digits, or the symbols `$` and `_`.
2.  The first character must not be a digit.
3.  Variable always starts in lowercase.

**The difference between the let, var, and const**

-   `let` – is a modern variable declaration.
-   `var` – is an old-school variable declaration.
-   `const` – is like `let`, but the value of the variable can’t be changed.

### Data Type

A variable in JavaScript can contain any data. A variable can at one moment be a string and a number. There are two types of Data Type one is Primitive Datatype and another one is Non-primitive. There are six primitive data types: strings, numbers, Boolean, null, undefined, and Symbol.

### Strings

A **string** is a series of characters. the string can be wrapped in double-quotes (`" "`)

```
"the string"; // double quoted string
```

**single quotes** (`' '`)

```
'Push'; // single quoted string
```

### Numbers

A number is a numerical value. The number doesn’t have any syntax like as a string If we write the number in (`"5"`) quotes it became a string.number can be a decimal, positive or negative value.

```
var x = 5; // whole integer
var y = 1.2; // float
var z = -76; // negative whole integer
```

There are many operations that we can apply on numbers like addition (`+`), subtraction (`-`), division (`/`) and multiplication (`+`). for e.g

```
var sum = 2 + 5; // returns 7
var difference = 6 - 4; //returns 2
```

#### NaN

NaN means Not a Number, even though it’s technically a number type.

### Boolean

A Boolean is a value that is either true or false. This type is commonly used to store yes/no values: `true` means “yes,”, and `false` means “no,”.

### Undefined

An undefined variable has no value. with variable let, we can define a variable but not assign a value to a variable it is undefined.

```
var thing; // returns undefined
```

### Null

Null is a value that represents nothing. The difference between Null and undefined. The Null is an internally empty value.

### Symbol

The symbol for unique identifiers. A Symbol is a new primitive data type in ES6

**Non-Primitive DataType**

### Object

An object is a collection of name/value pairs. You can create an object with a pair of curly braces {}

```
var student = {};
```

We can apply some properties to the student object using name/value pairs. They will be comma-separated and written as `propertyName: propertyValue`.

```
var dtudent {
  firstName: "rajesh", // string
  lastName: "sharma", 
  location: "Dharamshala", 
  introduced: 1999, // number
};
```
