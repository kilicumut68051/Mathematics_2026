## Question

Choose one function from the problem set and a point $x_0$ at which the derivative exists. Compute $f'(x_0)$ exact, and then calculate

$$
\frac{f(x_0+h)-f(x_0)}h
$$

for $h=1$, $0.1$, and $0.01$. Compare the values with $f'(x_0)$ and explain why the difference quotient approaching a single number is consistent with the definition of the derivative, while a few computations do not replace a limit argument.

## Solution

Using $f(x) = x^2$ at $x_0 = 2$: exact derivative $f'(2) = 2(2) = 4$.

- $h = 1$: $\frac{(2+1)^2 - 2^2}{1} = \frac{9 - 4}{1} = 5$
- $h = 0.1$: $\frac{(2.1)^2 - 2^2}{0.1} = \frac{4.41 - 4}{0.1} = 4.1$
- $h = 0.01$: $\frac{(2.01)^2 - 2^2}{0.01} = \frac{4.0401 - 4}{0.01} = 4.01$

The values approach $4$ as $h$ decreases, matching the definition of $f'(2)$, while a finite list of $h$ values cannot prove the limit holds for every $h \to 0$.