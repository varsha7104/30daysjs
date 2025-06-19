This is day 7
## 📔 Day 7
## Functions


1) A function is a reusable block of code or programming statements designed to perform a certain task.
2)  A function is declared by a function key word followed by a name, followed by parentheses () with a parameter  called with argument. 
3) A function can also take a default parameter. 
4) To store a data to a function, a function has to return certain data types. To get the value we call or invoke a function. 

Function makes code:

* clean and easy to read
* reusable
* easy to test

A function can be declared or created in couple of ways:

* Declaration function
* Expression function
* Anonymous function
* Arrow function
## Function Declaration
```javascript
//declaring a function without a parameter
function functionName() {
  // code goes here
}
functionName() // calling function by its name and with parentheses
```
## Function without a parameter and return
Function can be declared without a parameter.

```javascript
function square() {
  let num = 2
  let sq = num * num
  console.log(sq)
}

square() 
```

## Function returning value
Function can also return values, if a function does not return values the value of the function is undefined.
```javascript
function printFullName (){
      let firstName = 'Asabeneh'
      let lastName = 'Yetayeh'
      let space = ' '
      let fullName = firstName + space + lastName
      return fullName
}
console.log(printFullName())
  ```
  Output:
  ````Asabeneh  Yetayeh````
## Function with a parameter
In a function we can pass different data types(number, string, boolean, object, function) as a parameter.
```javascript

function functionName(parm1) {
  
}
functionName(parm1) 
```

## Function with two parameters
```javascript
// function with two parameters
function functionName(parm1, parm2) {
  //code goes her
}
functionName(parm1, parm2) 
```
```javascript
function sumTwoNumbers(numOne, numTwo) {
  let sum = numOne + numTwo
  console.log(sum)
}
sumTwoNumbers(10, 20) // calling functions
```
```javascript
## Function with many parameters

function functionName(parm1, parm2, parm3,...){

}
functionName(parm1,parm2,parm3,...) 
```


