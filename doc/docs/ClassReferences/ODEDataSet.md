
The class `ODEDataSet` is a subclass of `torch.utils.data.Dataset`,
it provides data for `EDMDSolver`, `EDMDDLSolver` and `ParamKoopmanDLSolver`.

## Attributes

- `__data`: The state and parameter data of the system.
- `__labels`: The label data of the system.

## Methods

- `__init__(self, data, labels)`
- `__len__(self)`
- `__getitem__(self, idx)`
- `generate_init_data(self, n_traj, traj_len, x_min, x_max, param_min, param_max, seed_x=11, seed_param=22)`
- `generate_next_data(self, data_x, param)`
