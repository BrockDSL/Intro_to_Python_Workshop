
![dsl_logo.png](dsl_logo.png)

# Introduction to Python

***

Material for today: `http://bit.ly/DSLPython`

## Variables - The Basics

Basic structure is `variable = value`. Variables can be many things, numbers, letters, and lists.

EG. ratio between kilograms and pounds `kg_to_lbs = 2.2`
EG. list of x,y coordinates of a point `origin = [0,0]`

## Variables - Dictionaries

More complicated variable that has a `value` and a `key`
EG. 
`stocks = {`
`"IBM": "Internation Business Machines",`
`"GOOGL" : "Alphabet Inc",`
`"AAPL: "Apple Inc"`
`}`

EG. `print(stocks["GOOGL"])`
displays `Alphabet Inc`

## Doing Math

| Symbol |  Operation|
| --- | --- |
|` *`| multiplication |
|`+`| addition |
|`-`|subtraction|
|`%`|remainder|
|`/`|division|


## Loops

Allow us to repeat the same thing a few times

`crayon_colours = ["red","blue","yellow"]`
`for crayon in crayon_colours:`
`    print(crayon)`


## Conditionals

Allow us to compare to values 

|Operator|
| --- |
| `==` |
| `>=` |
| `<=` |
| `<` |
| `>` |
| `!=` |

## Conditionals with Boolean

Allow us to combine conditionals

|Operator|
| --- |
|`and`|
|`or`|
|`not`|

## Functions

We can use predefined bits of code if they are turned int functions.

EG. `len(some_variable)` will print out how long the variable is. If a list, than how many items. If some text, how many characters.

Making our own, you follow this prototype

`def function_name(parameter):`
`value = 0 `
`# do some stuff`
`return value`


