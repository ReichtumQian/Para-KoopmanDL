
The class `AbstractODE` is an abstract class for ordinary differential equations (ODEs)
of the form

$$ \dot{\mathbf{x}}(t) = \mathbf{f} (\mathbf{x}(t), \mathbf{u}). $$

## Attributes

- `_dim` (int): The dimension of the ODE.
- `_param_dim` (int): The dimension of the parameter $\mathbf{u}$.
- `_rhs` ((ndarray, ndarray) -> ndarray): The right-hand side function of the ODE.
  It's a mapping $\mathbb{R}^{N \times N_x} \times \mathbb{R}^{N \times N_u} \rightarrow \mathbb{R}^{N \times N_x}$.


## Methods

- `__init__(self, dim, param_dim, rhs)`
- `rhs(self)`: Return the right-hand side function of the ODE.
