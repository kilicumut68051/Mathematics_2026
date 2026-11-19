## Question

For

$$
f(x)=e^{\sin(x^2)}
$$

compute the derivative. First write the layers

$$
x\longrightarrow x^2\longrightarrow \sin(x^2)\longrightarrow e^{\sin(x^2)}
$$

and explain why differentiation moves through them in the reverse order.

## Solution

Layers:

$$
x \longrightarrow x^2 \longrightarrow \sin(x^2) \longrightarrow e^{\sin(x^2)}
$$

By the chain rule, differentiation starts from the outermost function ($e^u \to e^u$), then differentiates the next inner function ($\sin v \to \cos v$), and finally differentiates the innermost function ($x^2 \to 2x$):

$$
f'(x) = e^{\sin(x^2)} \cdot \cos(x^2) \cdot 2x = 2x\cos(x^2)e^{\sin(x^2)}
$$