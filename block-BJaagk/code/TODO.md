1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

let percentage = function(marks,total){
   return (marks * 100) / total;
}
 let getPercentage = (marks,total) => {
   return (marks * 100) / total;
 }
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
//Declaration
Declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
``` 
//Expression


```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```
//Expression
```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
//Expression
```js
let percentage = (marks, total) => (marks * 100) / total;
```
//Expression

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
 // The Function Expression allows us to create an anonymous function that doesn't have any function name 
4. Why is a function call an expression in JavaScript?
 // 
A function call expression is used to execute a specified function with the provided arguments.
5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer
five = add; // Answer
five = five(10, 11); // Answer
five = function () {
  return 'Hello';
}; // Answer
```

6. What is the difference between function definition and function call? Explain with an example.
// they mean when you write all the code for your function. At that point the function just sits there doing nothing. call is when you tell the JavaScript interpreter to run the code in your function.

7. What is the similarities between function definition and function call?

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid
```

9. What is higher order function explain with an example.
// A Higher-Order function is a function that receives a function as an argument or returns the function as output. For example, Array. prototype.map 

10. Explain what is callback function. Why you can pass a function inside a function?
