# Expressions & Conditionals
A fragment of code that produces a value is called an expression. Every value written literally is an expression. for example: 77 or "apple"

## Operators in JavaScript
** Arithmetic Operators
    +   *    Addition
    -       Subtraction
    *       Multiplication
    **      Exponentiation
    /       Division
    %       Modulus
    ++      Increment
    --      Decrement


** assignment Operators
    =       x = y
    +=      x = x + y
    -=      x = x - y
    *=      x = x * y
    /=      x = x / y
    %=      x = x % y
    **=     x = x ** y

** Comparison Operators
    ==      equal to
    !=      not equal
    ===     equal value and types
    !==     not equal value or not equal type
    >       greater than
    <       less than
    >=      greater than or equal to
    <=      less than or equal to
    ?       turnary Operator

** Logical Operators
    &&      Logical AND
    ||      Logical OR
    !       Logical NOT

Apart from these, we also have type and bitwise operators. Bitwise operators perform bit by bit operations on numbers
example:
        7 + 8 = 15
        where,
            7 and 8 are Operands
            + are assignment Operator and
            15 are the Result


## Comments in JavaScript
Sometimes we want our programs to contain a text which is not executed by the JS Engine such a text is called comment in JavaScript.
A comment in JavaScript can be written as follows:
let a = 2;  // This is a sinngle linne comment

/* I am a ....
multiline comment ...
example..... */

Sometimes comments are used to prevent the execution of some line of code

let switch = true;
// switch = false;  ----> commented line can't executed


## Conditional Statements
Sometimes we might have to execute a block of code based off some condition.
For example a prompt might ask for the age of the user and if its greater than 18, display a special message.

In JavaScript we have three forms of if ... else Statement.
* if Statement
* if_else Statement
* if_else_if Statement

### If Statement
The if Statement in JavaScript looks like this:
    Syntax:

        if(condition){
            // execute this code
        }

The if Statement evaluates the condition inside the ().
if the condition is evaluated to true, the code inside the body of if is executed else the code is not executed.

### if_else Statement
The if Statement can have an optional else clause.
    Syntax:

        if(condition){
            // block of code, if condition true
        }
        else{
            // block of code, if condition false
        }

if the condition is true, code inside if is executed otherwise else block is executed.

### if_else_if Statement
Sometimes we might want to keep rechecking a set of conditions one by one until one matches.
    Syntax:

        if(age > 0){
            console.log("A valid age");
        }
        else if(age > 10 && age < 18){
            console.log("But you are a kid");
        }
        else if(age > 18){
            console.log("you are not a kid");
        }
        else{
            console.log("Invalid age");
        }


## JavaScript ternary operator
Evaluates a condition and executes a block of code based on the condition.
        syntax:
            condition ? exp1 : exp2
example syntax of ternary operator looks like this:
        (marks > 10) ? 'Yes' : 'No'

    (: if marks are greater than 10, you are passed else not)