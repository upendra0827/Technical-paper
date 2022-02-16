# Technical-paper

## Functions in JavaScript

### What are they and why do we use them :

Block of code statements which can be used anywhere in the project to execute the same task by calling the function name. To be precise, Imagine you are woking in a project wrote some code for a task. What if you want to use the code for 5 times ? We simply write the code again or we make a **for** loop. But, if we want to repeat it for 100 times or 1000 times, each time at a different place of the code ?

Writing the code again and again is not recommended as it takes much effort, time and memory space. Using a for loop too not recommended as it gives the output all at a specific place. To get the things done, here we use the functions. Whenever we want the code to execute the task maybe with or without parameters, we simply call the function by its name. That's it the code gets executed everytime.

### syntax :

```
function sample() { 
  // code  
}
```
## 1. Function without partameters.
```
function sample() { 
    // code  
}
```

##### here, <br>

Function name : **sample** <br>
Function keyword : **function**<br>
Parenthesis : **()**

## 2. Function with parameters.
```
function sample(a,b) {
  // code 
}
```
#### eg :
```
function square(num) { 
  console.log(num*num) 
 }
 ```
## 3. Calling a function :

Whenever we want to call a function writing its name along with the parameters is enough to get the desired results.
```
square(3) 
>> 9
```
This way, whenever the function is called the resulted will be printed.

## Real-life examples :

In an ATM transction we do observe the greeting messages before and after the transaction. Here, the greet message functions are used to make the life simpler.

#### example:
```
1. function greet() { 
      console.log('Thanks for using this ATM') 
}

2. function transaction(num) {
          console.log(`Your transaction of Rs.${num} is successful.`} 
          greet() 
}
```
Here, we make a transaction of random amount and let's see the result that gets printed.
```
transaction(1000)
```

```
>> Your transaction of Rs. 1000 is successful.
>> Thanks for using this ATM.
```

The thanks message is printed everytime when there's a transaction. Actually, the greet code is written once but is called everytime of the transaction as we have seen above. This is how they are useful in our daily life.

## Use of 'return' keyword :

When the function is called the output is printed on the screen. Another way to print the output is to store the result in a variable for later use and printing that one.

##### for eg.
```
function cube(num) { 
    return num**3 
}
```

```
const ans = cube(5)
```

We have called the function but it doesn't prints any output rather returns the output which is stored in the variable **ans**. The main purpose of the return keyword is to get the output and to perform some operations on them or for later usage.

```
console.log(ans) 
console.log(ans*10)
```

```
>> 125 
>> 1250
```


This will be printed out, when we log the **ans** on the console.

## Another way to declare functions :

There's another way to declare a function, where we don't use the function name. Have a look at the following function.
```
const cude = function(num) { 
    return num**3 
}
```
We have just assigned the function to the variable 'cube', where the returned output will be stored in this variable, and asually it can be printed by logging the variable on the console.

```
const sol = cube(3)
console.log(sol)
```

```
>> 27
```


## Arrow functions :

Without usinng both the 'function keyword' and 'function name', we have a function to use called as 'Arrow function'. It looks as simple as the previous functions, just with some changes in the syntax.
```
const sq_root = num => { num**(0.5) }
```
If observed carefully, we haven't used the parenthesis and return keyword. Its because if we have only one parameter, then no need to use the parenthesis. And also if the code statement can be completed in a single line, it will be returned automatically without return keyword.

```
const area = (l,b) => {
    let ar = l*b 
    return ar 
}
```
As the paramteres are more than one and have multiple block of lines of codes we have used both parenthesis and return keyword.















  
 
 






