# NewtonZeroes
A simple TIBASIC program to find a zero of a formula using Newton's Method.

HOW TO USE:

As far as command line tools go, this one is pretty simple to understand, but I figured I'd leave some simple documentation anyway:

1: Passes, 2: Accuracy:

Essentially, this is asking whether you want the condition that determines your final answer to be the amount of iterations (as Newton's Method is inherently iterative) or the degree of accuracy you need out of the answer. Enter 1 if you need to do it by number of passes, and 2 if you need to do it by degree of accuracy.

Formula:

Should be pretty self explanatory, but this is the formula you're trying to find a zero of. Be sure to use X as the dependent variable, and do note that the program does not support the use of implicitly defined functions. Adding the "y=" is unnecessary.

An example of an input might be:

Formula:
(X^3)+4(x^2)+17x-32

# of Passes/ Accuracy:

What you're asked here depends on whether you chose the passes or accuracy option. If you chose passes, simply enter the number of iterations you want the calculator to perform. If you chose accuracy, type in the degree of accuracy you want the answer to have. (For example, if you want it to be accurate within 3 decimal points, you would type in 0.001).

Starting Point:

This is the initial guess you make at the zero. It does not have to be even remotely accurate, just a starting point. (Though, in equations with multiple zeroes, it helps to be closest to the particular zero you're looking for.)

And then it's off to the races! You may notice the output is a bit overwhelming, which leads us to...

PARSING THE OUTPUT:

The output comes in the form of a list of every iteration performed. Naturally, the one at the bottom is the most accurate, and your final answer, but I decided to include the others in case you need them for some sort of math problem or other application.

...And that's it! Again, this is just a fun little script I wrote to automate a tedious Calculus operation.
