1. Using loops take 10 inputs from user and find the average of all the numbers.
let avg = 0
for(i = 0 ; i<10;i++){
val = +prompt("enter value")
avg = avg + val;
}
avg = avg/10
console.log(avg);
2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```
  "error" println is not defined,otherwise hi three time in console.log(),

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
function getEvenSum(max){
  let sum = 0; 
for(i = 0 ;i<=max; i++){
  if(i % 2 == 0){
    sum = sum + i;
  }
}
return sum;
}
getEvenSum(10)

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
function getOddSum(max){
  let sum = 0; 
for(i = 0 ;i<=max; i++){
  if(i % 2 != 0){
    sum = sum + i;
  }
}
return sum;
}
getOddSum(10)

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.
let num= 1234;
let prod =1;
while(num>0){
let rem= num%10
 num = num - rem;
prod = prod * rem;
num = num /10;

}
console.log(prod);

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // output 'Bigger than 5'
check(1); // output 'Smaller than 5'
check(5); // output 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // what will be the output  'You are arya'
getOutput('John'); // what will be the output 'You are john'
getOutput(); // what will be the output 'Who are you'
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // what will be the output 'You are arya'
getOutput('John'); // what will be the output You are john'
getOutput(); // what will be the output  'Who are you'
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
yes,Once return executes it terminates the program, as per different condition we can add multiple return and we can also do like this 
function sayHi() {
  function add() {
    return 21;
  }
  return add();
}

or
function test(battery) {
  if (val > 20) {
    return "good";
  }

  if (val < 10) {
    return "ok";
  }

  return false;
}
10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
for - when we know the number of iterations
while - when we do not know the iteration. 
