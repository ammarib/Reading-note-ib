# COMPARISON OPERATORS
At the most basic level, you can
evaluate two variables using a
comparison operator to return a
t rue or f al se value.

# JavaScript Loops

JavaScript loops are used to repeatedly run a block of code - until a certain condition is met. When developers
talk about iteration or iterating over, say, an array
, it is the same as looping. JavaScript offers several option
s to repeatedly run a block of code, including while, do while, for and for-in.

* Here is an example of a JavaScript while loop:

var sum = 0;
var number = 1;
while (number <= 50) {  // -- condition
  sum += number;        // -- body
  number++;             // -- updater
}
alert("Sum = " + sum);  // => Sum = 1275

## do-while loop

The block following do is executed first and then the condition is evaluated. If the while condition is true, the block is executed again
and repeats until the condition becomes false. This is known as a post-test loop as the condition is evaluated after the block has executed.

The do-while loop is executed at least once whereas the while loop may not execute 
at all. The do-while is typically used in a situation where the body of a loop contains 
a statement that generates a value that you want to use in your conditional expression

var sum = 0;
var number = 1;
do {
   sum += number;         // -- body
   number++;              // -- updater
} while (number <= 50);   // -- condition
alert("Sum = " + sum);    // => Sum = 1275

