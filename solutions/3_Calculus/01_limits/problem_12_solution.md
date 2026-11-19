## Question

Compute

$$
\lim_{x\to0}(1+3x)^{1/x}.
$$

Connect the result with the limit from Exercise 5 and show the appropriate transformation.

## Solution

$$
\lim_{x\to0}(1+3x)^{1/x} = \lim_{x\to0}\left[(1+3x)^{\frac{1}{3x}}\right]^3
$$

Setting $u = 3x$ (so $u \to 0$ as $x \to 0$) and using $\lim_{u\to0}(1+u)^{1/u} = e$ from Exercise 5:

$$
\left[\lim_{u\to0}(1+u)^{1/u}\right]^3 = e^3
$$