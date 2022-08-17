# String in JavaScripts
Strings are used to store and manipulate text. String can be created using the following syntax:
    let name = "Lorien" // creates a String
    name.length // This property prints length of the String

Strings can also be created using single quotes
    let name = 'Lorien'

## Template literals
Template literals use backtics instead of quotes to define a String
    let name = 'Lorien'

With Template literals, it is possible to use both single as well as double quotes inside a String
    let sentence = ` The name "is" Lorien's`
    // ` is a backtics
    // "" is a double quote
    // '' is a single quote

We can insert variables directly in Template literal. This is called string interpolation
    let a = `This is ${name}`   // name is a variables
    // prints `This is a 'lorien`

# Escape Sequence Characters
