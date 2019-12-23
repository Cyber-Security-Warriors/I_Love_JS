# Variable in JavaScript
**Variables** which hold the data value and it can be changed anytime. In JavaScript ``` var ```  Keyword use to declare a variable.
``` ; ``` used at the end of statement.

### Declaring a variable :
There are three different ways to declare the *variable*:
1. Using **var**
```javascript
var hight = 6;
var weight = 75;
var name = "Himanshu"; //variable declaration statement
```
from above example 
hight stores 6, weight store 75 & name will store String Himanshu.
2. Using **let**
```javascript
let age = 300;
```
age will store 300.
3. Using **const**
```javascript
const cool =true;
```
Each & every line end with semicolon is known as **Statement**.
### Difference b/w var, let & const :
var & let can be updated 
Major difference b/w var & let is that var variable are *function scoped* & let variable are *block scoped*. let introduced in ES6.
for eg : 
```javascript
// var variables are function scoped
>> var name = "himanshu";
>> name
"himanshu"
>> name = "Awasthi";
"Awasthi"
// let variable are block scoped
>> let x = 10;
>> x
10
>> x = 50;
50
```
const can't be updated
for eg :
```javascript
>> const cool = true;
>> cool
true
>> cool = false;
TypeError: invalid assignment to const `cool'
```
### Declare variable in **Strict Mode** :
In past we can declare variable without using any keyword(var,let & const) which is not good way to write code.
```javascript
// Normal 
dog = 'clever'; // bad practice of coding

// Strict Mode
'use strict';
dog = 'clever'; // ReferenceError: dog is not defined
```
### Scope for variables :
 -   **var** : Available in parent functions
        
 -   **let** and **const** : Available in a block denoted by _{ }_ 
 
 *Good Practice* use `const & let ` never use ` var `
 ### Naming Conventions for Variable
 - _should not_ start with capital unless they are _class_
 - Apart from A-Z & a-z only ' $ ' and ' _ ' sign can used in variable name.
 - Best way to declare variable is use _camelCase_
 ```javascript
 // camel case
 let iLovePizza = true;
 // UpperCamel Case
 const ILovePizza = false;
 // snake case
 const this_is_snake_case = true;
 // Kebab case(We not use in JS because - not allowed in variable name)
 const this-is-kebab-case = false;
 ```
 [click here to learn about Code Quality Tooling](03-code-quality-tooling.md)
     
