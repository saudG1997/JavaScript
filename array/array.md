# Arrays
## Arrays are variables which can hold more than one value.
        const fruits = ["banana","apple","grapes"]
        const a1 = [7, "Harry", false]      // can be different types

## Accessing values
        let numbers = [1,2,7,9]
        numbers[0]      // output:1
        numbers[1]      // output:2

## Finding the length
        let numbers = [1,7,9,21]
        numbers[0]          // output:1
        numbers.length      // output:4

## Changing the values
        let numbers = [7,2,40,9]
        numbers[2] = 8      
        // "numbers" now becomes[7,2,8,9]
        // Arrays are mutable, arrays can be changed

#### In JavaScript, arrays are objects. The typeof operator on arrays returns object
        const n = [1, 7, 9]
        typeof n        // returns "object"

Arrays can hold many values under a single name

# Array Methods
### There are some important array methods in JavaScript. some of them are as follows:           

##### 1. toString()
        // converts an array to a string of comma separated values
        let n = [1,7,9]
        n.toString()        // output: 1,7,9

##### 2.  join()
        // joins all the array elements using a separator
        let n = [7,9,13]
        n.join("-")         // output: 7-9-13

##### 3.  pop()
        // removes last element from the array
        let n = [1,2,4,6,9]
        n.pop()        // updates the original array returns the popped value

##### 4.  push()       
        // Adds a new element at the end of the array
        let a = [7,1,3,8]
            a.push(9)
            // modifies the original array and returns the new array length

##### 5. shift()
        //Removes first element and returns it

##### 6. unshift()
        // Adds element to the beginning returns new array length

##### 7. delete
        // Array elements can be deleted using the delete operator
        let d = [7,8,9,10]
        delete d[1]         // delete is an operator

##### 8. concat()
        // Used to join arrays to the given array
        let a1 = [1,2,3]
        let a2 = [4,5,6]
        let a3 = [9,8,7]
        a1.concat(a2,a3)    // returns [1,2,3,4,5,6,9,8,7]
        // returns a new array does not change existing arrays



