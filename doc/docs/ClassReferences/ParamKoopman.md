
The class `ParaKoopman` is a subclass of [[Koopman.md|Koopman]].
It represents a mapping $K: \mathrm{span}(\Psi) \times U \rightarrow \mathrm{span}(\Psi)$,
which is a finite-dimensional approximation of the parametric Koopman operator.

## Attributes

- `_func`: Inherited from `Koopman`, it's a mapping
  $K: \mathrm{span}(\Psi) \times U \rightarrow \mathrm{span}(\Psi)$,
  here we assume $U = \mathbb{R}^{N_u}$.

## Methods

- `__call__(self, x, para)`: Applies the parametric Koopman operator on `(x, para)`,
  which should satisfy $x \in \mathbb{R}^{N \times N_{\psi}}$,
  $\text{para} \in \mathbb{R}^{N_u}$.






