# Arrays
## Arrays are variables which can hold more than one value.
        const fruits = ["banana","apple","grapes"]
        const a1 = [7, "Harry", false]      // can be different types

## Accessing values
        let numbers = [1,2,7,9]
        numbers[0]      // o/p:1
        numbers[1]      // o/p:2

## Finding the length
        let numbers = [1,7,9,21]
        numbers[0]          // o/p:1
        numbers.length      // o/p:4

## Changing the values
        let numbers = [7,2,40,9]
        numbers[2] = 8      
        // "numbers" now becomes[7,2,8,9]
        // Arrays are mutable, arrays can be changed

#### In JavaScript, arrays are objects. The typeof operator on arrays returns object
        const n = [1, 7, 9]
        typeof n        // returns "object"

Arrays can hold many values under a single name

## Array Methods
#### There are some important array methods in JavaScript. some of them are as follows:
              
        // converts an array to a string of comma separated values
        1. toString() 

        let n = [1,7,9]
        n.toString()        // o/p: 1,7,9

        // joins all the array elements using a separator
        2.  join()

        let n = [7,9,13]
        n.join("-")         // o/p: 7-9-13

        // removes last element from the array
        3.  pop()

        let n = [1,2,4,6,9]
        n.pop()        // updates the original array returns the popped value

        // Adds a new element at the end of the array
        4.  push()

        
