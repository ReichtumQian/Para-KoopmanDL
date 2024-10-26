
The class `Koopman` is a mapping $K: \mathrm{span}(\Psi) \rightarrow \mathrm{span}(\Psi)$, 
which acts as the finite-dimensional approximation of the Koopman operator $\mathcal{K}$,
i.e.,

$$ \mathcal{K} \Psi \approx K \Psi. $$

## Attributes

- `_func`: The mapping $K: \mathrm{span}(\Psi) \rightarrow \mathrm{span}(\Psi)$,
  which can be either a matrix or a neural network.

## Methods

- `__init__(self, func)`
- `__call__(self, x)`: Applies the Koopman operator,
  `x` should satisfy $x \in \mathbb{R}^{N \times N_{\psi}}$.


