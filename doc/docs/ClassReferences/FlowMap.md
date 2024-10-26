
The class `FlowMap` implements the flow map $\varphi_t(x) := x(t), x(0) = x$.
This class serves as a base class for various numerical solvers
for initial value problems (IVPs).

## Attributes

- `_dt` (float): The time step size.

## Methods

- `__init__(self, dt)`
- `step(self, ode, x, u)`: 
  The input `x` should be in the form $\mathbb{R}^{N \times N_x}$,
  `u` should be in the form $\mathbb{R}^{N \times N_u}$.
  Returns the next state vector `x` after the ODE step.

