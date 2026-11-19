## Question

Write the system

$$\begin{cases} 2x-y+z=4, \\ x+3y-2z=1, \\ 3x+y+z=7. \end{cases}$$

in the form $Ax=b$.
Identify the coefficient matrix, the vector of unknowns, and the right-hand side vector. Explain how each row of the matrix corresponds to one equation.

## Solution

```text
A = [2, -1, 1; 1, 3, -2; 3, 1, 1]
x = [x; y; z]
b = [4; 1; 7]

Ax = b:
[2, -1, 1; 1, 3, -2; 3, 1, 1] * [x; y; z] = [4; 1; 7]

Row i of A holds the coefficients of equation i, e.g. row 1: 2x - y + z = 4.