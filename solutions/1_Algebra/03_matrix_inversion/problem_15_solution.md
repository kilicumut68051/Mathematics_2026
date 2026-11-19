A = [2, 1; 1, 3], b = [7; 8]

Method 1 (A^-1 * b):
det(A) = 6 - 1 = 5
A^-1 = (1/5) * [3, -1; -1, 2]
x = A^-1 * b = (1/5) * [21 - 8; -7 + 16] = [13/5; 9/5]

Method 2 (Gaussian elimination):
[2, 1 | 7]
[1, 3 | 8]

R1 <-> R2:
[1, 3 | 8]
[2, 1 | 7]

R2 <- R2 - 2*R1:
[1,  3 |  8]
[0, -5 | -9]

-5*x2 = -9 => x2 = 9/5
x1 + 3*(9/5) = 8 => x1 = 13/5
x = [13/5; 9/5]

Comparison:
Both give x = [13/5; 9/5]. Gaussian elimination was simpler here:
2 row steps and back-substitution, no full inverse needed.