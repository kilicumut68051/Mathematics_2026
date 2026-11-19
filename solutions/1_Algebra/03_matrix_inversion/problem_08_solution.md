## Question

Exercise 8. Inverse of a Transformation

The matrix
S = [2, 0; 0, 1/2]
describes a scaling of the plane.
Find S^-1 and explain geometrically what the inverse transformation does.
Check the action of the pair S, S^-1 on one simple vector.

## Solution

S^-1 = [1/2, 0; 0, 2]

S stretches x by 2 and compresses y by 1/2.
S^-1 compresses x by 1/2 and stretches y by 2, undoing S.

v = [1; 1]
S * v = [2; 1/2]
S^-1 * (S * v) = [1; 1] = v