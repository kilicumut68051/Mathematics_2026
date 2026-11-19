## Question

Exercise 9. Matrix Equation

Given
A = [1, 2; 0, 1], B = [3, 1; 2, 4].
Solve the equation AX = B for X.
Before calculating, decide on which side of the equation A^-1 must be used.
Then check the result by computing AX.

## Solution

A is on the left of X, so multiply on the left: X = A^-1 * B

A^-1 = [1, -2; 0, 1]
X = [1, -2; 0, 1] * [3, 1; 2, 4] = [-1, -7; 2, 4]

Check:
A * X = [1*(-1) + 2*2, 1*(-7) + 2*4; 2, 4] = [3, 1; 2, 4] = B