# 💻 Exercises:Day 6

## Exercises: Level 1
1) Iterate 0 to 10 using for loop, do the same using while and do while loop
```javascript
for (let i=0;i<=10;i++){
    console.log(i)
}
let i=0;
while(i<=10){
    console.log(i);
    i++;
}i=0;
do{
    console.log(i);
    i++;
}while(i<=10)
```
Output:````
0
1
2
3
4
5
6
7
8
9
10
0
1
2
3
4
5
6
7
8
9
10
0
1
2
3
4
5
6
7
8
9
10````
2) Iterate 10 to 0 using for loop, do the same using while and do while loop
```javascript
for (let i=10;i>=0;i--){
    console.log(i)
}
let i=10;
while(i>=10){
    console.log(i);
    i--;
}i=10;
do{
    console.log(i);
    i--;
}while(i>=0)
```
Output:````
10
9
8
7
6
5
4
3
2
1
0
10
10
9
8
7
6
5
4
3
2
1
0````

3) Iterate 0 to n using for loop
```javascript
n=+prompt("enter a number :")
for (let i=0;i<=n;i++){
    console.log(i)
}

```
Output:````
enter a number 5:
0
1
2
3
4
5````

4) Write a loop that makes the following pattern using console.log():
 ```
    #
    ##
    ###
    ####
    #####
    ######
    #######
 ```
```javascript
 n=+prompt("enter value of n: ")
for(let i=1;i<=n;i++){let row=''
    for(let j=1;j<=i;j++){
        row+='#'
    }console.log(row)
}
```
Output:
enter value of n: 5 
```
    #
    ##
    ###
    ####
    #####
    ######
    #######
 ```
5) Use loop to print the following pattern:
````
0 x 0 = 0
1 x 1 = 1
2 x 2 = 4
3 x 3 = 9
4 x 4 = 16
5 x 5 = 25
6 x 6 = 36
7 x 7 = 49
8 x 8 = 64
9 x 9 = 81
10 x 10 = 100
````
```javascript
n=+prompt("enter value of n: ")

    for(let j=1;j<=n;j++){
     console.log(n+"X"+j+"="+n*j);

}
```
Output:
````enter value of n: 10
10X1=10
10X2=20
10X3=30
10X4=40
10X5=50
10X6=60
10X7=70
10X8=80
10X9=90
10X10=100 
````
6) Using loop print the following pattern
````
 i    i^2   i^3
 0    0     0
 1    1     1
 2    4     8
 3    9     27
 4    16    64
 5    25    125
 6    36    216
 7    49    343
 8    64    512
 9    81    729
 10   100   1000

 ````
 
 ```javascript
n=+prompt("enter value of n: ")

    for(let j=1;j<=n;j++){
     console.log(j,j*j,j*j*j);
}
```


Output:
````
enter value of n: 10
1 1 1
2 4 8
3 9 27
4 16 64
5 25 125
6 36 216
7 49 343
8 64 512
9 81 729
10 100 1000
````
7) Use for loop to iterate from 0 to 100 and print only even numbers
```javascript
n=+prompt("enter value of n: ")
let s=0;
    for(let j=0;j<=n;j+=2){
     console.log(j);
    }
```
Output```` enter value of n: 100
0
2
4
6
8
10
12
14
16
18
20
22
24
26
28
30
32
34
36
38
40
42
44
46
48
50
52
54
56
58
60
62
64
66
68
70
72
74
76
78
80
82
84
86
88
90
92
94
96
98 100 ````

8) Use for loop to iterate from 0 to 100 and print only odd numbers
```javascript
n=+prompt("enter value of n: ")
let s=0;
    for(let j=1;j<=n;j+=2){
     console.log(j);
    }
```
Output:```` 1
3
5
7
9
11
13
15
17
19
21
23
25
27
29
31
33
35
37
39
41
43
45
47
49
51
53
55
57
59
61
63
65
67
69
71
73
75
77
79
81
83
85
87
89
91
93
95
97
99 ````

9) Use for loop to iterate from 0 to 100 and print only prime numbers
```javascript
n=+prompt("enter value of n: ")
let s=0;
let c=0;
    for(let j=2;j<=n;j++){
      for(let i=2;i<j;i++){
          if(j%i==0){
              c=1;
              break;
          }
      }if(c==0){
     console.log(j);}c=0;}
```
Output:```` enter value of n: 100
2
3
5
7
11
13
17
19
23
29
31
37
41
43
47
53
59
61
67
71
73
79
83
89
97 ````

10) Use for loop to iterate from 0 to 100 and print the sum of all numbers.

The sum of all numbers from 0 to 100 is 5050.
```javascript
n=+prompt("enter value of n: ")
let s=0;
let c=0;
    for(let j=1;j<=n;j++){
      s+=j;
      }
     console.log(s);
```
Output:
````
enter value of n: 100
5050
 ````
11) Use for loop to iterate from 0 to 100 and print the sum of all evens and the sum of all odds.
```javascript
n=+prompt("enter value of n: ")
let s=0;
let c=0;
    for(let j=1;j<=n;j+=2){
      s+=j;
      }for(let j=0;j<=n;j+=2){
      c+=j;
      }
     console.log(s,c);
```
Output:
````
enter value of n: 100
2500 2550
 ````
The sum of all evens from 0 to 100 is 2550. And the sum of all odds from 0 to 100 is 2500.
Use for loop to iterate from 0 to 100 and print the sum of all evens and the sum of all odds. Print sum of evens and sum of odds as array

  [2550, 2500]
```javascript
n=+prompt("enter value of n: ")
let s=0;
let c=0;
    for(let j=1;j<=n;j+=2){
      s+=j;
      }for(let j=0;j<=n;j+=2){
      c+=j;
      }
     const num=[]
      num.push(s)
      num.push(c)
     console.log(num);

```
Output:
````
enter value of n: 100
[ 2500, 2550 ]
 ````