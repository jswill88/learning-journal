# Operators and Loops

## Comparison and Logical Operators
* `==` Is equal to
* `!=` Is not equal to
* `===` Strict equal to
* `!==` Strict not equal to
  * `'3' !== 3` returns `false`
* `>` greater than
* `<` less than
* `>=` greater than or equal to
* `<=` less than or equal to
* `&&` logical and
* `||` logical or
* `!` logical not
  * `!(2<1)` returns `false` 
  * `!false` returns `true`

## Loops
* **Loops** check a condition and run a block of code if it is true
* `for(var i = 0; i < 10; i++) {  
    document.write(i);    
}`
* use a **FOR** loop if you want to run code a specific number of times
* use a **while** loop if you don't know how many times the code should run. It will loop as long as the condition is `true`
* **do...while** is similar to a **while**, but it will always run the statements at least once, even if the condition evaluates to `false`
* **For** loop
  * Initialization: `var i = 0` Create a variable and set it to 0. This is known as the counter
  * Condition: `i < 10` The loop will continue until the counter reaches a specified number
  * Update: `i++` Every time the statements are run, it adds one to the counter
* **While** loop syntax:  
`var i = 1;`   
`var msg = '';`   
`while (i <10) {`  
    `msg += i + ' x 5 = ' + (i*5) + '<br />';`  
    `i++;`  
`}`
* `msg += msg` meanse `msg = msg + msg`
