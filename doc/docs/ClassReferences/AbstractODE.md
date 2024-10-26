
The class `AbstractODE` is an abstract class for ordinary differential equations (ODEs)
of the form

$$ \dot{\mathbf{x}}(t) = \mathbf{f} (\mathbf{x}(t), \mathbf{u}). $$

## Attributes

- `_dim`: The dimension of the ODE.
- `_param_dim`: The dimension of the parameter $\mathbf{u}$.
- `_rhs`: The right-hand side function of the ODE.

## Methods

- `__init__(self, dim, param_dim, rhs)`
