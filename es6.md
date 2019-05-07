# Resource:

https://www.udemy.com/
Course Name: Accelerated ES6 JavaScript Training

## Section 1 ES6 Introduction
**1. What is ES6**
ES6 is the next generation of javascript with additinal new features.

Now, not all browsers support ES6, so es6 code need to be rewrite in a ES5 style.

Three things to run ES6 locally:
1. Compiler: compile es6 code to es5 ([Babel](https://babeljs.io/))
2. Modules loader: SystemJS or Webpack
3. A lightweight server

## Section 2 Syntax changes& Extensions
**1. let & const**
_var_ and _let_ are all keywords used to declare changable variables.
The biggest difference between _var_ and _let_ is that _let_ supports BLOCK scope, NOT always global scope anymore!

e.g.:
if(true) {
    let age = 30;
}

console.log(age); // error occured: age is not defined.

_const_ is the keyword to decalre constant, unchangable variables.


