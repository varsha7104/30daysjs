# 💻 Exercises
## Exercises: Level 1
1) Get user input using prompt(“Enter your age:”). If user is 18 or older , give feedback:'You are old enough to drive' but if not 18 give another feedback stating to wait for the number of years he needs to turn 18.
```
Enter your age: 30
You are old enough to drive.

Enter your age:15
You are left with 3 years to drive.
```

Code:
```javascript
let num=+prompt("Enter the age ");
num<18? console.log(`You are left with ${18-num} years to drive.`
):
console.log("You are old enough to drive. ")
```
Output:
````
Enter the age 15
You are left with 3 years to drive.
````
2) Compare the values of myAge and yourAge using if … else. Based on the comparison and log the result to console stating who is older (me or you). Use prompt(“Enter your age:”) to get the age as input.
Enter your age: 30
You are 5 years older than me.

Code:
```javascript
let num=+prompt("Enter the age ");
let j=+prompt("enter your age")
num<j? console.log(`You are left with ${j-num} years to reach my age.`
):
console.log("You are greater my age ")
```
Output:
````
Enter the age 25
enter your age 34
You are left with 9 years to reach my age.
````
3) If a is greater than b return 'a is greater than b' else 'a is less than b'. Try to implement it in to ways

using if else
ternary operator.
```
  let a = 4
  let b = 3
  4 is greater than 3
  ```
  Code:
  
```javascript
let num=+prompt("Enter the a ");
let j=+prompt("enter your b")
num<j? console.log(`${num} is less than ${j}.`
):
console.log(`${num} is greater than ${j}.`
)
if(num<j){
  console.log(`${num} is less than ${j}.`
)  
}
else {
   console.log(`${num} is greater than ${j}.`
) 
}
```
Output:
````
Enter the a 4
enter your b5
4 is less than 5.
4 is less than 5.
````
4) Even numbers are divisible by 2 and the remainder is zero. How do you check, if a number is even or not using JavaScript?
```
Enter a number: 2
2 is an even number

Enter a number: 9
9 is is an odd number.
```
Code:
```javascript
let num=+prompt("Enter the a ");
if(num%2==0){
  console.log(`${num} is even.`
)  
}
else {
   console.log(`${num} is odd.`
) 
}
```
Output:
````
Enter the a 4
4 is even.
````
## Exercise 2 (Level- Medium):
1) Write a code which can give grades to students according to theirs scores:
```
80-100, A
70-89, B
60-69, C
50-59, D
0-49, F
````

Code:
``` javascript
let num=+prompt("Enter the a ");
if(num>=80 && num<=100){
  console.log(`${num} :A.`)  
}else if(num>=70 && num<=79){
  console.log(`${num} :B.`)  
}
else if(num>=60 && num<=69){
  console.log(`${num} :C.`)  
}
else if(num>=50 && num<=59){
  console.log(`${num} :D.`)  
}
else {
   console.log(`${num} F`) 
}
```
Output:
````
Enter the a 84
84 :A.
````
2) Check if the season is Autumn, Winter, Spring or Summer. If the user input is :
```
September, October or November, the season is Autumn.
December, January or February, the season is Winter.
March, April or May, the season is Spring
June, July or August, the season is Summer
````

Code:
``` javascript
let num=prompt("Enter the month ");
if(num=="September" ||  num=="October" || num=="November" ){
  console.log(`the season is Autumn.`)  
}else if(num=="December"  || num== "January" ||num== "February") {
  console.log(`the season is Winter.`)  
}
else if(num=="March"  || num== "April"  || num== "May"){
  console.log(`the season is Spring`)  
}
else {
   console.log(`the season is Summer`) 
}
```
Output:
````
Enter the month September
the season is Autumn.
````
3) Check if a day is weekend day or a working day. Your script will take day as an input.
 
 ```
  What is the day  today? Saturday
  Saturday is a weekend.

  What is the day today? saturDaY
  Saturday is a weekend.

  What is the day today? Friday
  Friday is a working day.

  What is the day today? FrIDAy
  Friday is a working day.
  ```
Code:
``` javascript
  let num=prompt("Enter the month ");
num=num.toLowerCase()
if(num==="saturday" ||  num==="sunday" ){
  console.log(`the weekday is weekend.`)  
}
else {
   console.log(`the season is Summer`) 
}
```
Output:
````
Enter the month sunDay
the weekday is weekend.
````
## Level 3(Hard)
1) Write a program which tells the number of days in a month.
```
  Enter a month: January
  January has 31 days.

  Enter a month: JANUARY
  January has 31 day

  Enter a month: February
  February has 28 days.

  Enter a month: FEbruary
  February has 28 days.
  ```
Write a program which tells the number of days in a month, now consider leap year.
Code:
``` javascript
  let num=prompt("Enter the month ");
num=num.toLowerCase()
if(num=="september" ||    num=="november"  || num== "april"  || num=="june"){
  console.log(`the month is 30 days`)  
}else if(num=="december"  || num== "january" || num=="march"  || num== "may" || num=="july"|| num=="august" || num=="october"){
  console.log(`the month is 31`)  
}
else {
   console.log(`the month is 28  days`) 
}
```
Output:
````
Enter the month APRIL
the month is 30 days
````