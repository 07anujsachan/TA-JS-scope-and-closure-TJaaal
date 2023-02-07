1. What does thread of execution means in JavaScript?

It goes through it line by line, and does each of the line of code, they call this the thread of execution.

2. Where the JavaScript code gets executed?

Whenever the JavaScript engine receives a script file, it first creates a default Execution Context known as the Global Execution Context (GEC) . The GEC is the base/default Execution Context where all JavaScript code that is not inside of a function gets executed

3. What does context means in Global Execution Context?

The global execution context is created when a JavaScript script first starts to run, and it represents the global scope in JavaScript.

4. When do you create a global execution context.

The global execution context is created when a JavaScript script first starts to run, and it represents the global scope in JavaScript.

5. Execution context consists of what all things?

The Execution Context contains the code that's currently running, and everything that aids in its execution. 

6. What are the different types of execution context?
There are two kinds of Execution Context in JavaScript:
Global Execution Context (GEC)
Function Execution Context (FEC)
7. When global and function execution context gets created?
The global execution context is created when a JavaScript script first starts to run, and it represents the global scope in JavaScript. 
8. Function execution gets created during function execution or while declaring a function.


9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)