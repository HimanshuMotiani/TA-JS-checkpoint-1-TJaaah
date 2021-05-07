1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
Ans - "return" will send the result where function is called, and console.log() will print there itself in console 

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
Ans- For first = sum(1,2), it will store the returned value and result will be 3 in "first", whereas second=sum(1,2), "second will not have a value in it as it not returning anything just printing it."

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
//36 as third parameter is not defined so it will take first two parameter for calculation
4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
yes, we can store let add= sum(a,b){return a+b;}, but we can call this function by only calling the "add(1,2)".
5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
function sayHello(name){
  return `Hello ${name}`;
}
sayHello("Arya");
6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
"Hello, John" it will take name for upper variable Or it will be undefined as it is not stored in variable
7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); //John

showMessage(); // Output 2 "Hello, John" it will take name for upper variable Or it will be undefined as it is not stored in variable

alert(userName); // Output 3 //John
```

8. What is a Anonymous Function give example of three functions.
Function which does not have a name.
let sum = function(a,b){return a+b; }
let sum = (a,b) =>{return a+b;}
9. Can function declaration be a Anonymous Function? Explain
No,but we can convert into function expression(let a = function b(){}) , and the into anonymous by let a = function(){}; 
10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```

update..()
delete..()
evaluate..()
transfor..()
save..()
add..()

