# Technical-paper

## Functions in JavaScript

### What are they and why do we use them :
Block of code statements which can be used anywhere in the project to execute the same task by calling the function name. To be precise, imagine you are woking in a project wrote some code for a task. 

To perform the same task again somewhere in the project writing again the same code taking so much of effort and memory space which is not recommeded, here where functions are useful to get the things done. We can use them with or without parameters.

### syntax :


function sample() { <br>
&nbsp; &nbsp;  // code  <br>
}

## 1.This is a function without partameters.

function sample() { <br>
&nbsp; &nbsp; // code  <br>
}


##### here, <br>

Function name : **sample** <br>
Function keyword : **function**<br>
Parenthesis : **()**

## 2.Function with parameters.

function sample(a,b) {<br>
&nbsp; &nbsp; // code <br>
}

#### eg :

function square(num) { <br>
  &nbsp; &nbsp; console.log(num*num) <br>
 }
 
## 3.calling a function :

Whenever we want to call a function writing its name along with the parameters is enough to get the desired results.

square(3) <br>
\>> **9**

This way, whenever the function is called the resulted will be printed.

## Real-life examples :

In an ATM transction we do observe the greeting messages before and after the transaction. Here, the greet message functions are used to make the life simpler.

#### example:

1. function greet() { <br>
&nbsp; &nbsp; console.log('Thanks for using this ATM') <br>
}

2. function transaction(num) { <br> 
&nbsp; &nbsp; console.log(\`Your transaction of Rs.${num} is successful.\`} <br>
&nbsp; &nbsp; greet() <br>
}

Here, we make a transaction of random amount and let's see the result that gets printed.

transaction(1000)

\>> **Your transaction of Rs. 1000 is successful.** <br>
\>> **Thanks for using this ATM.**

The thanks message is printed everytime when there's a transaction. Actually, the greet code is written once but is called everytime of the transaction as we have seen above. This is how they are useful in our daily life.

## Use of 'return' keyword :

When the function is called the output is printed on the screen. Another way to print the output is to store the result in a variable for later use and printing that one.

##### for eg.

function cube(num) { <br>
&nbsp; &nbsp; return num\**3 <br>
}

const ans = cube(5)

We have called the function but it doesn't prints any output rather returns the output which is stored in the variable **ans**. The main purpose of the return keyword is to get the output and to perform some operations on them or for later usage.

console.log(ans) <br>
console.log(ans*10)

\>> **125** <br>
\>> **1250**

This will be printed out, when we log the **ans** on the console.

## Another way to declare functions :

There's another way to declare a function, where we don't use the function name. Have a look at the following function.

const cude = function(num) => { <br>
&nbsp; &nbsp; return num\**3 <br>
}

We have just assigned the function to the variable 'cube', where the returned output will be stored in this variable, and asually it can be printed by logging the variable on the console.

const sol = cube(3) <br>
console.log(sol)

\>> 27

## Arrow functions :

Without usinng both the 'function keyword' and 'function name', we have a function to use called as 'Arrow function'. It looks as simple as the previous functions, just with some changes in the syntax.

const sq_root = num => { num\*(0.5) }

If observed carefully, we haven't used the parenthesis and return keyword. Its because if we have only one parameter, then no need to use the parenthesis. And also if the code statement can be completed in a single line, it will be returned automatically without return keyword.


const area = (l,b) => { <br>
&nbsp; &nbsp; let ar = l*b <br>
&nbsp; &nbsp; return ar <br>
}

As the paramteres are more than one and have multiple block of lines of codes we have used both parenthesis and return keyword.















  
 
 






