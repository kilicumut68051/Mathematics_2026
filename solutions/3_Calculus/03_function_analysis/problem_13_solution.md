## Question

Perform a complete analysis of

$$
f(x)=\frac{\ln x}{x},\qquad x>0.
$$

Find the maximum and the behavior at the ends of the domain. Explain which information is necessary for a correct sketch.

## Solution

- Domain: $D_f = (0, \infty)$.
- Zero: $\ln x = 0 \implies x = 1$, point $(1, 0)$.
- Behavior at domain ends:
  - $\lim_{x\to 0^+} \frac{\ln x}{x} = -\infty \implies$ vertical asymptote $x = 0$.
  - $\lim_{x\to\infty} \frac{\ln x}{x} = 0 \implies$ horizontal asymptote $y = 0$ (approached from above for $x > 1$).
- Monotonicity and maximum:

$$
f'(x) = \frac{\frac{1}{x}\cdot x - \ln x \cdot 1}{x^2} = \frac{1 - \ln x}{x^2}
$$

  - Increasing on $(0, e)$; decreasing on $(e, \infty)$.
  - Global maximum at $x = e$: $f(e) = \frac{1}{e}$.
- Convexity: $f''(x) = \frac{2\ln x - 3}{x^3} = 0 \implies$ inflection point at $\left(e^{3/2}, \frac{3}{2e^{3/2}}\right)$.

A correct sketch requires the vertical asymptote at $x = 0$, the zero at $(1, 0)$, the global maximum at $\left(e, \frac{1}{e}\right)$, and the decay toward the horizontal asymptote $y = 0$ as $x \to \infty$.