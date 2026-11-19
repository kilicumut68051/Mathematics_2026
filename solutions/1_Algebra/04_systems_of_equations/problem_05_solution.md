## Question

For the augmented matrix

$$\begin{pmatrix} 1 & 2 & -1 & \mid & 3 \\ 0 & 1 & 2 & \mid & 1 \\ 0 & 0 & 0 & \mid & 0 \\ \end{pmatrix}$$

determine the number of solutions and write them in parametric form. Explain how you know how many variables may be chosen freely.

## Solution

```text
[1, 2, -1 | 3]
[0, 1,  2 | 1]
[0, 0,  0 | 0]

2 pivots, 3 unknowns: 3 - 2 = 1 free variable (z).
No contradiction, so there are infinitely many solutions.

z = t
y = 1 - 2t
x = 3 - 2y + z = 1 + 5t

(x, y, z) = (1 + 5t, 1 - 2t, t), t in R
```