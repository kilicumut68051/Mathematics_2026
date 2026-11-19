## Question

Analyze the domain, zero, and monotonicity of

$$
f(x)=\ln x-x+1.
$$

Explain why the analysis must begin with the domain.

## Solution

- Domain: $D_f = (0, \infty)$.
- Monotonicity:

$$
f'(x) = \frac{1}{x} - 1 = \frac{1 - x}{x}
$$

  - On $(0, 1)$: $f'(x) > 0 \implies$ strictly increasing.
  - On $(1, \infty)$: $f'(x) < 0 \implies$ strictly decreasing.
- Maximum and zero: $f$ has a global maximum at $x = 1$ with $f(1) = \ln 1 - 1 + 1 = 0$. Since $f$ increases to $0$ on $(0, 1)$ and decreases from $0$ on $(1, \infty)$, $x = 1$ is the unique zero.

The analysis must begin with $x > 0$ because $\ln x$ is undefined for $x \le 0$ and the sign of $f'(x) = \frac{1-x}{x}$ relies on the denominator $x$ being positive.