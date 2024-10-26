
The class `ParaKoopmanDLSolver` implements the algorithm of
learning parametric Koopman decompositions.

## Attributes

- `__dictionary` (TrainableDictionary)

## Methods

- `__init__(self, dictionary)`
- `solve(self, dataset, n_epochs, batch_size, tol)`:
    - `dataset` (ODEDataSet): The dataset to solve.
