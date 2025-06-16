# 💻 Day 3: Exercises
## Exercises: Level 1
1) Declare firstName, lastName, country, city, age, isMarried, year variable and assign value to it and use the typeof operator to check different data types.
```javascript
 let firstName="varsha"
 let lastName="jonnapalli"
 let country="india"
 let city="vizag"
 let age=18.4
 let isMarried= false
 let year= 2024
 console.log(typeof(firstName),typeof(lastName))
 console.log(typeof(country),typeof(city))
 console.log(typeof(age),typeof(isMarried))
 console.log(typeof(year))
 ```
 Output:
 ```` 
 string string
string string
number boolean
number
```` 
 <br>
2) Check if type of '10' is equal to 10

```javascript
 console.log(typeof('10')==typeof(10))
 ```
 Output: ```` false ````
 <br>
 3) Check if parseInt('9.8') is equal to 10
 ```javascript
  console.log(typeof( parseInt('9.8') )==typeof(10))
  ```
 Output: ```` true ````
  <br>
4) Boolean value is either true or false.
 ```javascript
 let f=false 
 console.log(typeof(f))
   ```

  Output: ````boolean````
   <br>
  5) Write three JavaScript statement which provide truthy value.
   ```javascript
  let y=true
let u="varsha"
let d=3
d?console.log("true"):console.log("false")
y?console.log("true"):console.log("false")
u?console.log("true"):console.log("false")
 ```

  Output: ````true
true
true````
<br>
6) Write three JavaScript statement which provide falsy value.
 ```javascript
  let y=false
let u=""
let d=NaN
let a=0
let s=0n
let f=null
let t=undefined
d?console.log("true"):console.log("false")
y?console.log("true"):console.log("false")
u?console.log("true"):console.log("false")
a?console.log("true"):console.log("false")
s?console.log("true"):console.log("false")
f?console.log("true"):console.log("false")
t?console.log("true"):console.log("false")
 ```

  Output: ````false
false
false
false
false
false
false````
<br>
7) Figure out the result of the following comparison expression first without using console.log(). After you decide the result confirm it using console.log()
 ```javascript
 let a=10
let b=45
c=a>b
console.log(c)
 ```

  Output: ````false````
  <br>
  8) 4 > 3
   ```javascript
 console.log(4 > 3)
 ```

  Output: ````true````
  <br>
9) 4 >= 3
 ```javascript
 console.log(4 >= 3)
 ```

  Output: ````true````
  <br>
10) 4 < 3
 ```javascript
 console.log(4 < 3)
 ```

  Output: ````false````
  <br>
11)4 <= 3
 ```javascript
 console.log(4 <= 3)
 ```

  Output: ````false````
  <br>
12) 4 == 4
 ```javascript
 console.log(4==4)
 ```

  Output: ````true````
  <br>
13) 4 === 4
 ```javascript
 console.log(4 ===4)
 ```

  Output: ````true````
  <br>
14) 4 != 4
 ```javascript
 console.log(4 !=4)
 ```

  Output: ````false````
  <br>
15) 4 !== 4
 ```javascript
 console.log(4 !== 3)
 ```

  Output: ````false````
  <br>

16)4 != '4'
 ```javascript
 console.log(4 !='4')
 ```

  Output: ````true````
  <br>
17) 4 == '4'
 ```javascript
 console.log(4 == '4')
 ```

  Output: ````false````
  <br>
18) 4 === '4'
 ```javascript
 console.log(4 ==='4')
 ```

  Output: ````true````
  <br>
  19) Find the length of python and jargon and make a falsy comparison statement.
  ```javascript
let y="python",k="jargon"
console.log(y.length!=k.length)
 ```

  Output: ````false````
  <br>
20) Figure out the result of the following expressions first without using console.log(). After you decide the result confirm it by using console.log()
```javascript
console.log(4 > 3 && 10 < 12)
 ```

  Output: ````true````
  <br>
  21)4 > 3 && 10 < 12
  ```javascript
console.log(4 > 3 && 10 < 12)
 ```

  Output: ````true````
  <br>
22)4 > 3 && 10 > 12
```javascript
console.log(4 > 3 && 10 > 12)
 ```

  Output: ````false````
  <br>
23) 4 > 3 || 10 < 12
```javascript
console.log(4 > 3 || 10 < 12)
 ```

  Output: ````true````
  <br>
24) 4 > 3 || 10 > 12
```javascript
console.log(4 > 3 && 10 > 12)
 ```

  Output: ````true````
  <br>
25)!(4 > 3)
```javascript
console.log(!(4 > 3 ))
 ```

  Output: ````false````
  <br>
26)!(4 < 3)
```javascript
console.log(!(4< 3) )
 ```

  Output: ````true````
  <br>
27) !(false)
```javascript
console.log(!(false))
 ```
Output: ````true````
  <br>
28) !(4 > 3 && 10 < 12)
```javascript
console.log(!(4 > 3 && 10 < 12))
 ```

  Output: ````false````
  <br>
29) !(4 > 3 && 10 > 12)
```javascript
console.log(!(4 > 3 && 10 > 12))
 ```

  Output: ````true````
  <br>
30) !(4 === '4')
```javascript
console.log(!(4==='4))
 ```

  Output: ````false````
  <br>
  31) There is no 'on' in both dragon and python
```javascript
let y="python",k="dragon"
console.log(y.includes("on") && k.includes("on"))
```

  Output: ````true````
  <br>
32)Use the Date object to do the following activities

```javascript
const now= new Date()
console.log(now)
```

  Output: ````2025-06-16T01:00:33.306Z````
  <br>
33) What is the year today?
```javascript
const now= new Date()
console.log(now.getYear())
```

  Output: ````2025````
  <br>
34)What is the month today as a number?
```javascript
const now= new Date()
console.log(now.getMonth())
```

  Output: ````5````
  <br>
35) What is the date today?
```javascript
const now= new Date()
console.log(now.getDate())
```

  Output: ````16````
  <br>
36)What is the day today as a number?
```javascript
const now= new Date()
console.log(now.getDay())
```

  Output: ````16````
  <br>
37) What is the hours now?
```javascript
const now= new Date()
console.log(now.getHours())
```

  Output: ````6````
  <br>
38) What is the minutes now?
```javascript
const now= new Date()
console.log(now.getMinutes())
```

  Output: ````35````
  <br>
39) Find out the numbers of seconds elapsed from January 1, 1970 to now.

* January 1, 1970 is the starting point of time in Unix-based systems (called the Unix Epoch).
```javascript
const now= new Date()
console.log(now.getSeconds())
```

  Output: ````52````
  <br>
  ## Exercises: Level- 2
 1) Write a script that prompt the user to enter base and height of the triangle and calculate an area of a triangle (area = 0.5 x b x h).

Enter base: 20<br>
Enter height: 10<br>
The area of the triangle is 100
```javascript
let b=prompt("enter the base: ")
let h=prompt("enter the height: ")
console.log("area",0.5*b*h)

```

  Output: 
  ````
  enter the base: 4
enter the height: 3
area 6
````
  <br>
  2) Write a script that prompt the user to enter side a, side b, and side c of the triangle and and calculate the perimeter of triangle (perimeter = a + b + c)

Enter side a: 5<br>
Enter side b: 4<br>
Enter side c: 3<br>
The perimeter of the triangle is 12
```javascript
let a=+prompt("enter a: ")
let b=+prompt("enter b: ")
let c=+prompt("enter c: ")
console.log("perimeter",a+b+c)

```

  Output: 
  ````
  enter a: 5
enter b: 4
enter c: 3
perimeter 12
````
3) Get length and width using prompt and calculate an area of rectangle

 (area = length x width  )<br>
 (perimeter = 2 x (length + width))
 ```javascript
 let l=+prompt("enter a: ")
let b=+prompt("enter b: ")
console.log("area",l*b)
console.log("perimeter",2*(l+b))

```

  Output: 
  ````
 enter a: 5
enter b: 4
area 20
perimeter 18
````
4) Get radius using prompt and calculate the area of a circle (area = pi x r x r) and circumference of a circle(c = 2 x pi x r) where pi = 3.14.
```javascript
let l=+prompt("enter r: ")
let pi = 3.14
console.log("area",pi*l*l)
console.log("circumference",2*(l*pi))

```

  Output: 
  ````
  enter r: 49
area 7539.14
circumference 307.72
````
<br>
5) Calculate the slope, x-intercept and y-intercept of y = 2x -2

```javascript

let l=prompt("enter in the format y = ax +b: ")
console.log("slope",l[4])
console.log("y-intercept",l[8])
console.log("x-intercept",(+(l[8])/(+l[4]))) //(b/a)

```

  Output: 
  ````
  enter in the format y = ax +b: y = 2x -2
slope 2
y-intercept 2
x-intercept 1
````
<br>
6) Slope is m = (y2-y1)/(x2-x1). Find the slope between point (2, 2) and point(6,10)

```javascript
let x1=+prompt("enter in the x1: ")
let y1=+prompt("enter in the y1: ")
let x2=+prompt("enter in the x2: ")
let y2=+prompt("enter in the y2: ")

console.log("slope",((y2-y1)/(x2-x1))) 
```

  Output: 
  ````
  enter in the x1: 2
enter in the y1: 2
enter in the x2: 6
enter in the y2: 10
slope 2
````
7) Compare the slope of above two questions.

```javascript
let x1=+prompt("enter in the x1: ")
let y1=+prompt("enter in the y1: ")
let x2=+prompt("enter in the x2: ")
let y2=+prompt("enter in the y2: ")
let l=prompt("enter in the format y = ax +b: ")
console.log("slope",l[4])
console.log("y-intercept",l[8])
let y=(+(l[8])/(+l[4]))//1
let u=((y2-y1)/(x2-x1))//2
console.log(y<u)

 
```

  Output: 
  ````
  enter in the x1: 2
enter in the y1: 2
enter in the x2: 6
enter in the y2: 10
enter in the format y = ax +b: y = 2x -2
slope 2
y-intercept 2
true
````
8) Calculate the value of y (y = x2 + 6x + 9). Try to use different x values and figure out at what x value y is 0.
```javascript
let x=+prompt("enter in the x1: ")

console.log("yvalue",x*x+6*x+9)
console.log("root",-3)
```
 Output: 
  ````
  enter in the x1: -3
yvalue 0
root -3
````
9) Writ a script that prompt a user to enter hours and rate per hour. Calculate pay of the person?

Enter hours: 40
Enter rate per hour: 28
Your weekly earning is 1120
```javascript
let x=+prompt("enter in the x1: ")
let y=+prompt("enter in the x1: ")
console.log("yvalue",x*y)
```
 Output: 
  ````
  enter in the x1: 40
enter in the x1: 28
yvalue 1120
````
10) If the length of your name is greater than 7 say, your name is long else say your name is short.
```javascript
let x=prompt("enter in the x1: ")
x.length>7?console.log("long"):
console.log("short")
```
 Output: 
  ````
 short
````
11) Compare your first name length and your family name length and you should get this output.

let firstName = 'Asabeneh'
let lastName = 'Yetayeh'
Your first name, Asabeneh is longer than your family name, Yetayeh
```javascript
let x=prompt("enter in the x1: ")
let y=prompt("enter in the x1: ")
x.length>y.length?console.log("Your first name,$ {x} is longer than your family name, ${y}"):
console.log("Your first name, $ {x} is shorter than your family name, `${y}")
```
 Output: 
  ````
 enter in the x1: varsha
enter in the x1: jonnapalli
Your first name, $ {x} is shorter than your family name, `${y}

````
12) Declare two variables myAge and yourAge and assign them initial values and myAge and yourAge.

let myAge = 250
let yourAge = 25
I am 225 years older than you.
```javascript
let x=+prompt("enter in the x age : ")
let y=+prompt("enter in the y age: ")
x>y?console.log("my age,$ {x} is longer than your age ${y}"):
console.log("my fage, $ {x} is shorter than your age, `${y}")
```
 Output: 
  ````
 enter in the x age : 25
enter in the y age: 45
my fage, $ {x} is shorter than your age, `${y}

````