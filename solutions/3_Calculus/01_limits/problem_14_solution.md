## Question

Compute

$$
\lim_{x\to0}\frac{1-\cos x}{x^2}.
$$

Justify the result without using l'Hôpital's rule, using a trigonometric identity and the fundamental limit.

## Solution

Using $1 - \cos x = 2\sin^2\left(\frac{x}{2}\right)$:

$$
\lim_{x\to0}\frac{1-\cos x}{x^2} = \lim_{x\to0}\frac{2\sin^2\left(\frac{x}{2}\right)}{x^2} = \lim_{x\to0}\frac{1}{2}\left(\frac{\sin(x/2)}{x/2}\right)^2 = \frac{1}{2}\cdot 1^2 = \frac{1}{2}
$$