## Question

Compute

$$
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}.
$$

Explain why the highest-degree terms determine the result.

## Solution

$$
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7} = \lim_{n\to\infty}\frac{4 - \frac{3}{n} + \frac{1}{n^2}}{2 + \frac{5}{n} - \frac{7}{n^2}} = \frac{4}{2} = 2
$$

Dividing numerator and denominator by $n^2$ causes all lower-degree terms ($\frac{3}{n}, \frac{1}{n^2}, \frac{5}{n}, \frac{7}{n^2}$) to approach $0$ as $n \to \infty$, leaving the ratio of the leading coefficients.