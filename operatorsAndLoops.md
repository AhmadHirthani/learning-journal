## Comparison Operator
While we are programming we face many situation where we should decide what to do according to a specific condition. In JavaScript we have many types of these conditions such as the comparison operator. Using comparison operator result (true or false) we can decide what to do. In JavaScript we have many comparison operator such as
== to check equality in values between the and left side of the comparison.
!= the opposite of ==
=== to check equality in values and types between right and left side of the comparison.
!== the opposite of ===
< > <= <= to check that one side of the comparison is greater than the other.
<= >= to check that one side of the comparison is greater than or equal the other.

### Example
var pass = 50;
var score = 90;
var hasPassed = score >= pass;
var el = document.getElementByld('answer');
e1.textContent = 'Leve 1 passed:' + has Passed; 
The result will be (Level passed: true) 

## Logical Operator
Besides the comparison operator, we have the logical operator which is work in a logic manner to compine two statments or conditions and return true or false value.
&& called logical and. It returns true only if the the two conditions around it are true.
|| called logical or. It returns false only if the the two conditions around it are false.
! called not. It return the opposite of the statement.

### Example
var scorel = 8; 
var score2 = 8; 
var passl 6; 
var pass2 = 6; 
var passBoth = (scorel >= passl) && (score2 >= pass2);
var msg = 'Both rounds passed: ' + passBoth;
var el = document.getElementById( 'answer') ;
el.textContent = msg; 
The result will be (Both rounds passed:true)

## Loops
Loops are used in each programming language. It is very important because it facilitae a lot of tasks that will be more complec without loops. Using loops can increase reuseability and decrease the number of repeated code. In javaScript we have three types of loops, for, while and do while. For used when we know the boundries (start and end point) of the loop. While is used when we dont know the boundries of the loop but we know a condition that loop will stop when this condition achieved. So if the condition is true the loop will run until the condtion becomes false. In contrast of while, do while start executing the loop code for one time then check the condition, if the condition is true it will continue, if false it will stop.

### For loop example:
var scores= [24. 32, 17]; //Array of scores
var arraylength scores.l ength; // Items in array
var roundNumber = O; //Current round
var msg ''; //Message
var i ; // Counter
for (i = O; i < arraylength; i++) {
roundNumber = (i + l);
msg += 'Round ' + roundNumber + ' : ';
msg += scores[i] + '<br / >' ;
document .getElementByid( 'answer') .i nnerHTML msg; 
### The result will be:
Round 1: 24
Round 2: 32
Round 3: 17

### While loop example:
var i = l ;
var msg = ' ' ;
II Set counter to 1
II Message
II Store 5 times tabl e in a variable
while (i < 10) {
msg += i + ' x 5 = ' + (i * 5) + '<br I>';
i++;
document .getEl ementByid( ' answer') . innerHTML = msg; 
### The result will be:
lx5=5
2 x s = 10
3 x 5 = 15
4 x 5 = 20
s x s = 25
6 x s = 30
7 x 5 = 35
8 x s = 40
9 x 5 = 45

### Do while loop example:
var i = l;
var msg ;
do {
msg += i + ' x 5 = ' + (i * 5) + '<br I>' ;s
i++;
} while ( i < 1) ;
document.getElementByld('answer').innerHTML = msg; 
### The result will be:
lx5=5





