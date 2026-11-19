S = [2, 0; 0, 1], H = [1, 1; 0, 1], T = HS

Method 1:
T = H * S = [2, 1; 0, 1]
det(T) = 2
T^-1 = (1/2) * [1, -1; 0, 2] = [1/2, -1/2; 0, 1]

Method 2:
S^-1 = [1/2, 0; 0, 1]
H^-1 = [1, -1; 0, 1]
S^-1 * H^-1 = [1/2, -1/2; 0, 1]

Both methods give the same result.

Wrong order:
H^-1 * S^-1 = [1/2, -1; 0, 1] != T^-1

T = HS applies S first and then H.
To undo it we undo H first and then S, so T^-1 = S^-1 * H^-1.