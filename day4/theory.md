# 📔 Day 4
## Conditionals
1) make decisions based on different conditions.
2)  By default , statements in JS script executed sequentially from top to bottom.
3) If the processing logic require so, the sequential flow of execution can be altered in two ways:

a) Conditional execution: a block of one or more statements will be executed if a certain expression is true

b) Repetitive execution: a block of one or more statements will be repetitively executed as long as a certain expression is true. 

Conditions can be implementing using the following ways:
they are
* if
* if else
* if else if else
* switch
* ternary operator
## If
 "if"  is to used check if a condition is true and to execute the block code. 

```
if (condition) {
 //this part of code runs for truthy condition
} 
```
```javascript
let num=3;
if(num>0){
    console.log(`${num} is greater number `)
}
```
Output:
```` 3 is greater number ````
<br>
```javascript
let num;
if(num){
    console.log(`${num} is greater number `)
}
```
Output:
```` 3 is greater number ````

## If Else
If condition is true the first block will be executed, if not the else condition will be executed.

```
if (condition) {
  // this part of code runs for truthy condition
} else {
  // this part of code runs for false condition
}
```
```javascript
let num=-3;
if(num>0){
    console.log(`${num} is greater number than 0 `)
}
else {
    console.log(`${num} is less number than 0 `)
}
```
Output:
````-3 is less number than 0  ````

# If Else if Else
We make decisions not by checking one or two conditions instead we make decisions based on multiple conditions. 

As similar to our daily life, programming is also full of conditions. We use else if when we have multiple conditions.
```
// syntax
if (condition) {
     // code
} else if (condition) {
   // code
} else {
    //  code

}
```
```javascript
let num=-3;
if(num>0){
    console.log(`${num} is greater number than 0 `)
}else if(num==0){
      console.log(`${num} is equal to 0 `)
}
else {
    console.log(`${num} is less number than 0 `)
}
```
Output:
````-3 is less number than 0  ````
## Switch
1) Switch is an alternative for if else if else else. 
2) The switch statement starts with a switch keyword followed by a parenthesis and code block.
 3) Case block runs if the value in the switch statement parenthesis matches with the case value.
 4)  The break statement is to terminate execution 
 5) The default block runs if all the cases don't satisfy the condition.
 ```javascript
let num=-3;
switch(true){
    case num>0:
    console.log(`${num} is greater number than 0 `)
    break;
 case (num==0):
      console.log(`${num} is equal to 0 `)
      break;

case (num<0) :
    console.log(`${num} is less number than 0 `)
    break;
}
```
Output:
````-3 is less number than 0  ````
## Ternary Operators
 ```javascript
let num=-3;
num<0? console.log("-3 is less number than 0 "):
console.log("-3 is greater  number than 0 ")
```
Output:
````-3 is less number than 0  ````

* Completed my day 4
