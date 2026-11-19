## Question

Analyze the monotonicity and extrema of

$$f(x)=xe^{-x}.$$

Also examine the behavior as $x\to\infty$ and explain how the limit affects the shape of the graph on the right-hand side.

## Solution

$$f'(x) = e^{-x} - xe^{-x} = (1 - x)e^{-x}$$

Critical point: $f'(x) = 0 \implies x = 1$.

- On $(-\infty, 1)$: $f'(x) > 0 \implies$ increasing.
- On $(1, \infty)$: $f'(x) < 0 \implies$ decreasing.
- Local and global maximum at $x = 1$: $f(1) = e^{-1} = \frac{1}{e}$.

Behavior as $x \to \infty$:

$$\lim_{x\to\infty} \frac{x}{e^x} = 0$$

Since $f(x) > 0$ for $x > 0$ and $\lim_{x\to\infty} f(x) = 0$, the graph approaches the positive $x$-axis ($y = 0$) from above as a horizontal asymptote on the right.