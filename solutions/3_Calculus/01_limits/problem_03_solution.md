## Question

Compute

$$
\lim_{n\to\infty}\left(\sqrt{n^2+5n}-n\right).
$$

Use the conjugate expression and explain why this transformation removes the difficulty.

## Solution

$$
\lim_{n\to\infty}\left(\sqrt{n^2+5n}-n\right) = \lim_{n\to\infty}\frac{(n^2+5n)-n^2}{\sqrt{n^2+5n}+n} = \lim_{n\to\infty}\frac{5n}{n\left(\sqrt{1+\frac{5}{n}}+1\right)} = \lim_{n\to\infty}\frac{5}{\sqrt{1+\frac{5}{n}}+1} = \frac{5}{2}
$$

Multiplying and dividing by the conjugate cancels $n^2$ in the numerator and replaces the $\infty - \infty$ subtraction with a sum in the denominator.