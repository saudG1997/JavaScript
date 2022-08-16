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
The Syntax of a for loop looks something like this:
        for(statement1; statement2; statement3){
            // code to be executed
        }

        where,
        - statement1 is executed one time
        - statement2 is the condition base on which the loop runs (loop body is executed)
        - statement3 is executed everytime the loop body is executed

## The for-in loop
The Syntax of for-in loop looks like this:
        for(key in object){
            // code to be executed
        }

Note: for-in loop also work with arrays which will be discussed in the later...


## The for-of loop
The Syntax of for-of loop looks like this:
        for(variable of iterable){
            // code...
        }

        where,
        variable --- for every iteration,
        iterable --- iterable data structure like arrays, strings etc.

## The while loop

