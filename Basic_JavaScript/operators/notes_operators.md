Control flow statements
Conditional statement 

if - condition
===============
let i=-6
-> 1 if condition
if(i>0){
//when condition is true then only if block will be execution


-> 2 if-else condition
=======================
let i=-6

if(i>0){
// if condition will false
else{
//it will go to else block}}

3 if
let age =20
->else if ->else

if(age<18){ // false
console. log( "no voter id")}
else if(age>=18){ // true
console. log( "voter id")}
else{
console. log( "default ld")



SwitchCase 
The switch statement is used to perform different actions based on different conditic
as an alternative to multiple if.. .else if. ..else blocks.
Syntax 

switch (expression) {
case valuel
// Code block
break;
// once condition satisfied end execution
case value2
//body
break;
...
default
// Default code block


Looping Statements
==================
for Statement The for loop in JavaScript is used to iterate over a range
of values or to
repeat a block of code a certain number of times. It consists of three parts
initialization, condition, and iteration expression . The loop continues as long as
the condition is true.

Initialization -> Executed once before the loop starts.
Condition -> Checked before every iteration; loop runs as long as it's true.
Update -> Executed after each loop iteration.

Example
for( initialization; condition ; iteration) {}