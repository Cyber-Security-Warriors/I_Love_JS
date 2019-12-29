## Types in Javascript :
There are 7 types in JS known as *SNOB'N'US*
1. String
2. Number
3. Object
4. Boolean
5. Undefined
6. Symbol : Always gives a guaranteed unique identifier
7. Null

Everything is Primitive type except Object, _Object_ is special one.

### String in JS

3 ways of creating String in Javascript
- ' '
```javascript
const first = 'Himanshu';
```
- " "
```javascript
const middle = "ihackpy";
```
- Backticks(``)
```javascript
const last = `Awasthi`;
```
Single quote & double quote both are same but when we avoid to use single quote in long sentences because It may have chance to break JS.

for eg:

```javascript
const life = 'She's beautiful'; // this raise error
const life = 'She\'s beautiful'; //Correct Use
const life = "She's beautiful"; // Correct Use
```
#### Multiline String:
```javascript
const song = 'ohhh \
ya\
I\
like Pizza';  // Better to use backticks
const song1 = `ohhh 
ya
I
like Pizza`;
```
#### Concatanation & Interpolation of String
 -   '+' is used for **concatenation**.
 -   **Concatenation**: when 2 or more strings combined to one
 
 -   For Eg:
    
 `const name = 'Himanshu';`
    
 `const hello = 'Hello my name is ' + name + '. It was Great to see You.'`
    
 _(can use double or single quotes)_
    
 -  For Eg:
 
 ` 1+1 // 2 `
 
 `'1'+'1' // 11 `
 
 `1 + '1' // 11`
 
 -   **Interpolation**: when you put a variable inside a string
 
 -  For Eg:
        
 const name = 'Himanshu'; const hello = `Hello my name is ${name}. Nice to meet you. I am ${100+1} years old.`; console.log(hello); // Hello my name is Himanshu. Nice to meet you. I am 101 years old.
        
-   Backticks also used for _tagged template literals_.

-   Backticks are helpful for creating HTML:

```javascript
  const html = `
    <div>
      <h2>Hey everyone! I am ${name}.</h2>
    </div>
  `;
```

### Numbers in JS



Only **one** type of number in JavaScript.

```javascript
const age = 24;
const area = 178.5;
console.log(typeof age); // number
console.log(typeof area); // number

```

-   `typeof` is used to find out the 'type' of a variable.

-   **Math helper methods:**
    
    -   Math helper methods provide power to manipulate data according to our need. 
    for eg Math.round(), Math.floor() etc.
        
        ```javascript
          Math.round(2.5); // 3
          Math.floor(2.4); // 2
          Math.ceil(2.4); // 3
          Math.random(); // 0.21329726661734782 - random number between 0 and 1
          Math.PI; //3.141592653589793
        
        ```
        
-   **Modulo and Power operators:**
    
    ```javascript
      const smarties = 20;
      const kids = 3;
      const eachKidGets = Math.floor(smarties/kids); // 6
      const leftSmarties = smarties % kids; // 2 - modulo operation
      
      const x = 2 ** 3; // 8 - power operation using power operator (**)
      // or
      const x = Math.pow(2,3); // 8 - power operation using Math.pow
    
    ```
    
-   Example
    
    0.1 + 0.2 // 0.30000000000000004
    

Why? [Explanation](http://0.30000000000000004.com/)

So, when working with money, don't store them as dollars and cents. Store all of the money in cents as you won't have to deal with fractions only whole nos. When need to display to user, just convert them back.

-   **Infinity and Negative Infinity:**

`typeof Infinity; // number`

`typeof -Infinity; // number`

-   **Not a Number (NaN):**

`10 / 'dog' // NaN`

`typeof NaN // number`
