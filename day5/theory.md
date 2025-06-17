# 📔 Day 5
## Arrays
* an array can store multiple values.
* Each value in an array has an index, and each index has a reference in a memory address.
*  Each value can be accessed by using their indexes. 

* An array is a collection of <b>different data types </b>which are ordered and changeable(modifiable).
 * An array allows storing duplicate elements and different data types. 
 * An array can be empty, or it may have different data type values.
 ## How to create an empty array
 It is very common to use const instead of let to declare an array variable. If you ar using const it means you do not use that variable name again.

1) Using Array constructor
```javascript
const array=Array()
console.log(array)
````
Output:
```` [] ````

2) Using square brackets([])
```javascript
const array=[]
console.log(array)
````
Output:
```` [] ````
## How to create an array with values
```javascript
const array=[0,3.14,6]
const barray=["lemon","banana"];
console.log(array.length)
console.log(array)
console.log(barray.length)
console.log(barray)
````
Output:
````
 3
[ 0, 3.14, 6 ]
2
[ 'lemon', 'banana' ] 
````

* Array can have items of different data types
```javascript
const array=[0,3.14,6, true,"lemon","banana"];
console.log(array.length)
console.log(array)

````
Output:
````
 6
[ 0, 3.14, 6, true, 'lemon', 'banana' ]
````
## Creating an array using split
```javascript
let a="javascript"
const r=a.split('')
console.log(r)
p='Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon'
q=p.split(',')
console.log(q)
````
Output:
````
[
  'j', 'a', 'v', 'a',
  's', 'c', 'r', 'i',
  'p', 't'
]
[
  'Facebook',
  ' Google',
  ' Microsoft',
  ' Apple',
  ' IBM',
  ' Oracle',
  ' Amazon'
]
````
## Accessing array items using index
```javascript
p='Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon'
q=p.split(',')
console.log(q[0])
```
Output:
```` 'Facebook' ````
# Modifying array element
```javascript
p='Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon'
q=p.split(',')
q[0]="Marvel"
console.log(q)
````
Output:
````
[
  'Marvel',
  ' Google',
  ' Microsoft',
  ' Apple',
  ' IBM',
  ' Oracle',
  ' Amazon'
]

````
## Methods to manipulate array
* Array
* length
* concat
* indexOf
*  slice
* splice 
*  join 
* toString
*  includes 
* lastIndexOf
*  isArray
* fill
*  push
* pop
* shift
*  unshift
## Array Constructor
```javascript
const array=Array(8)
console.log(array)
```
Output: ```` [ <8 empty items> ] ````
## Creating static values with fill
```javascript
const array=Array(8).fill('X')
console.log(array)
```
Output: ```` [
  'X', 'X', 'X',
  'X', 'X', 'X',
  'X', 'X'
] ````
## Concatenating array using concat
```javascript
const f = [1, 2, 3]
const s = [4, 5, 6]
const t =f.concat(s)

console.log(t) 
```
Output: ```` [ 1, 2, 3, 4, 5, 6 ]````
## Getting array length
```javascript
const f = [1, 2, 3]
const t =f.length
console.log(t) 
```
Output: ````  3 ````
## Getting index an element in arr array
```javascript
const f = [1, 2, 3]
console.log(f.indexOf(2)) 
```
Output: ````  1 ````
* Check an element if it exist in an array
```javascript
const f = [1, 2, 3]
console.log(f.indexOf(6)) 
```
Output: ````  -1 ````
* -1 represents element not present
## Getting last index of an element in array
```javascript
const f = [1, 2, 3,2]
console.log(f.lastIndexOf(2))
```
Output: ````  3````
## includes:
```javascript
const f = [1, 2, 3,2]
console.log(f.includes(2)) 
```
Output: ````  true````
## Checking array
Array.isArray:To check if the data type is an array
```javascript
const f = [1, 2, 3,2]
console.log(Array.isArray(f)) 
const fi=['facebook','walmart']
console.log(Array.isArray(fi)) 
```
Output: ````  true true````
## Converting array to string
```javascript
const f = [1, 2, 3,2]
console.log(f.toString()) 
```
Output: ````  1,2,3,2 ````
## Joining array elements
join: It is used to join the elements of the array, the argument we passed in the join method will be joined in the array and return as a string.
*  By default, it joins with a comma, but we can pass different string parameter which can be joined between the items.
```javascript
const f = [1, 2, 3,2]
console.log(f.join()) 
```
Output: ````  1,2,3,2 ````
## Slice array elements
Slice: To cut out a multiple items in range. It takes two parameters:starting and ending position. It doesn't include the ending position
```javascript
const f = [1, 2, 3,2]
console.log(f.slice(0,1))
console.log(f.slice(0,5)) 
```
Output: ````  [ 1 ]
[ 1, 2, 3, 2 ] ````
## Splice method in array
Splice: It takes three parameters:Starting position, number of times to be removed and number of items to be added.
```javascript
const numbers = [1, 2, 3, 4, 5]
  numbers.splice()
  console.log(numbers)                
  const numbe = [1, 2, 3, 4, 5]
    numbe.splice(0,1)
  console.log(numbe)           
  const n = [1, 2, 3, 4, 5, 6]
    n.splice(3, 3, 7, 8, 9)
  console.log(n.splice(3, 3, 7, 8, 9)) 
  ```
  Output ``` [ 1, 2, 3, 4, 5 ][ 2, 3, 4, 5 ] [7,8,9]```
   
* in 3rd one  [1, 2, 3, 7, 8, 9] //it removes three item and replace three items
## Adding item to an array using push
Push: adding item in the end. To add item to the end of an existing array we use the push method.
```javascript
const numbers = [1, 2, 3, 4, 5]
  numbers.push(7)
  console.log(numbers)                
  
  ```
  Output: ```` [ 1, 2, 3, 4, 5, 7 ]````
## Removing the end element using pop
pop: Removing item in the end.
```javascript
const numbers = [1, 2, 3, 4, 5,7]
  numbers.pop()
  console.log(numbers)                
  
  ```
  Output: ```` [ 1, 2, 3, 4, 5 ]````
  ## Removing an element from the beginning
shift: Removing one array element in the beginning of the array.
```javascript
const numbers = [1, 2, 3, 4, 5,7]
  numbers.shift()
  console.log(numbers)            
  ```
  Output:
  ```` [ 2, 3, 4, 5, 7 ] ````
  ## Add an element from the beginning
unshift: Adding array element in the beginning of the array.
```javascript
const numbers = [1, 2, 3, 4, 5,7]
  numbers.unshift(0)
  console.log(numbers)                
   ```
  Output:
  ```` [0,1, 2, 3, 4, 5, 7 ] ````
 ##  Reversing array order
reverse: reverse the order of an array.
```javascript
const numbers = [1, 2, 3, 4, 5,7]
  numbers.reverse()
  console.log(numbers)                
   ```
  Output:
  ```` [ 7, 5, 4, 3, 2, 1 ] ````
 ##  Sorting elements in array
 ```javascript
 const numbers = [1, 3,2,25, 4, 5,7]
  numbers.sort()
  console.log(numbers)                
  ```
  Output:
  ````
   [
  1, 2, 25, 3,
  4, 5,  7
]
````
## Array of arrays
 ```javascript
const numbers = [[1, 3,2],[25, 4, 5,7]]

  console.log(numbers) 
   ```
  Output:````[ [ 1, 3, 2 ], [ 25, 4, 5, 7 ]]````      

  * Completed day 5