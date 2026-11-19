A = [1, 2; 3, 5]

[1, 2 | 1, 0]
[3, 5 | 0, 1]

R2 <- R2 - 3*R1:
[1,  2 |  1, 0]
[0, -1 | -3, 1]

R2 <- -R2:
[1, 2 |  1,  0]
[0, 1 |  3, -1]

R1 <- R1 - 2*R2:
[1, 0 | -5,  2]
[0, 1 |  3, -1]

A^-1 = [-5, 2; 3, -1]

Each row operation is multiplication by an elementary matrix E.
E_k * ... * E_1 * A = I, so E_k * ... * E_1 = A^-1,
and applying the same operations to I produces A^-1.