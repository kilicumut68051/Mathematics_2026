## Question

Analyze

$$
f(x)=\frac1{x^2-1}.
$$

Determine the domain, asymptotes, sign, and monotonicity on the intervals of the domain. Explain why each interval must be analyzed separately.

## Solution

- Domain: $D_f = (-\infty, -1) \cup (-1, 1) \cup (1, \infty)$.
- Asymptotes: Vertical asymptotes at $x = -1$ and $x = 1$; horizontal asymptote at $y = 0$ ($\lim_{x\to\pm\infty} f(x) = 0$).
- Sign: $f(x) > 0$ on $(-\infty, -1) \cup (1, \infty)$; $f(x) < 0$ on $(-1, 1)$.
- Monotonicity:

$$
f'(x) = \frac{-2x}{(x^2 - 1)^2}
$$

  - On $(-\infty, -1)$: $f'(x) > 0 \implies$ increasing.
  - On $(-1, 0)$: $f'(x) > 0 \implies$ increasing.
  - On $(0, 1)$: $f'(x) < 0 \implies$ decreasing.
  - On $(1, \infty)$: $f'(x) < 0 \implies$ decreasing.

Each interval must be analyzed separately because $f$ is discontinuous at $x = \pm 1$, so monotonicity cannot cross vertical asymptotes.