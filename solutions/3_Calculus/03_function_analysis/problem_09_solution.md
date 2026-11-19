## Question

Analyze the asymptotes of

$$
f(x)=\frac{x^2+1}{x-1}.
$$

Perform polynomial division and explain why the remainder term vanishes for large $|x|$.

## Solution

- Vertical asymptote: $x = 1$ ($\lim_{x\to 1^-} f(x) = -\infty$, $\lim_{x\to 1^+} f(x) = +\infty$).
- Polynomial division:

$$
\frac{x^2 + 1}{x - 1} = \frac{(x - 1)(x + 1) + 2}{x - 1} = x + 1 + \frac{2}{x - 1}
$$

- Oblique asymptote: $y = x + 1$.

As $|x| \to \infty$, the denominator $|x - 1| \to \infty$, so the remainder term $\frac{2}{x - 1} \to 0$ and $f(x)$ approaches the line $y = x + 1$.