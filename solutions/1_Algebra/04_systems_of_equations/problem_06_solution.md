[1, 1 | 2]
[a, a | 4]

R2 <- R2 - a*R1:
[1, 1 |     2]
[0, 0 | 4 - 2a]

a = 2: 0 = 0, infinitely many solutions: (x, y) = (2 - t, t)
a != 2: 0 = 4 - 2a != 0, no solution

Exactly one solution never occurs: row 2 of the coefficients is a * row 1,
so there is always a zero row, hence at most 1 pivot for 2 unknowns.