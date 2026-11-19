## Question

Exercise 14. A Matrix That Is Its Own Inverse

Assume that a square matrix A satisfies A^2 = I.
Show that A^-1 = A.
Then give an example of a 2x2 matrix different from I and -I
that satisfies this condition, and verify it by multiplication.

## Solution

Proof:
A^2 = I means A * A = I.
By definition, B is the inverse of A if AB = BA = I.
Taking B = A gives A*A = I, which holds.
So A^-1 = A.

Example:
A = [0, 1; 1, 0]   (A != I, A != -I)
A^2 = [0*0 + 1*1, 0*1 + 1*0; 1*0 + 0*1, 1*1 + 0*0] = [1, 0; 0, 1] = I