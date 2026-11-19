## Question

Solve

$$\begin{cases} x+y+z=2, \\ 2x+2y+2z=4, \\ x-y+z=0. \end{cases}$$

Give the solution in parametric form, identify a free variable, and for one chosen parameter value check that the resulting point really satisfies the system.

## Solution

```text
[1,  1, 1 | 2]
[2,  2, 2 | 4]
[1, -1, 1 | 0]

R2 <- R2 - 2*R1, R3 <- R3 - R1:
[1,  1, 1 |  2]
[0,  0, 0 |  0]
[0, -2, 0 | -2]

y = 1, x + z = 1
Free variable: z = t

(x, y, z) = (1 - t, 1, t), t in R

Check with t = 2: (-1, 1, 2)
-1 + 1 + 2 = 2
2*(-1) + 2*1 + 2*2 = 4
-1 - 1 + 2 = 0
```