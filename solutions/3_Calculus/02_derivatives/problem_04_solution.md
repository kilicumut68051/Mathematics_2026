## Question

For

$$
f(x)=\frac{x^2+1}{x-1}
$$

determine the domain, compute the derivative, simplify the result, and explain why the restriction $x\neq1$ remains important.

## Solution

Domain: $D_f = \mathbb{R} \setminus \{1\}$.

Using the quotient rule $\left(\frac{u}{v}\right)' = \frac{u'v - uv'}{v^2}$ with $u = x^2 + 1$ and $v = x - 1$:

$$
f'(x) = \frac{2x(x - 1) - (x^2 + 1)(1)}{(x - 1)^2} = \frac{2x^2 - 2x - x^2 - 1}{(x - 1)^2} = \frac{x^2 - 2x - 1}{(x - 1)^2}
$$

The restriction $x \neq 1$ remains necessary because $f(1)$ is undefined and $f'(x)$ also has division by $(x - 1)^2 = 0$ at $x = 1$.