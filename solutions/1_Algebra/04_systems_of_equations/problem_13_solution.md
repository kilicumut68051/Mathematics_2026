## Question

Consider the system

$$x_1+x_2=10,\qquad x_2+x_3=8,\qquad x_1-x_3=2.$$

Solve it and check whether all three equations are independently necessary to describe the solution set. If one follows from the others, show this by calculation.

## Solution

```text
[1, 1,  0 | 10]
[0, 1,  1 |  8]
[1, 0, -1 |  2]

R3 <- R3 - R1:
[1,  1,  0 | 10]
[0,  1,  1 |  8]
[0, -1, -1 | -8]

R3 <- R3 + R2:
[1, 1, 0 | 10]
[0, 1, 1 |  8]
[0, 0, 0 |  0]

x3 = t, x2 = 8 - t, x1 = 2 + t

(x1, x2, x3) = (2 + t, 8 - t, t), t in R

Equation 3 follows from equations 1 and 2:
(x1 + x2) - (x2 + x3) = 10 - 8  =>  x1 - x3 = 2
So only two equations are independently necessary.
```