# 💻 Exercise
## Exercise: Level 1
1)Declare an empty array;
```javascript
const array=[]
console.log(array)
````
Output:
```` [] ````

2) Declare an array with more than 5 
number of elements
```javascript
const numbers = [1, 3,2,25, 4, 5,7]

  console.log(numbers)   
  ```

Output:
```` [[
  1, 3, 2, 25,
  4, 5, 7
]] 
````

3) Find the length of your array
```javascript
const numbers = [1, 3,2,25, 4, 5,7]

  console.log(numbers.length)   
  ```

Output:
```` 
7
````

4) Get the first item, the middle item and the last item of the array
```javascript
const numbers = [1, 3,2,25, 4, 5,7]

  console.log(numbers[0])   
   console.log(numbers[3])  
    console.log(numbers[numbers.length-1])  
  ```

Output:
```` 
1
25
7
````
5) Declare an array called mixedDataTypes, put different data types in the array and find the length of the array. The array size should be greater than 5
```javascript
const numbers = [1, 3,2,"va", true, 5,7]
 
    console.log(numbers.length)  
  ```

Output:
```` 
7
````
6) Declare an array variable name itCompanies and assign initial values Facebook, Google, Microsoft, Apple, IBM, Oracle and Amazon
```javascript
const company=['Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]
  ```

7) Print the array using console.log()
```javascript
const company=['Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]
    console.log(company)  
 ```   


Output:
````       
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
8) Print the number of companies in the array

```javascript
const company=['Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]
    console.log(company.length)  
 ```   


Output:
````       
7
 ````
9) Print the first company, middle and last company
Print out each company
```javascript
const company=['Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]
    console.log(company[0])   
   console.log(company[3])  
    console.log(company[company.length-1]) 
 ```   


Output:
````       
Facebook
 Apple
 Amazon
 ````

10) Change each company name to uppercase one by one and print them out


```javascript
const company=['Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]
    console.log(company[0].toUpperCase())   
 ``` 
Output:
````       
FACEBOOK
 ````
11) Print the array like as a sentence: Facebook, Google, Microsoft, Apple, IBM,Oracle and Amazon are big IT companies.
```javascript
const company=['Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]
console.log(company.join(',') + " big company");
 ``` 
Output:
````       
Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon big company
 ````
 12) Check if a certain company exists in the itCompanies array. If it exist return the company else return a company is not found
```javascript
 const company=['Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]
console.log(company.includes('Facebook') );
 ``` 
Output:
````   
true
````
13) Filter out companies which have more than one 'o' without the filter method
```javascript
const company = ['Facebook', 'Google', 'Microsoft', 'Apple', 'IBM', 'Oracle', 'Amazon'];
const result = [];

for (let i = 0; i < company.length; i++) {
    let name = company[i];
    let count = 0;
    
    for (let j = 0; j < name.length; j++) {
        if (name[j] === 'o' || name[j] === 'O') {
            count++;
        }
    }

    if (count <= 1) {
        result.push(name);
    }
}

console.log(result);
```
Output:
````   
[ 'Facebook', 'Apple', 'IBM', 'Oracle', 'Amazon' ]
````
14) Sort the array using sort() method
```javascript
const company=['Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]
company.sort()
console.log(company );
  ```
Output:
````   
[
  ' Amazon',
  ' Apple',
  ' Google',
  ' IBM',
  ' Microsoft',
  ' Oracle',
  'Facebook'
]
````
15) Reverse the array using reverse() method
```javascript
const company=['Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]
company.reverse()
console.log(company );
  ```
Output:
````   
[
  ' Amazon',
  ' Oracle',
  ' IBM',
  ' Apple',
  ' Microsoft',
  ' Google',
  'Facebook'
]
````
16) Slice out the first 3 companies from the array
```javascript
const company=['Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]

console.log(company.slice(0,3) );
```
Output:
````   
[ 'Facebook', ' Google', ' Microsoft' ]
````
17) Slice out the last 3 companies from the array
```javascript
const company=['Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]

console.log(company.slice(-3) );
```
Output:
````   
[ ' IBM', ' Oracle', ' Amazon' ]
````
18) Slice out the middle IT company or companies from the array
```javascript
const company = ['Facebook', 'Google', 'Microsoft', 'Apple', 'IBM', 'Oracle', 'Amazon'];
const midIndex = Math.floor(company.length / 2);
const middle = company.slice(midIndex, midIndex + 1);
console.log(middle);
```
Output:
````   
[ 'Apple' ]
````
19) Remove the first IT company from the array
```javascript
const company=['Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]
company.shift()
console.log(company );
```
Output:
````   
[ ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]
````
20) Remove the
 middle IT company or companies from the array
  ```javascript
 let company = ['Facebook', 'Google', 'Microsoft', 'Apple', 'IBM', 'Oracle', 'Amazon'];

if (company.length % 2 === 1) {
  // Odd length: remove 1 middle element
  const mid = Math.floor(company.length / 2);
  company.splice(mid, 1);
} else {
  // Even length: remove 2 middle elements
  const mid = company.length / 2;
  company.splice(mid - 1, 2);
}

console.log(company);
```
Output:
````
[ 'Facebook', 'Google', 'Microsoft', 'IBM', 'Oracle', 'Amazon' ]
````
 21) Remove the last IT company from the array
 ```javascript
const company=['Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]
company.pop()
console.log(company );
  ```
Output:
````   
[ 'Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle' ]
````

22) Remove all IT companies
 ```javascript
const company=['Facebook', ' Google', ' Microsoft', ' Apple', ' IBM', ' Oracle', ' Amazon' ]
company.length=0
console.log(company );
  ```
Output:
````   
[]
````
## Exercise 2 (Medium):
