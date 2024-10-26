
A `TrainableDictionary` is a subclass of [[Dictionary.md|Dictionary]].
It contains a trainable neural network and $N_y$ non-trainable outputs,
mapping $\Psi: \mathbb{R}^{N \times N_x} \rightarrow \mathbb{R}^{N \times N_{\psi}}$.

## Attributes

- `__Ny`: The number of non-trainable outputs.

## Methods

- `__init__(self, func, Nx, Npsi, Ny)`
- `parameters(self)`: Return the trainable parameters of the network.


