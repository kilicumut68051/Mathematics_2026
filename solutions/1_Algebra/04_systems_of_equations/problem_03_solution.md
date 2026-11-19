## Question

Solve or show that the system is inconsistent:

$$\begin{cases} x+2y=3, \\ 2x+4y=7. \end{cases}$$

Show how the contradiction appears in the matrix after elimination and interpret it in terms of equations.

## Solution

```text
[1, 2 | 3]
[2, 4 | 7]

R2 <- R2 - 2*R1:
[1, 2 | 3]
[0, 0 | 1]

The second row says 0 = 1, so there is no solution.
Equation 2 says x + 2y = 7/2, equation 1 says x + 2y = 3.
```