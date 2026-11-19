System 1:
[1,  1 | 2]
[1, -1 | 0]

R2 <- R2 - R1:
[1,  1 |  2]
[0, -2 | -2]

2 pivots, 2 unknowns: exactly one solution, (x, y) = (1, 1).

System 2:
[1, 1 | 2]
[2, 2 | 4]

R2 <- R2 - 2*R1:
[1, 1 | 2]
[0, 0 | 0]

1 pivot, 2 unknowns, no contradiction: infinitely many solutions, (x, y) = (2 - t, t).

System 3:
[1, 1 | 2]
[2, 2 | 5]

R2 <- R2 - 2*R1:
[1, 1 | 2]
[0, 0 | 1]

0 = 1 is false: no solution.