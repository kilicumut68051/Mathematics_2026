## Question

Exercise 3. When Does the Inverse Not Exist?

For
A = [2, 4; 1, 2]
explain in two ways why A^-1 does not exist:
using the determinant and using dependence between the rows.

## Solution

Determinant:
det(A) = 2*2 - 4*1 = 0, so A^-1 does not exist.

Dependent rows:
Row 1 = 2 * Row 2, so the rows are linearly dependent.
R1 <- R1 - 2*R2 gives a zero row, so A cannot be reduced to I.

det(A) = 0 exactly when the rows are dependent.