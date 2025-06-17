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