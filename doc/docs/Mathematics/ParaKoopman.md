

## Parametric Dynamical Systems

Let $(X, \mathcal{S}, m)$, with $X \subseteq \mathbb{R}^{N_x}$ be a finite measure space
where $\mathcal{S}$ is the Borel $\sigma$-algebra and $m$ is a measure on $(X, \mathcal{S})$.
Consider a set $U \subseteq \mathbb{R}^{N_u}$ of parameters, and the parametric discrete-time dynamics

$$ \mathbf{x}_{n+1} = \mathbf{f}(\mathbf{x}_n, \mathbf{u}), \quad n = 0,1,\cdots $$

where $\mathbf{u} \in U$ remains static, or control systems

$$ \mathbf{x}_{n+1} = \mathbf{f}(\mathbf{x}_n, \mathbf{u}_n), \quad n = 0,1,\cdots, $$

where $\mathbf{u}_n \in U$ changes in discrete steps dynamically.

## Parametric Koopman Operator

**Definition**. Consider the Hilber space

$$ L^2(X, m) = \left\{ \phi: X \rightarrow \mathbb{R}: \|\phi\|_{L^2(X, m)} < \infty \right\}. $$

An element $\phi \in L^2(X, m)$ is called an *observable*.

**Definition**. The *parametric Koopman operator* maps an observable $\phi \in L^2(X, m)$ to another observable $\mathcal{K}\phi$ defined by:

$$ \mathcal{K}(\mathbf{u}) \phi(\mathbf{x}) := \phi \circ \mathbf{f}(\mathbf{x}, \mathbf{u}). $$



