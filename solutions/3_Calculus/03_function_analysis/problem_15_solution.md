## Question

For the function

$$
f(x)=x^3-3x
$$

the derivative was correctly computed as

$$
f'(x)=3(x-1)(x+1).
$$

However, a student wrote the following conclusion:

> The derivative is positive between its zeros and negative outside them. Therefore, the function is decreasing on $(-\infty,-1)\cup(1,\infty)$, increasing on $(-1,1)$, has a local minimum at $x=-1$, and a local maximum at $x=1$.

1. Without differentiating again, explain why merely identifying the zeros of the derivative does not justify the stated sign chart, and find the error in the student's reasoning.
2. Construct the correct sign chart for $f'(x)$.
3. Give the correct intervals of monotonicity and the character of the extrema.
4. In each of the three intervals, choose one simple test point and show that the sign of the derivative confirms your classification.

## Solution

1. Zeros only divide the domain into intervals; the sign on each interval depends on the leading coefficient of the quadratic $f'(x) = 3x^2 - 3$. Since the leading coefficient is positive ($3 > 0$), the parabola opens upward, so $f'(x)$ is positive outside $(-1, 1)$ and negative between $-1$ and $1$—the student inverted the signs.
2. Sign chart for $f'(x) = 3(x - 1)(x + 1)$:
   - $(-\infty, -1)$: $f'(x) > 0$
   - $(-1, 1)$: $f'(x) < 0$
   - $(1, \infty)$: $f'(x) > 0$
3. Monotonicity and extrema:
   - Increasing on $(-\infty, -1)$ and $(1, \infty)$; decreasing on $(-1, 1)$.
   - Local maximum at $x = -1$ ($f(-1) = 2$); local minimum at $x = 1$ ($f(1) = -2$).
4. Test points:
   - $x = -2 \in (-\infty, -1)$: $f'(-2) = 3(-3)(-1) = 9 > 0$ (increasing).
   - $x = 0 \in (-1, 1)$: $f'(0) = 3(-1)(1) = -3 < 0$ (decreasing).
   - $x = 2 \in (1, \infty)$: $f'(2) = 3(1)(3) = 9 > 0$ (increasing).