## Question

Find a polynomial $p(x)=ax^2+bx+c$ whose graph passes through $(0,1)$, $(1,3)$, and $(2,9)$. Reduce the problem to a system of equations and check the result by substituting all three points.

## Solution

```text
p(0) = 1: c = 1
p(1) = 3: a + b + c = 3
p(2) = 9: 4a + 2b + c = 9

[1, 1, 1 | 3]
[4, 2, 1 | 9]
[0, 0, 1 | 1]

R2 <- R2 - 4*R1:
[1,  1,  1 |  3]
[0, -2, -3 | -3]
[0,  0,  1 |  1]

c = 1, b = 0, a = 2

p(x) = 2x^2 + 1

Check: p(0) = 1, p(1) = 3, p(2) = 9
```