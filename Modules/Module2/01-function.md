# Functions in Javascript

*Functions* are one of the fundamental building blocks in JS. 
In this section we will talk about **Built in** functions in JS. 
These global functions—functions which are called globally rather than on an object—directly return their results to the caller.
[Source MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects)  

for eg: 
```javascript
console.log('Hi!'); // print a log message
```
cosole.log() returns *undefined* because it only perform the task which is printing the log message. 

***Note*** : Some functions not return any value So these functions return **undefined**.

*Built in functions example : *

```javascript
Math.max(20,10) // 20
parseFloat('22012.567'); // 22012.567
parseInt('3097.789'); // 3097
Date(); // "Sun Dec 29 2019 18:18:56 GMT+0530 (India Standard Time)"
Date.now() // Time period of earth in millisecond 1577623779716
scrollTo(0,660); // undefined
```

`scrollTo(); function return undefined like console.log() because while executing this function will scroll your page according to passed parameter which is  x,y coordinate for scrollTo function.`

Learn more about [Standard Built in Objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects).

[Click Here for Next](02-function.md)
