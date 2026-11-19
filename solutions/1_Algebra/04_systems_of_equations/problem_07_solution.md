1) 2x - y = 3, 4y = 8
Method: back-substitution (the matrix is already triangular).
y = 2
2x - 2 = 3 => x = 5/2
(x, y) = (5/2, 2)

2) Same invertible A, A^-1 known, three right-hand sides b_1, b_2, b_3
Method: x_i = A^-1 * b_i.
A^-1 is reused for all three, each needs only one matrix-vector product.

3) One 3x3 system, A^-1 not given, one solution needed
Method: Gaussian elimination on [A | b] and back-substitution.
Computing A^-1 is unnecessary, there is only one right-hand side.