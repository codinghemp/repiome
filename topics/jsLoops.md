## Loops

[Back to Table of Contents](../README.md/#Table-of-Contents)

[Mozilla Loops Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

### For Loops

A for loop is used to iterate over an array or an object. <br>
The for loop has three parts: the initializationExpression, the conditionExpression, and the incrementExpression.
```javascript
for (let i = 0; i < array.length; i++) {
  // code to be executed
}
```

[Back to Table of Contents](../README.md/#Table-of-Contents)

### For In Loops
Looping through properties of an object
 ```javascript
const object = { key1: "value1", key2: "value2" };
for (const key in object) {
    console.log(key + ": " + object[key]);
}
```

[Back to Table of Contents](../README.md/#Table-of-Contents)

### For Of Loops
Looping through elements of an array or a string
 ```javascript
const array = [1, 2, 3, 4, 5];
for (const element of array) {
    console.log(element);
}
```

[Back to Table of Contents](../README.md/#Table-of-Contents)

### For Each Loops
A For Each loop is a method that allows you to iterate through and perform a function on each element of an array.
 ```javascript
array.forEach(function(element) {
    // code to be executed for each element
});
```

[Back to Table of Contents](../README.md/#Table-of-Contents)

### While Loops
 A while loop is used to execute a block of code repeatedly as long as a given condition is true.
 ```javascript
 while (condition) {
  // code to be executed
}
```

[Back to Table of Contents](../README.md/#Table-of-Contents)

### Do While Loops
Executing code as long as a certain condition is true
 ```javascript
while (condition) {
    // code to be executed
}
```