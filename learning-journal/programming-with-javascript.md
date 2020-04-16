# Programming with Javascript
* Javascript can access content, modify content, program rules, and react to events

## What is a script?
* A script is a series of instructions that a computer follows to acheive a goal
* To write a script, state your goal, then list the tasks that need to be completed in order to acheive it
  1. Define the Goal
  1. Design the script
  1. Code each step
* Computers solve problems by following a series of instruction one after the other
* To approach writing a script, sketch out tasks in a flowchart

## Expressions and Operators
* Expressions assign a value to a variable, such as `var color = blue;` or `var area = 3 * 2;`
* Some operators: 
  * `i++` means `i = i +1`, same idea with `--`
  * `%` meanse **modulus** whichs divides the numbers and takes the remainder
  * adding two strings together goes like this:
  `var one = '7'`  
  `var two = 'dog'`  
  `var three = one + 2;`  
  `three == '7dog'`

## Functions
* Functions group a series of statements to perform a specific task. They are packaged in a code block. They are reusable
* Information passed to a function are known as the **parameters** and what comes out is the **return value**
* example:  
`function sayHello() {
    document.write('Hello!');
}`
* To call the function `sayHello();`
* An example with variables: 
`function getArea (width, height) { 
    return width * height;
}`
* call the function `getArea(3,5);` returns `15`
* **Arguments** are the values you put in the parentheses when you call a function
* You can use **variables** as **arguments**

