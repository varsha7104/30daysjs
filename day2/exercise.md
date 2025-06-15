# Exercises:
## Level 1
1) Declare a variable named challenge and assign it to an initial value '30 Days Of JavaScript'.
```javascript
let num="30 days of JavaScript"
```
2) Print the string on the browser console using console.log()
```javascript
let num="30 days of JavaScript"
console.log(num)
```
Output: ```` 30 days of JavaScript ````
<br>
3) Print the length of the string on the browser console using console.log()
```javascript
let num="30 days of JavaScript"
console.log(num.length)
```
Output: ```` 21  ````
<br>
4) Change all the string characters to capital letters using toUpperCase() method
```javascript
let num="30 days of JavaScript"
console.log(num.toUpperCase())
```
Output: ```` 30 DAYS OF JAVASCRIPT  ````
<br>
5) Change all the string characters to lowercase letters using toLowerCase() method
```javascript
let num="30 days of JavaScript"
console.log(num.toLowerCase())
```
Output: ```` 30 days of javascript  ````
<br>
6) Cut (slice) out the first word of the string using substr() or substring() method
```javascript
let num="30 days of JavaScript"
console.log(num.substr(0,2))
console.log(num.substr(0,3))
```
Output: 
```` 
30
30 
 ````
 7) Slice out the phrase Days Of JavaScript from 30 Days Of JavaScript.
 ```javascript
let num="30 days of JavaScript"
console.log(num.substr( 3,4))
```
Output: ```` days````
<br>
8)Check if the string contains a word Script using includes() method
```javascript
let num="30 days of JavaScript"
console.log(num.includes('Script'))
```
Output: ```` true````
<br>
9) Split the string into an array using split() method
```javascript
let num="30 days of JavaScript"
console.log(num.split(' '))
```
Output: ```` [ '30', 'days', 'of', 'JavaScript' ]````
<br>
10) Split the string 30 Days Of JavaScript at the space using split() method
```javascript
let num="30 days of JavaScript"
console.log(num.split(' '))
```
Output: ```` [ '30', 'days', 'of', 'JavaScript' ]````
<br>
11) 'Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon' split the string at the comma and change it to an array.
```javascript
s='Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon' 
console.log(s.split(','))
```
Output: ```` [
  'Facebook',
  ' Google',
  ' Microsoft',
  ' Apple',
  ' IBM',
  ' Oracle',
  ' Amazon'
]````
<br>
12) Change 30 Days Of JavaScript to 30 Days Of Python using replace() method.
```javascript
let num="30 days of JavaScript"
console.log(num.replace('JavaScript',"Python"))
```
Output: ```` 30 days of Python````

<br>
13) What is character at index 15 in '30 Days Of JavaScript' string? Use charAt() method.

```javascript
let num="30 days of JavaScript"
console.log(num.charAt(15))
```
Output: ```` S ````

<br>
14) What is the character code of J in '30 Days Of JavaScript' string using charCodeAt()

```javascript
let num="30 days of JavaScript"
console.log(num.charCodeAt('J'))
```
Output: ```` 51 ````

<br>
15) Use indexOf to determine the position of the first occurrence of a in 30 Days Of JavaScript

```javascript
let num="30 days of JavaScript"
console.log(num.indexOf('a'))
```
Output: ```` 4 ````

<br>
16) Use lastIndexOf to determine the position of the last occurrence of a in 30 Days Of JavaScript.

```javascript
let num="30 days of JavaScript"
console.log(num.indexOf('a'))
```
Output: ```` 14 ````
<br>
17) Use indexOf to find the position of the first occurrence of the word because in the following sentence:'You cannot end a sentence with because because because is a conjunction'
```javascript
let num="'You cannot end a sentence with because because because is a conjunction'"
console.log(num.indexOf('because'))
```
Output: ```` 32 ````
<br>
17) Use lastIndexOf to find the position of the last occurrence of the word because in the following sentence:'You cannot end a sentence with because because because is a conjunction'
```javascript
let num="'You cannot end a sentence with because because because is a conjunction'"
console.log(num.lastIndexOf('because'))
```
Output: ```` 48 ````
<br>
19) Use search to find the position of the first occurrence of the word because in the following sentence:'You cannot end a sentence with because because because is a conjunction'
```javascript
let num="'You cannot end a sentence with because because because is a conjunction'"
console.log(num.search('because'))
```
Output: ```` 32 ````
<br>
20) Use trim() to remove any trailing whitespace at the beginning and the end of a string.E.g ' 30 Days Of JavaScript '.
```javascript
let num="           sentence with because because because is a conjunction'"
console.log(num.trim('  '))
```
Output: ```` sentence with because because because is a conjunction' ````
<br>
21) Use startsWith() method with the string 30 Days Of JavaScript and make the result true
```javascript
let num="30 days of JavaScript"
console.log(num.startsWith('30'))
```
Output: ```` true ````
<br>
22) Use endsWith() method with the string 30 Days Of JavaScript and make the result true
```javascript
let num="30 days of JavaScript"
console.log(num.endsWith('ript'))
```
Output: ```` true ````
<br>
23)Use match() method to find all the a’s in 30 Days Of JavaScript
```javascript
let num="30 days of JavaScript"
console.log(num.match('a'))
```
Output: 
```` 
[ 'a', index: 4, input: '30 days of JavaScript', groups: undefined ]
````
<br>
24) Use concat() and merge '30 Days of' and 'JavaScript' to a single string, '30 Days Of JavaScript'

```javascript
let num="30 days",k= " of JavaScript"
console.log(num.concat(k))

```
Output: ```` 30 days of JavaScript ````
<br>
25) Use repeat() method to print 30 Days Of JavaScript 2 times
```javascript
let num="30 days of JavaScript"
console.log(num.repeat(2))


```
Output: ```` 30 days of JavaScript 
30 days of JavaScript````

## LEVEL 2
1) Using console.log() print out the following statement:

The quote 'There is no exercise better for the heart than reaching down and lifting people up.' by John Holmes teaches us to help one another.
```javascript
let num="The quote \'There is no exercise better for the heart than reaching down and lifting people up.\' by John Holmes teaches us to help one another."
console.log(num)

```
Output:
 ```` 
 The quote 'There is no exercise better for the heart than reaching down and lifting people up.' by John Holmes teaches us to help one another.
````
<br>
2) Using console.log() print out the following quote by Mother Teresa:

"Love is not patronizing and charity isn't about pity, it is about love. Charity and love are the same -- with charity you give love, so don't just give money but reach out your hand instead."
```javascript
let num="Love is not patronizing and charity isn't about pity, it is about love. Charity and love are the same -- with charity you give love, so don't just give money but reach out your hand instead."
console.log(num)
```
Output:
 ```` 
 Love is not patronizing and charity isn't about pity, it is about love. Charity and love are the same -- with charity you give love, so don't just give money but reach out your hand instead.

````
<br>
3) Check if typeof '10' is exactly equal to 10. If not make it exactly equal.

```javascript
let n='10',s=10
console.log(typeof(n))
console.log(typeof(s))
console.log(+(n))
console.log(typeof(n),typeof(s))
```
Output:
 ```` 
 string
number
10
string number
````
<br>
4) Check if parseFloat('9.8') is equal to 10 if not make it exactly equal with 10.

```javascript
let n=10.4,s=10
let o=parseInt(n)
console.log(o==s)
```
Output: ````  true````
<br>
5)  Check if 'on' is found in both python and jargon
```javascript
let n="python",m="jargon"
console.log(n.includes("on"))
console.log(m.includes("on"))

```
Output: ````  true
true ````
6)I hope this course is not full of jargon. Check if jargon is in the sentence.
```javascript
let n="I hope this course is not full of jargon"
console.log(n.includes(" jargon"))
```
Output: ````  true```` <br>
7) Generate a random number between 0 and 100 inclusively.
```javascript
console.log(Math.random()*101)
```
Output: ````   38.12868126789345````
<br>
8) Generate a random number between 50 and 100 inclusively.
```javascript
console.log(Math.floor(Math.random() * 51) + 50); 
```
Output: ````  68````
<br>
9) Generate a random number between 0 and 255 inclusively.
```javascript
console.log(Math.floor(Math.random() * 256)  ); 
```
Output: ```` 242````
10) Access the 'JavaScript' string characters using a random number.

```javascript
const str = "JavaScript";
const i= Math.floor(Math.random() * str.length);
const r = str[i];
console.log(`Random character: ${r}`);
```
Output: ```` r````
<br>
11) Use console.log() and escape characters to print the following pattern.

1 1 1 1 1<br>
2 1 2 4 8 <br>
3 1 3 9 27 <br>
4 1 4 16 64 <br>
5 1 5 25 125<br>
```javascript
console.log("1 1 1 1 1\n2 1 2 4 8\n3 1 3 9 27 \n4 1 4 16 64 \n5 1 5 25 125");
```
Output: 
```` 
1 1 1 1 1
2 1 2 4 8
3 1 3 9 27 
4 1 4 16 64 
5 1 5 25 125
````
12) Use substr to slice out the phrase because because because from the following sentence:'You cannot end a sentence with because because because is a conjunction'
```javascript
let s='You cannot end a sentence with because because because is a conjunction'
console.log(s.substr(30,24))
```
Output: ```` because because because ````
# Level 3 (Hard):
1) 'Love is the best thing in this world. Some found their love and some are still looking for their love.' Count the number of word love in this sentence.
```javascript
const s = "Love is the best thing in this world. Some found their love and some are still looking for their love.";
const matches = s.match(/love/gi); 
const count = matches ? matches.length : 0;

console.log(`'love' appears ${count} times`);
```
Output: ```` love' appears 3 times ````
2) se match() to count the number of all because in the following sentence:'You cannot end a sentence with because because because is a conjunction'
```javascript
const s = "You cannot end a sentence with because because because is a conjunction";
const matches = s.match(/because/gi); 
const count = matches ? matches.length : 0;

console.log(`'because' appears ${count} times`);
```
Output: ```` 'because' appears 3 times ````
3) Clean the following text and find the most frequent word (hint, use replace and regular expressions).

    const sentence = '%I $am@% a %tea@cher%, &and& I lo%#ve %te@a@ching%;. The@re $is no@th@ing; &as& mo@re rewarding as educa@ting &and& @emp%o@weri@ng peo@ple. ;I found tea@ching m%o@re interesting tha@n any ot#her %jo@bs. %Do@es thi%s mo@tiv#ate yo@u to be a tea@cher!? %Th#is 30#Days&OfJavaScript &is al@so $the $resu@lt of &love& of tea&ching'
    
Code:
 ```javascript
const sentence = `%I $am@% a %tea@cher%, &and& I lo%#ve %te@a@ching%;. The@re $is no@th@ing; &as& mo@re rewarding as educa@ting &and& @emp%o@weri@ng peo@ple. ;I found tea@ching m%o@re interesting tha@n any ot#her %jo@bs. %Do@es thi%s mo@tiv#ate yo@u to be a tea@cher!? %Th#is 30#Days&OfJavaScript &is al@so $the $resu@lt of &love& of tea&ching`;

const cleanText = sentence.replace(/[^a-zA-Z\s]/g, "").toLowerCase();

const words = cleanText.split(/\s+/);

const counts = {};

words.forEach(word => {
  counts[word] = (counts[word] || 0) + 1;
});

const mostFrequent = Object.entries(counts).reduce((a, b) => a[1] > b[1] ? a : b);

console.log(`Most frequent word: '${mostFrequent[0]}' (${mostFrequent[1]} times)`);

```
Output: 
````  
Most frequent word: 'teaching' (3 times)
  ````
<br>
4) Calculate the total annual income of the person by extracting the numbers from the following text. 'He earns 5000 euro from salary per month, 10000 euro annual bonus, 15000 euro online courses per month.'

```javascript
const text = 'He earns 5000 euro from salary per month, 10000 euro annual bonus, 15000 euro online courses per month.';

const numbers = text.match(/\d+/g).map(Number); 
const i = (numbers[0] + numbers[2]) * 12 + numbers[1];
console.log(`Total annual income: ${i} euro`);

```
Output: ```` Total annual income: 250000 euro ````
****
🎉 CONGRATULATIONS ! 🎉