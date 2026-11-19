## Question

For

$$f(x)=(3x^2-2x+1)^5$$

identify the inner and outer functions, compute their derivatives, and combine the result according to the chain rule. Explain the origin of the additional factor.

## Solution

Outer function: $g(u) = u^5$, with $g'(u) = 5u^4$.
Inner function: $u(x) = 3x^2 - 2x + 1$, with $u'(x) = 6x - 2$.

By the chain rule:

$$f'(x) = g'(u(x))\cdot u'(x) = 5(3x^2 - 2x + 1)^4(6x - 2)$$

The factor $(6x - 2)$ comes from the rate of change of the inner expression $3x^2 - 2x + 1$ with respect to $x$.