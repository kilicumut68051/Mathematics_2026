## Question

Do not solve all of the following systems completely. For each situation, choose the method that best uses its structure and justify your choice:

1. one system with a triangular coefficient matrix

$$\begin{cases} 2x-y=3, \\ 4y=8; \end{cases}$$

2. three systems $Ax=b_i$ with the same invertible matrix $A$, when $A^{-1}$ is already known;
3. one $3\times3$ system for which the inverse matrix is not given and the goal is only to find one solution vector.

For case 1, carry out the chosen method completely. For cases 2 and 3, describe the plan and indicate which part of the computation would be reusable or unnecessary. Do not judge a method by its name alone — refer to the number of right-hand sides and the structure of the matrix.

## Solution

```text
1) 2x - y = 3, 4y = 8
Method: back-substitution (the matrix is already triangular).
y = 2
2x - 2 = 3 => x = 5/2
(x, y) = (5/2, 2)

2) Same invertible A, A^-1 known, three right-hand sides b_1, b_2, b_3
Method: x_i = A^-1 * b_i.
A^-1 is reused for all three, each needs only one matrix-vector product.

3) One 3x3 system, A^-1 not given, one solution needed
Method: Gaussian elimination on [A | b] and back-substitution.
Computing A^-1 is unnecessary, there is only one right-hand side.
```