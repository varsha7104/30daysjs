# Booleans
A boolean data type represents one of the two values:true or false
```javascript
let y=true
let u;
u=4>3
console.log(y,u);
```
 Output:````true true````
 ## Truthy values
1) All numbers(positive and negative) are truthy except zero
2) All strings are truthy except an empty string ('')
3) The boolean true

## Falsy values
1) 0
2) 0n
3) null
4) undefined
5) NaN
6) the boolean false
7) '', "", ``, empty string
## Undefined
If we declare a variable and if we do not assign a value, If the function is not returning the value. it will be undefined .
```javascript
let y;
console.log(y)
```
Output: ````undefined````
## Null:
```javascript
let empty = null
console.log(empty)
```
Output: ````null````
# Operators
## Assignment operators:
An equal sign in JavaScript is an assignment operator. It uses to assign a variable.
```javascript
let firstName = 'Asabeneh'
let country = 'Finland'
console.log(firstName=country)
```
Output: ````Finland````
```javascript
let a=10
let b=20
console.log(a+=b)
console.log(a-=b)
console.log(a*=b)
console.log(a/=b)
console.log(a%=b)
console.log(a**=b)
```
Output: ````30
10
200
10
10
100000000000000000000````
## Arithmetic Operators
Arithmetic operators are mathematical operators.

1) Addition(+): a + b
2) Subtraction(-): a - b
3) Multiplication(*): a * b
4) Division(/): a / b
5) Modulus(%): a % b
6) Exponential(**): a ** b
```javascript
let a=10
let b=20

let s=(a+b)
let w=(a-b)
let m=(a*b)
let d=(a/b)
console.log(s,w,m,d)
```
Output: ```` 30 -10 200 0.5 ````
## Comparison Operators
```javascript
let a=10
let b=20
console.log(a==b)
console.log(a!=b)
console.log(a>b)
console.log(a<b)
console.log(a>=b)
console.log(a<=b)
```
Output:
````
a==b: false
a!=b:true
a>b:false
a<b:true
a>=b:false
a<=b:true
````
## Logical Operators
```javascript
const r=4>3 && 5>4
console.log(r)
const y=4>3 || 4>5
console.log(y)
let c=!(7>5)
console.log(c)
```
Output:
````
true
true
false
````
## Increment Operator
 The increment could be pre or post increment.
Pre-increment
```javascript
let count = 0
console.log(++count)       
console.log(count)        
```
Output:````1 1 ````

Post-increment
```javascript
let count = 0
console.log(count++)      
console.log(count)          
```
Output:````0 1````
## Decrement Operator
The decrement could be pre or post decrement. 

Pre-decrement
```javascript
let count = 0
console.log(--count) 
console.log(count) 
```
Output: ````-1 -1````

Post-decrement
```javascript
let count = 0
console.log(count--) 
console.log(count)   
```
Output: ````0 -1````
## Ternary Operators
Ternary operator allows to write a condition. 
```javascript
let count = 0
count? console.log("rain"):
console.log("wind")
```
Output: ````wind````
## Window Methods
## Window alert() method
 alert() method displays an alert box with a specified message and an OK button. It is a builtin method and it takes on argument
 ```javascript
 alert('Welcome to 30DaysOfJavaScript')
 ```
 Output: ````Welcome to 30DaysOfJavaScript````
 ## Window prompt() method
The window prompt methods display a prompt box with an input on your browser to take input values and the input data can be stored in a variable. 
The prompt() method takes two arguments. The second argument is optional.

prompt('required text', 'optional text')
 ```javascript
let number = prompt('Enter number', 'number goes here')
console.log(number)
```
Output:
````
Enter number12
12
````
## Window confirm() method
The confirm() method displays a dialog box with a specified message, along with an OK and a Cancel button. used to ask permission from a user to execute something. Window confirm() takes a string as an argument. Clicking the OK yields true value, whereas clicking the Cancel button yields false value.
```javascript 
const agree = confirm('Are you sure you like to delete? ')
console.log(agree)
```
Output:
````Are you sure you like to delete?  yes or no ````
## Date Object
JavaScript Date Object. The object we create using Date object provides many methods to work with date and time.<br>
getFullYear(), getMonth(), getDate(), getDay(), getHours(), getMinutes, getSeconds(), getMilliseconds(), getTime(), getDay()

## Date time Object

Creating a time object
Once we create time object. The time object will provide information about time. Let us create a time object
```javascript 
const now = new Date()
console.log(now) 
```
Output: ````index.html:11 Sun Jun 15 2025 22:15:26 GMT+0530 (India Standard Time)````

## Getting full year
```javascript 
const now = new Date()
console.log(now.getFullYear()) 
```
Output:
````2025````

## Getting month
```javascript 
const now = new Date()
console.log(now.getMonth())
```
Output:
````5````

## Getting date
```javascript 
const now = new Date()
console.log(now.getDate()) 
```
Output:
````15````

## Getting day
```javascript 
const now = new Date()
console.log(now.getDay()) // 6, because the day is Saturday which is the 7th day
//  Sunday is 0, Monday is 1 and Saturday is 6
// Getting the weekday as a number (0-6)
```
Output:
````0````
## Getting hours
```javascript 
const now = new Date()
console.log(now.getHours()) // 0, because the time is 00:56:41
```
Output:
````22````

## Getting minutes
```javascript 
const now = new Date()
console.log(now.getMinutes()) // 56, because the time is 00:56:41
```
Output: ````24 ````

## Getting seconds
```javascript 
const now = new Date()
console.log(now.getSeconds()) 
```
Output: ````34 ````

# Getting time

## Using getTime()
```javascript 
const now = new Date() 
console.log(now.getTime()) 
```
Output:
````1750006715819````
```javascript 
const allSeconds = Date.now() 
console.log(allSeconds) 
```
Output:
````1750006715819````
```javascript 
const timeInSeconds = new Date().getTime()
console.log(allSeconds == timeInSeconds)
```
Output: ````true ````
