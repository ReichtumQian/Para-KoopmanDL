
The class `EDMDDLSolver` implements the EDMD-DL algorithm.

## Attributes

- `__regularizer`: The regularizer $\lambda$ used in the computation of $K$.

## Methods

- `__init__(self, dictionary, regularizer)`
- `solve(self, data_x, data_y, n_epochs, batch_size, tolerance)`: 
  Applies the EDMD-DL algorithm to solve the system, 
  return a `Koopman` instance with a neural network function.




