## Question

Analyze, depending on the parameter $a$, the system

$$\begin{cases} x+y=2, \\ ax+ay=4. \end{cases}$$

Among the three possibilities — exactly one solution, infinitely many solutions, no solution — determine which actually occur and for which values of $a$. If one type cannot occur, explain why.

## Solution

```text
[1, 1 | 2]
[a, a | 4]

R2 <- R2 - a*R1:
[1, 1 |     2]
[0, 0 | 4 - 2a]

a = 2: 0 = 0, infinitely many solutions: (x, y) = (2 - t, t)
a != 2: 0 = 4 - 2a != 0, no solution

Exactly one solution never occurs: row 2 of the coefficients is a * row 1,
so there is always a zero row, hence at most 1 pivot for 2 unknowns.
```