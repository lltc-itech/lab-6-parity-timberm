# Instructions  

For this lab, you're going to flex some JavaScript Operators. You're going to attempt to create two programs on two web pages. The first one is required. The second one we'll consider an extra challenge, though we _have_ covered everything you need to know to accomplish it.

## Parity Tester

_Parity_ is the quality of an integer being even or odd. This page should prompt the user to enter an integer number and write to the browser window whether the number is even or odd. You should use the file called `parity.html` that is included with this lab.

Remember, you can use the prompt function to get input from a user:

```JavaScript
var myValue = prompt("Enter an integer greater than one.")
```

* You will also have to use the modulus operator (`%`) to test if a number is divisible by 2. 
* Think about what the remainder is when you divide an even number by 2.
* What is it when you divide an odd number by 2?

## Prime (Challenge)

This challenge is not required, however, even if you partially complete it, I will give you _some_ credit. A complete solution is not actually possible, anyway. So just try to get it doing _something_ and you should be okay.

The challenge is create a program that takes a numerical input from a user and then outputs a statement stating whether the number is prime. Your code goes in the file `prime_chal.html`.

Recall that a prime number is a number that is only divisible by one and itself.

A remarkably effective way to do this is to use the modulus operator (`%`) in conjunction with the conditional operator (`cond ? if_true : if_false`). With this, you can write a relatively short program that will effectively test numbers up to around 350.

You might have to think very carefully about this, but I promise it _is_ doable.

* Remember that a prime number is not divisible by anything but itself.
* You only need to check divisibility by other prime numbers.
* You can use the conditional operator to test each one.

## As Always

If you are stuck, contact me. I'm here to help.
