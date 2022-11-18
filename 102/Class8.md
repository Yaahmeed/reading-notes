# Class 8 Notes

## Operators and Loops

### Expressions and Operators

* An expression is a calid unit of code that resolces to a value.
* 2 types of expressions: those that have side effects (such as assigning values) and those that purely evaluate

The expression x = 42 is an example of assigning value

* Uses the = operator to assign the calue of 42 to the variable x.
The expression 7 + 2 is an example of evaluate
Uses the + operator to ADD 7 and 2 together to produce a value of 9.
If not part of a bigger construct, (ie: a variable declaration like let x = 7 + 2) the result will be immediately discarded.

* All complex expressions are joined by operators such as = and +

### Operators in this chapter

* Assignment
* Comparison
* Arithmetic
* Bitwise
* Logical
* Biglnt
* String
* Conditional (ternary)
* Comma
* Unary
* Relational

### Loops and Iteration

* Loops offer a quick and easy way to do something repeatedly.
* Loops repeat an action some number of times.
J

### JS Statements for loops

* for
loop repeats until a specified condition evaluates to false
for ([initialExpression]);
[conditionExpression];
[incrementExpression]) statement

* do...while
statement repeats until a specified condition evaluates to false
do
statement
while (condition)

* while
statement executes statements as long as a specified condition evaluates to true

while (condition)
statement

* labeled
provides a statement with an identifier that lets you refer to it elsewhere in your program. You can use a label to identify a loop, then use the break or continue statements to indicate whether a program should interrupt the loop or continue its execution

label:
statement

* break
use to terminate a loop, switch, or in conjunction with a labeled statement

break; break label;

* continue
can be used to restart a while, do-while, for, or label statement

continue
continue label;

* for...in
iterates a specified variable over all the properties of an object. For each distinct property, JS executes the specified statements

for (variable in object)
statement

* for...of
creates a loop iterating over iterable objects, invoking a custom iteration hook with statements to be executed for the value of eack distinct property

for (variable of object);
statement
