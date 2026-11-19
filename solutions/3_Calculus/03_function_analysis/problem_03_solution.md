## Question

Analyze the domain, zeros, asymptotes, and monotonicity of

$$
f(x)=\frac{x+1}{x-2}.
$$

Finally, sketch a graph consistent with all the information obtained.

## Solution

- Domain: $D_f = \mathbb{R} \setminus \{2\}$.
- Zero: $x + 1 = 0 \implies x = -1$, point $(-1, 0)$.
- Vertical asymptote: $\lim_{x\to 2^-} f(x) = -\infty$, $\lim_{x\to 2^+} f(x) = +\infty \implies x = 2$.
- Horizontal asymptote: $\lim_{x\to \pm\infty} \frac{x+1}{x-2} = 1 \implies y = 1$.
- Monotonicity:

$$
f'(x) = \frac{1(x - 2) - (x + 1)(1)}{(x - 2)^2} = \frac{-3}{(x - 2)^2} < 0 \quad \forall x \neq 2
$$

$f$ is strictly decreasing on $(-\infty, 2)$ and strictly decreasing on $(2, \infty)$.