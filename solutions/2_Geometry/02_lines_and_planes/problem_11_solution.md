## Question

Find the equation of the plane containing

$$
(x,y,z)=(1,0,2)+t(1,1,-1)
$$

and the point $P=(0,2,1)$. Check that both the entire line and the point lie in the plane you obtain.

## Solution

Point on line: $Q = (1, 0, 2)$, direction $\mathbf{v}_1 = (1, 1, -1)$.
Vector to $P$: $\mathbf{v}_2 = P - Q = (-1, 2, -1)$.
Normal: $\mathbf{n} = \mathbf{v}_1 \times \mathbf{v}_2 = (1, 2, 3)$.
Plane: $1(x - 0) + 2(y - 2) + 3(z - 1) = 0 \implies x + 2y + 3z = 7$.
Check $P(0, 2, 1)$: $0 + 2(2) + 3(1) = 7$.
Check line: $(1 + t) + 2(t) + 3(2 - t) = 7$ for all $t$.