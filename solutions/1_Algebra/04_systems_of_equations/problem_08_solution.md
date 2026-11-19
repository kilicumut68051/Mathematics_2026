## Question

Solve by elimination the two systems

$$\begin{cases} 2x+y=5, \\ x-y=1, \end{cases}$$

$$\begin{cases} 2x+y=1, \\ x-y=4. \end{cases}$$

Compare the successive elimination steps. Which part of the calculation is the same in both cases, and why?

## Solution

```text
System 1:
[2,  1 | 5]
[1, -1 | 1]

R1 <-> R2:
[1, -1 | 1]
[2,  1 | 5]

R2 <- R2 - 2*R1:
[1, -1 | 1]
[0,  3 | 3]

y = 1, x = 2

System 2:
[2,  1 | 1]
[1, -1 | 4]

R1 <-> R2:
[1, -1 | 4]
[2,  1 | 1]

R2 <- R2 - 2*R1:
[1, -1 |  4]
[0,  3 | -7]

y = -7/3, x = 5/3

Same in both: the row operations and the coefficient part [1, -1; 0, 3],
because they depend only on the coefficient matrix. Only the right-hand side differs.
```