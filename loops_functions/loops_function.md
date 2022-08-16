# Loops and Functions
We use loops to perform repeated actions.
#### for example
    If you are assigned a task of printing numbers from 1 to 100, it will be very hectic to do it manually, loops help us automate such tasks.

## Types of loops in JavaScript
* for loop : loop a block of code no. of times.
* for-in loop : loops through the keys of an object
* for-of loop : loops through the values of an object
* while loop: loops a block based on a specific condition
* do-while loop : while loop variant which runs atleast once

## The for loop
- The Syntax of a for loop looks something like this:

        for(statement1; statement2; statement3){
            // code to be executed
        }

        where,
        - statement1 is executed one time
        - statement2 is the condition base on which the loop runs (loop body is executed)
        - statement3 is executed everytime the loop body is executed

## The for-in loop
- The Syntax of for-in loop looks like this:

        for(key in object){
            // code to be executed
        }

Note: for-in loop also work with arrays which will be discussed in the later...


## The for-of loop
- The Syntax of for-of loop looks like this:

        for(variable of iterable){
            // code...
        }

        where,
        variable --- for every iteration,
        iterable --- iterable data structure like arrays, strings etc.

## The while loop
- The Syntax of while loop looks like this:

        while(condition){
            // code to be executed
        }

Note: if the condition never becomes false, the loop will never end and this might crash the runtime.

## The do-while loop
- The do-while loop's syntax looks like this:

        do{
            // code to be executed
            // executed at least  once
        }while(condition)

## Functions in JavaScript
- A JavaScript Functions is a block of code designed to perform a particular task.
- Syntax:
        function myFunc(){
            // code
        }
        myFunc()

        // function with parameters
        function lorienFunc(parameter1, parameter2){
            // code
            // here the parameters behave as local variables
        }
        lorienFunc(7,8) // function invocation

Note: Function invocation is a way to use the code inside the function

- A function can also return a value. the value is "returned" back to the caller

        const sum = (a,b) => {
            let c = a+b;
            return c;       // returns the sum
        }


        // another way to create and use the function
        let y = sum(1,3)
        console.log(y)      // prints 4