## Question

Exercise 10. Inverse of a Diagonal Matrix

Given
D = [2, 0, 0; 0, -3, 0; 0, 0, 5], E = [2, 0, 0; 0, 0, 0; 0, 0, 5].
Without using Gauss-Jordan elimination, decide which matrix is invertible.
For the invertible matrix, give the inverse and check the result by multiplication.

## Solution

D has all nonzero diagonal entries, so D is invertible.
E has a zero on the diagonal (det(E) = 0), so E is not invertible.

D^-1 = diag(1/2, -1/3, 1/5)

Check:
D * D^-1 = diag(2*1/2, (-3)*(-1/3), 5*1/5) = I