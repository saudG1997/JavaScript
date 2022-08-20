# Variables and Data
Just like we follow some rules while speaking english (the grammar), we have some rules to follow while writing a JavaScript program. The set of these rules is called syntax in JavaScript.

## What is a Variable ?
A Variable is a container that stores a value. This is very similar to the containers used to store rice, water and .... (Treat this as an analogy!)

The value of a JavaScript Variable can be changed during the execution of a program

###### Declaring Variables
--------------------------------------------------------------------------
    example:
            var a = 7;
            let a = 7;

            (where, 
                var & let are keyword,
                a are identifier,
                = are assignment_operator and 
                7 are literal )
---------------------------------------------------------------------------

### Rules for choosing Variable names:
-> letters, digits, underscores and $ sign allowed.
-> must begin with a $, _ or a letter.
-> JavaScript reserved keywords cannot be used as a Variable name.
-> apple and Apple are different Variable (case sensitive).

## var vs let in JavaScript
-> var is globally scoped while let and const are block scoped.
-> var can be updated and re-declared within it's scope.
-> let can be updated but not re-declared.
-> const can neither be updated nor be re-declared.
-> var Variables are initialized with undefined whereas let and const Variables are not initialized.
-> const must be initialized during decelaration unlike let and var.

## Primitive data types and objects
Primitive datatypes are a set of basic data types in JavaScript.
object is a non primitive datatypes in JavaScript. There are the 7 primitive datatypes in JavaScript and they are:
* Null
* Number
* String
* Symbol
* Undefined
* Boolean
* Big initialized

### object
An object in JavaScript can be created as follows:

    const item = {
        name : "Red Bull",
        price : "1180"
    }

    (note: 'name' and 'price' are key , whereas "Red Bull" and "1180" are value)