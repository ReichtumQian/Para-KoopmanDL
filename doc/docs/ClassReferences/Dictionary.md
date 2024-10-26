
A `Dictionary` is a vector function
$\Psi = (\psi_1, \psi_2, \cdots, \psi_{N_\psi})^T$,
where $\psi_i = g_i$ for $i = 1,\cdots,N_y$ (see
[[ApproxKoopman.md|Approximation of Koopman]]).
It supports batched operation
$\Psi: \mathbb{R}^{N \times N_x} \rightarrow \mathbb{R}^{N \times N_{\psi}}$.

## Attributes

- `_function`: The batched vector function
  $\Psi: \mathbb{R}^{N \times N_x} \rightarrow \mathbb{R}^{N \times N_{\psi}}$.
- `_Nx`: The input dimension $N_x$.
- `_Npsi`: The output dimension $N_{\psi}$.

## Methods

- `__init__(self, function, Nx, Npsi)`
- `__call__(self, x)`: Applies the dictionary to input `x`, which must satisfy $x \in \mathbb{R}^{N \times N_x}$.

