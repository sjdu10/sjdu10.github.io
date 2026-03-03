---
title: "vmc_torch"
excerpt: "A high-performance, parallelized Variational Monte Carlo library built on PyTorch for quantum many-body systems."
collection: portfolio
---

## vmc_torch

A high-performance, parallelized **Variational Monte Carlo (VMC)** library built on [PyTorch](https://pytorch.org/) for quantum many-body systems.

**GitHub:** [https://github.com/sjdu10/vmc_torch](https://github.com/sjdu10/vmc_torch)

### Features

- **Neural Quantum States (NQS)**: Variational ansatze based on neural network architectures.
- **Tensor Network States (TNS)**: Support for Matrix Product States (MPS), Projected Entangled Pair States (PEPS), both bosonic and fermionic.
- **Hybrid NN-fTNS Models**: Neuralized fermionic tensor network states that combine neural networks with fermionic tensor networks for improved variational expressivity.
- **Tensor Network Functions (TNF)**: Functions defined by tensor networks with arbitrary geometry, supporting volume-law entanglement structures.
- **Distributed MCMC Sampling**: Uses [mpi4py](https://mpi4py.readthedocs.io/) for massively parallel Markov Chain Monte Carlo sampling on HPC clusters.
- **Auto-differentiation Optimization**: Leverages PyTorch's automatic differentiation for optimization methods including Stochastic Reconfiguration (SR).

### Related Publications

1. Si-Jing Du, Ao Chen, and Garnet Kin-Lic Chan, "Neuralized Fermionic Tensor Networks for Quantum Many-Body Systems," [Phys. Rev. B 113, 085134 (2026)](https://doi.org/10.1103/x8vl-qf14).
2. Wen-Yuan Liu\*, Si-Jing Du\*, Ruojing Peng, Johnnie Gray, and Garnet Kin-Lic Chan, "Tensor Network Computations That Capture Strict Variationality, Volume Law Behavior, and the Efficient Representation of Neural Network States," [Phys. Rev. Lett. 133, 260404 (2024)](https://doi.org/10.1103/PhysRevLett.133.260404).
