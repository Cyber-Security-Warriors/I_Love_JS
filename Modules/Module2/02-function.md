# Custom Function in JS

- Custom functions are function which can be *created* & *define*.
- Every function in the JS is **Function** object.

### Defining Function

Function Definition also known as Function Declaration.

` Function Definition `

```javascript
function myFunctn(){
// function body
}
```

### Calling Function

Function Calling helps to get result from defined function.

` Function Calling `

```javascript
// running or calling function

myFunctn();
```

Example : 

```javascript
function calculateBill(){
    console.log("Running Calculate Bill");
    const total = 100*2;
    return total;
    }
  
calculateBill(); // return 200
console.log(total); // throw not defined error because total is defined inside the function
const myTotal = calculateBill(); // store return value of function in new variable myTotal
console.log(`this is your total $${myTotal}`); // this is your total $200
```

[Click Here For Next](03-parameter-argument.md)
