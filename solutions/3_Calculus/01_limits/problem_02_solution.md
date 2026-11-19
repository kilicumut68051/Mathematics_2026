## Question

Compute

$$
\lim_{n\to\infty}\frac{3n+1}{n^2+4},\qquad \lim_{n\to\infty}\frac{2n^3-n}{5n^2+1}.
$$

Compare the two cases and formulate a general observation about the degrees of the polynomials in the numerator and denominator.

## Solution

$$
\lim_{n\to\infty}\frac{3n+1}{n^2+4} = \lim_{n\to\infty}\frac{\frac{3}{n} + \frac{1}{n^2}}{1 + \frac{4}{n^2}} = 0
$$

$$
\lim_{n\to\infty}\frac{2n^3-n}{5n^2+1} = \lim_{n\to\infty}\frac{2n - \frac{1}{n}}{5 + \frac{1}{n^2}} = +\infty
$$

When the degree of the numerator is smaller than the degree of the denominator, the limit is $0$; when the degree of the numerator is larger, the sequence diverges to $\pm\infty$.