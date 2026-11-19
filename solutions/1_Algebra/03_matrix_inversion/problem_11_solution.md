A(t) = [1, t; t, 1]
det(A(t)) = 1 - t^2

Invertible iff 1 - t^2 != 0, i.e. t != 1 and t != -1.

A(t)^-1 = (1/(1 - t^2)) * [1, -t; -t, 1],   t != 1, -1

At t = 1 and t = -1 the denominator is 0, so the formula is undefined.
t = 1:  A = [1, 1; 1, 1], t = -1: A = [1, -1; -1, 1].
The rows are dependent and det = 0.