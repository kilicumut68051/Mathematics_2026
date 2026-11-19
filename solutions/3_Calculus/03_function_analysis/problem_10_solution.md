## Question

Perform a complete analysis of

$$
f(x)=\frac{x}{x^2+1}.
$$

Include the domain, symmetry, zeros, limits, monotonicity, extrema, and convexity. Finally, produce a sketch based only on this information.

## Solution

- Domain: $D_f = \mathbb{R}$.
- Symmetry: $f(-x) = -f(x) \implies$ odd function (symmetric about the origin).
- Zero: $f(x) = 0 \implies x = 0$, point $(0, 0)$.
- Limits and asymptotes: $\lim_{x\to\pm\infty} \frac{x}{x^2+1} = 0 \implies$ horizontal asymptote $y = 0$; no vertical asymptotes.
- Monotonicity and extrema:

$$
f'(x) = \frac{(x^2 + 1) - x(2x)}{(x^2 + 1)^2} = \frac{1 - x^2}{(x^2 + 1)^2}
$$

  - Decreasing on $(-\infty, -1)$ and $(1, \infty)$; increasing on $(-1, 1)$.
  - Global minimum at $x = -1$: $f(-1) = -\frac{1}{2}$; global maximum at $x = 1$: $f(1) = \frac{1}{2}$.
- Convexity and inflection points:

$$
f''(x) = \frac{-2x(x^2 + 1)^2 - (1 - x^2)\cdot 2(x^2 + 1)(2x)}{(x^2 + 1)^4} = \frac{2x(x^2 - 3)}{(x^2 + 1)^3}
$$

  - Concave on $(-\infty, -\sqrt{3})$ and $(0, \sqrt{3})$; convex on $(-\sqrt{3}, 0)$ and $(\sqrt{3}, \infty)$.
  - Inflection points: $(0, 0)$ and $\left(\pm\sqrt{3}, \pm\frac{\sqrt{3}}{4}\right)$.