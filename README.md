# Basic-DataFitting
1. Build wine evaluation model by linear regression using all 11 attributes.

2. Build wine evaluation model by linear regression using 1 attribute which is the most efficient.

Support Library: Panda, Numpy, Matplotlib.pylot

Function:
X: matrix contains 11 attributes of the wine, 
Y: matrix contains the quality of the wine

- getAB(X, Y): return matrix A, B which is the tranpose form of X, Y sequently

- Theta(A, B): return Theta = (AT.A)-1(AT.B)

- R(theta_hat): return residual vector norm ||r|| = ||A.theta_hat – B||
