# Divi Educational Examples

Small, self-contained programs for learning how the [Divi](https://github.com/QoroQuantum/divi) quantum-programming framework represents and executes quantum workflows.

## Installation

```bash
pip install "qoro-divi[jupyter]==0.13.0"
```

The Minimum Birkhoff Decomposition example additionally requires the packages in its own `requirements.txt`.

Each example defaults to a local simulator. Where shown, `QoroService` is an optional backend substitution for users who already have service credentials; it is not required to complete a tutorial.

## Examples

- [Economic Load Dispatch](./economic_load_dispatch) — formulate constrained generation dispatch as a QUBO and solve it with PCE.
- [Minimum Birkhoff Decomposition](./minimum_birkhoff_decomposition) — combine a standalone `CircuitPipeline` with a classical CPLEX post-processor.
- [Portfolio Optimization](./portfolio_optimization) — build a Markowitz QUBO and partition it before solving with QAOA or PCE.
- [Quantum-Guided Cluster Algorithm](./quantum_guided_cluster) — use QAOA or PCE correlations to guide Max-Cut cluster moves.
- [Spin Dynamics](./spin_dynamics) — evolve a transverse-field Ising chain with `TimeEvolutionTrajectory`.
- [Travelling Salesman Problem](./travelling_salesman) — compare direct QAOA, partitioned QAOA, and PCE on a TSP QUBO.

## Working Through a Demo

Read the demo README, run its local Python entry point, then open its notebook when one is provided. The notebooks explain the same concepts interactively and are kept without saved execution output.

## License

See [LICENSE](./LICENSE) for details.
