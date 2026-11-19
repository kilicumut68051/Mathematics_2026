## Question

Exercise 2. Formula for a 2x2 Matrix

Find the inverse of
A = [3, 2; 5, 4]
using the formula for a 2x2 matrix.
At the end, check the result by computing one product with A.

## Solution

det(A) = 3*4 - 2*5 = 2

A^-1 = (1/2) * [4, -2; -5, 3] = [2, -1; -5/2, 3/2]

Check:
A * A^-1 = [3*2 + 2*(-5/2), 3*(-1) + 2*(3/2); 5*2 + 4*(-5/2), 5*(-1) + 4*(3/2)]
         = [1, 0; 0, 1] = I