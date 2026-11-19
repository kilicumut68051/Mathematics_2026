## Question

For

$$f_a(x)=x^3-3ax$$

depending on $a$, determine the number of critical points and their character. Separate the parameter cases and justify why the structure of the graph changes.

## Solution

$$f_a'(x) = 3x^2 - 3a = 3(x^2 - a)$$

1. $a < 0$: $x^2 - a > 0$ for all $x \in \mathbb{R} \implies 0$ critical points; $f_a$ is strictly increasing everywhere with no extrema.
2. $a = 0$: $f_0'(x) = 3x^2 = 0 \implies 1$ critical point at $x = 0$. Since $f_0'(x) \ge 0$ on both sides, $(0, 0)$ is a horizontal inflection point (no extremum).
3. $a > 0$: $f_a'(x) = 0 \implies x = \pm\sqrt{a}$ ($2$ critical points). $f_a$ increases on $(-\infty, -\sqrt{a})$, decreases on $(-\sqrt{a}, \sqrt{a})$, and increases on $(\sqrt{a}, \infty)$, giving a local maximum at $(-\sqrt{a}, 2a\sqrt{a})$ and a local minimum at $(\sqrt{a}, -2a\sqrt{a})$.

Changing the sign of $a$ changes the number of real roots of $x^2 = a$ from $0$ to $1$ to $2$, determining whether the cubic bends to form extrema.