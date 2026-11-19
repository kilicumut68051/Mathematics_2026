## Question

Using only

$$f'(x)=\lim_{h\to0}\frac{f(x+h)-f(x)}h,$$

find the derivative of $f(x)=x^2$. Compare the result with the power rule and indicate where the limit is used in the calculation.

## Solution

$$f'(x) = \lim_{h\to0}\frac{(x+h)^2 - x^2}{h} = \lim_{h\to0}\frac{2xh + h^2}{h} = \lim_{h\to0}(2x + h) = 2x$$

This matches the power rule $\frac{d}{dx}(x^2) = 2x^{2-1} = 2x$. The limit is used in the final step as $h \to 0$ to drop the term $h$ from $2x + h$.