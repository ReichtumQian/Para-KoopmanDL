
The class `ForwardEuler` is a subclass of [[FlowMap.md|FlowMap]].
It implements the forward Euler method

$$ \mathbf{x}(n+1) = \mathbf{x}(n) + k \mathbf{f}(\mathbf{x}(n), \mathbf{u}(n)), $$

where $k$ is the time step size.

## Methods

- `step(self, ode, x, u)`: Overrides `FlowMap.step()`.