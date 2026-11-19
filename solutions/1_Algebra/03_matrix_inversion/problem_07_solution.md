## Question

Exercise 7. Inverse of a Product

For
A = [1, 1; 0, 1], B = [2, 0; 0, 3]
compute (AB)^-1 and B^-1 * A^-1.
Check that the results are the same and explain the meaning of the reversed order.

## Solution

AB = [2, 3; 0, 3]
det(AB) = 6
(AB)^-1 = (1/6) * [3, -3; 0, 2] = [1/2, -1/2; 0, 1/3]

A^-1 = [1, -1; 0, 1]
B^-1 = [1/2, 0; 0, 1/3]
B^-1 * A^-1 = [1/2, -1/2; 0, 1/3]

The results are equal: (AB)^-1 = B^-1 * A^-1.

AB means "first B, then A", so to undo it we first undo A, then B.