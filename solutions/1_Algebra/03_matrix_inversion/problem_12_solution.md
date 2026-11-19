## Question

Exercise 12. Finding Inverses Without Starting from Scratch

It is known that
A^-1 = [2, -1; -3, 2].
Without finding A, compute (3A)^-1, (A^T)^-1, and (A^2)^-1.
Justify each result using the appropriate property.

## Solution

(3A)^-1 = (1/3) * A^-1 = [2/3, -1/3; -1, 2/3]
Property: (cA)^-1 = (1/c) * A^-1

(A^T)^-1 = (A^-1)^T = [2, -3; -1, 2]
Property: (A^T)^-1 = (A^-1)^T

(A^2)^-1 = (A^-1)^2 = [2, -1; -3, 2] * [2, -1; -3, 2]
         = [4 + 3, -2 - 2; -6 - 6, 3 + 4] = [7, -4; -12, 7]
Property: (A*A)^-1 = A^-1 * A^-1