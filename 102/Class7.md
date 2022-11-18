# Class 7 Notes

## Programming with JavaScript

### Control flow

* Control flow is the order in which the computer executes statements in a script.
* A typical script in JS includes many control structures including: conditionals, loops, and functions.
* Control flow means that when you read a script, you must, not only, read from start to finish, but also look at program structure and how it affects order of execution.

### JS Functions

* A block of code designed to perform a particular task.
* Function syntax: function is defined with the function keyword, followed by a name, followed by parentheses ( )
* Parentheses may include parameter names separated by commas: (para1, para2, etc)
* Code to be Executed by the function is placed inside of curly brackest { }

Function parameters are listed inside of the parentheses ( ) in the function definition.

Function arguments are the values recieved by the function when it is invoked.
I
nside the function, the arguments (the parameters) behave as local variables.

* Functions allow you to reuse code. Define the code once, and use it many times. Use the same code many times with different arguments to produce different results.
* Functions can be used as variable values: formulas, assignments, calculations
* Variables declared within a JS function become LOCAL to that function.
* Local variables can only be accessed from within that function

### Function Invocation

* This means that the code inside of the function will execute when "something" invokes (calls) the function

* When an event occurs (user clicks a button)
* When it is invoked (called) from JS code
* Automatically (self invoked)
* The ( ) operator invokes the function accessing a function without ( ) will return the function object instead of the function result.

### Function Return

* When JS reaches a return statement, the function will stop executing
* If function was invoked from a statement, JS will "return" to execute the code after the invoking statement
* Functions often compute a return value, this return value is "returned" back to the "caller" (user)

### JS Operators

Arithmetic operators

* Assignment operator (=) assigns a value to a variable
* Addition operator (+) adds numbers
* Multiplaction operator (*) multiplies numbers
* Subtraction operator (-) subtrabts numbers
* Division operator (/) divides numbers
* Modulus operator (%) division remainder
* Exponentiation operator (**) raises the value to the power on the right of operator
* Increment operator (++) Increment
Decrement operator (--) * Decrement

Assignment Operators

* Operator -- Example -- Same As
      =             x=y             x=y
    +=             x=+y         x=x+y
    -=             x-=y           x=x-y
    *=             x*=y           x=x*y
    /=             x/=y           x=x/y
    %=           x%=y         x=x%y
    **=           x**y           x=x**y

Adding JS Strings

* ie: let firstname = "X";
let lastname = "Y";
let firstlast = firstname + " " + lastname;

JS Compairison operators

==     Equal to
===   Equal value and equal type
!=       Not equal
!==    Not equal value or equal type
>         Greater than
<         Lesser than
>=      Greater than or equal to
<=       Lesser than or equal to
?         Ternary operator

JS Logical Operators
&&     Logical AND
||         Logical OR
!          Logical NOT

* JS Type Operators
* JS Bitwise Operators
