System A:
[1,  1 | 2]
[2, -1 | 1]
[3,  0 | 3]

R2 <- R2 - 2*R1, R3 <- R3 - 3*R1:
[1,  1 |  2]
[0, -3 | -3]
[0, -3 | -3]

R3 <- R3 - R2:
[1,  1 |  2]
[0, -3 | -3]
[0,  0 |  0]

Consistent, (x, y) = (1, 1)

System B:
[1,  1 |   2]
[2, -1 |   1]
[3,  0 | 3.1]

R2 <- R2 - 2*R1, R3 <- R3 - 3*R1:
[1,  1 |    2]
[0, -3 |   -3]
[0, -3 | -2.9]

R3 <- R3 - R2:
[1,  1 |  2]
[0, -3 | -3]
[0,  0 | 0.1]

0 = 0.1 is false, so system B is inconsistent.

In A, the third equation is the sum of the first two (3x = 3).
Changing 3 to 3.1 breaks this relation, so the third line misses the intersection point.