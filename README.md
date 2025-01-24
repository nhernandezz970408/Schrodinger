# Schrodinger Equation using Physics Informed Neural Network

The Physics Informed Neural Network were proposed in 2019 by M. Raissi, et al. (https://doi.org/10.1016/j.jcp.2018.10.045). The fundamental of PINNs is to combine neural networks with physics based constarins to solve differential equations. The differential equation is incorporated in the loss function term. The previous general physics knowledge acts as a regularization agent that limits the posible solutions.

## 1-D Poisson equation
As a first step to the proyect, I'm going to solve 1D Poisson equation:

$\frac{d^{2} u(x)}{dx^2} = f(x), x ∈ [0,1]$

The boundary conditions will be:

$u(0) = 0, u(1) = 0$

Whit the PINN the idea is to determine $u(x)$ and $f(x) = -2$ would be know in order to get an analitical solution to the problem.
