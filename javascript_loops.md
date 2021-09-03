#   IT IS TIME TO BRING YOU IN TO THE LOOP
#### you are finally going to make me a god
#   WHAT?! NO, I WAS JUST MAKING A JOKE ABOUT HOW YOU CAN USE THE WORDS OF POWER IN A SIMPLE AND REITERATING WAY
#### oh, the loop. i see it now.

## [Forms of Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#while_statement)
- for loops
``` javascript
for ([intialExpression];[conditionExpression]; [incrementExpression]);
    statement
```
``` javascript
for (i = 0; i <= x; i++>){
    console.log(i)
}
```
  - Build a structure to tell the computer how long to run.
    - `i=0` sets an index
    - `i<=x` is a conditional that continues until it is false
    - `i++` is to increment the index value
    - **the conditon test is *after* the intial expression**

- while loop
``` javascript
while(condition){
    statment
}
```
``` javascript
let n = 0;
let x = 0;
while (n < 3) {
    n++;
    x += n;
}
```
  - **the condition test occurs *before* the statement**
  -`let n = 0; let x =0` are a setting of variables
  -`n<3` is the conditional statement
  -`n++; x += n;` are the interative statement
  -`break` will terminate the innermost enclosing `while` or `for`

[The Temple](intro.md)