## Question

Exercise 6. Solving a System Using the Inverse

Solve Ax = b, where
A = [2, 1; 1, 3], b = [5; 7],
using x = A^-1 * b.
Then substitute the resulting vector back into the equation and check the result.

## Solution

det(A) = 6 - 1 = 5
A^-1 = (1/5) * [3, -1; -1, 2]

x = A^-1 * b = (1/5) * [3*5 - 7; -5 + 2*7] = (1/5) * [8; 9] = [8/5; 9/5]

Check:
A * x = [2*(8/5) + 9/5; 8/5 + 3*(9/5)] = [25/5; 35/5] = [5; 7] = b