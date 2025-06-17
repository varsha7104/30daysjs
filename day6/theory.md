# Loops

In programming languages to carry out repetitive task we use different kinds of loops. The following examples are the commonly used loops in JavaScript and other programming languages.

## for Loop
```
// For loop structure
for(initialization, condition, increment/decrement){
  // code goes here
}
```
```javascript
for(let i = 0; i <= 5; i++){
  console.log(i)
}
```
Output:```` 0 1 2 3 4 5 ````
```javascript
for(let i = 5; i >= 0; i--){
  console.log(i)
}
```
Output:```` 5 4 3 2 1 0 ````
```javascript
const countries = ['Finland', 'Sweden', 'Denmark', 'Norway', 'Iceland']
const newArr = []
for(let i = 0; i < countries.length; i++){
  newArr.push(countries[i].toUpperCase())
}
```
Output:```` ["FINLAND", "SWEDEN", "DENMARK", "NORWAY", "ICELAND"] ````

* Creating a new array based on the existing array
```javascript
const numbers = [1, 2, 3, 4, 5]
const newArr = []
let sum = 0
for(let i = 0; i < numbers.length; i++){
  newArr.push( numbers[i] ** 2)

}

console.log(newArr) 
```
Output:```` [1, 4, 9, 16, 25] ````


## while loop
```javascript
let i = 0
while (i <= 5) {
  console.log(i)
  i++
}
```

Output:```` 0 1 2 3 4 5````
## do while loop
```javascript
let i = 0
do {
  console.log(i)
  i++
} while (i <= 5)

```

Output:```` 0 1 2 3 4 5 ````
## for of loop
We use for of loop for arrays. It is very hand way to iterate through an array if we are not interested in the index of each element in the array.
```
for (const element of arr) {
  // code goes here
}
```
```javascript
const numbers = [1, 2, 3, 4, 5]

for (const num of numbers) {
  console.log(num)
}
```

Output:````  1 2 3 4 5 ````

## break
Break is used to interrupt a loop.
```javascript
for(let i = 0; i <= 5; i++){
  if(i == 3){
    break
  }
  console.log(i)
}
```
Output ```` 0 1 2 ````

The above code stops if 3 found in the iteration process.

## continue
We use the keyword continue to skip a certain iterations.
```javascript
for(let i = 0; i <= 5; i++){
  if(i == 3){
    continue
  }
  console.log(i)
}
```
Output ```` 0 1 2  4 5````

* completed day 6
