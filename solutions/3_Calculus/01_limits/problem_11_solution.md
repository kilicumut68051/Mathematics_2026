## Question

Compute

$$
\lim_{n\to\infty}\sqrt[n]{5^n+2^n}.
$$

Explain which term dominates and why the transformation looks different from the case of a quotient of polynomials.

## Solution

$$
\lim_{n\to\infty}\sqrt[n]{5^n+2^n} = \lim_{n\to\infty}\sqrt[n]{5^n\left(1 + \left(\frac{2}{5}\right)^n\right)} = \lim_{n\to\infty}5\left(1 + \left(\frac{2}{5}\right)^n\right)^{1/n} = 5 \cdot 1^0 = 5
$$

$5^n$ dominates $2^n$ because $\left(\frac{2}{5}\right)^n \to 0$; unlike a polynomial quotient where we divide by a single power, here we factor out the largest exponential base $5^n$ inside the $n$-th root.