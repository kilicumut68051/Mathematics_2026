## Question

Find the orthogonal projection of $P=(2,1,3)$ onto the plane $x+y+z=3$, and then find the reflection of $P$ across this plane. Check that the midpoint of the segment joining the point and its reflection lies on the plane.

## Solution

$\mathbf{n} = (1, 1, 1)$
Line: $(2 + t, 1 + t, 3 + t)$
In plane: $(2 + t) + (1 + t) + (3 + t) = 3 \implies 6 + 3t = 3 \implies t = -1$
Orthogonal projection: $P' = (1, 0, 2)$
Reflection: $P'' = P + 2(P' - P) = (2, 1, 3) + 2(-1, -1, -1) = (0, -1, 1)$
Midpoint of $P$ and $P''$: $\left(\frac{2 + 0}{2}, \frac{1 - 1}{2}, \frac{3 + 1}{2}\right) = (1, 0, 2)$, which satisfies $1 + 0 + 2 = 3$.