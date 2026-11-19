## Question

Find numbers $x,y$ satisfying

$$x+y=10,\qquad 2x+5y=32.$$

Solve the system and explain geometrically why the solution is unique.

## Solution

```text
[1, 1 | 10]
[2, 5 | 32]

R2 <- R2 - 2*R1:
[1, 1 | 10]
[0, 3 | 12]

y = 4, x = 6
(x, y) = (6, 4)

Check: 6 + 4 = 10, 2*6 + 5*4 = 32

The two lines have different slopes (-1 and -2/5), so they are not parallel
and intersect in exactly one point.
```