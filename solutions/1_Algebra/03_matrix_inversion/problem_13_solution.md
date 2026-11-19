## Question

Exercise 13. Undoing a Composite Transformation

The matrices
S = [2, 0; 0, 1], H = [1, 1; 0, 1]
describe nonuniform scaling and shear. For T = HS, find T^-1 in two ways:
1. first compute T, then its inverse,
2. use (HS)^-1 = S^-1 * H^-1.
Compare the results. Additionally compute H^-1 * S^-1 and verify that
the incorrect order gives a different matrix.
Explain the rule: "when undoing a composition of operations, we undo them from the end."

## Solution

Method 1:
T = H * S = [2, 1; 0, 1]
det(T) = 2
T^-1 = (1/2) * [1, -1; 0, 2] = [1/2, -1/2; 0, 1]

Method 2:
S^-1 = [1/2, 0; 0, 1]
H^-1 = [1, -1; 0, 1]
S^-1 * H^-1 = [1/2, -1/2; 0, 1]

Both methods give the same result.

Wrong order:
H^-1 * S^-1 = [1/2, -1; 0, 1] != T^-1

T = HS applies S first and then H.
To undo it we undo H first and then S, so T^-1 = S^-1 * H^-1.