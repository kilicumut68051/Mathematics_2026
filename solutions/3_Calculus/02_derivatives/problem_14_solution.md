## Question

Investigate the behavior at $x=0$ of

$$f(x)= \begin{cases} x^2,&x\ge0, \\ ax,&x<0. \end{cases}$$

For which values of $a$ is the function continuous? For which values do the one-sided derivatives exist and agree? For which value of $a$ is the function differentiable? Explain why continuity alone is not sufficient.

## Solution

- Continuity at $x = 0$: $f(0) = 0$, $\lim_{x\to 0^+} f(x) = 0$, $\lim_{x\to 0^-} f(x) = 0$ for all $a \in \mathbb{R}$. Continuous for all $a \in \mathbb{R}$.
- One-sided derivatives at $x = 0$: $f'_+(0) = \lim_{h\to 0^+}\frac{h^2}{h} = 0$, $f'_-(0) = \lim_{h\to 0^-}\frac{ah}{h} = a$. They agree when $a = 0$.
- Differentiability at $x = 0$: For $a = 0$ only.
- Continuity only requires the graph to meet at $(0, 0)$, whereas differentiability also requires a single non-corner tangent slope ($a = 0$).