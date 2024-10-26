
A `TrainableDictionary` is a subclass of [[Dictionary.md|Dictionary]].
It contains a trainable neural network and $N_y$ non-trainable outputs,
mapping $\Psi: \mathbb{R}^{N \times N_x} \rightarrow \mathbb{R}^{N \times N_{\psi}}$.

## Attributes

- `__Ny`: The number of non-trainable outputs.
- `__optimizer`: The optimizer of `_func`, which is a neural network model.

## Methods

- `__init__(self, func, Nx, Npsi, optimizer)`
- `train(self, data_loader, loss_func, n_epochs)`: Trains the `self._func`.


