[1, 1, 1 | 1]
[1, t, 1 | 2]
[1, 1, t | 3]

R2 <- R2 - R1, R3 <- R3 - R1:
[1,   1,   1 | 1]
[0, t-1,   0 | 1]
[0,   0, t-1 | 2]

t = 1: row 2 gives 0 = 1, no solution.

t != 1:
y = 1/(t-1)
z = 2/(t-1)
x = 1 - y - z = (t-4)/(t-1)

Exactly one solution:
(x, y, z) = ((t-4)/(t-1), 1/(t-1), 2/(t-1))