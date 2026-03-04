---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Applied Physics**, California Institute of Technology, 2022 -- present
  * GPA: 4.1/4.3
  * Advisor: Prof. Garnet Kin-Lic Chan
* **M.S. in Applied Physics**, California Institute of Technology, 2022 -- 2024
  * GPA: 4.1/4.3
  * Advisor: Prof. Garnet Kin-Lic Chan
* **B.S. in Physics**, Peking University, 2018 -- 2022
  * GPA: 3.76/4.00
  * Advisor: Prof. Yi Zhang

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
* **S. Du**, W. Liu, R. Peng, J. Gray and G. Chan. "Tensor Network Computations That Capture Strict Variationality, Volume Law Behavior, and the Efficient Representation of Neural Network States." Oral presentation at APS Global Physics Summit, Anaheim, CA, 2025.

Professional Experience
======
* **Graduate Research Assistant**, California Institute of Technology, 2022 -- present
* **Undergraduate Research Assistant**, Peking University, 2019 -- 2022

Skills
======
* **Programming**: Python, PyTorch
* **HPC & Systems**: MPI, GPU Parallelization
* **Methods**: Markov Chain Monte Carlo, Numerical Linear Algebra, Tensor Networks, Variational Optimization

Research Experience
======
* **Large-Scale Quantum Monte Carlo with Hybrid TN-NN Models**
  * Advisor: Prof. Garnet Kin-Lic Chan, Caltech
  * Built a hybrid ansatz combining Tensor Networks (MPS/PEPS) with Neural Networks (Transformer), achieving state-of-the-art ground-state energy for the Fermi-Hubbard model.
  * Ran large-scale GPU/CPU parallelized Monte Carlo simulations of quantum many-body systems.

* **Unifying Tensor Networks and Deep Learning Optimization**
  * Advisor: Prof. Garnet Kin-Lic Chan, Caltech
  * Developed a framework treating Tensor Networks as neural architectures, enabling modern ML techniques (autodiff, stochastic natural gradient) for tensor network optimization.
  * Leveraged structural inductive bias of Tensor Networks to improve trainability and interpretability of large-scale variational models.

* **ML-Assisted Quantum Ground-State Search**
  * Advisor: Prof. Yi Zhang, Peking University
  * Mapped quantum ground-state searches onto low-dimensional classical constrained optimization, greatly reducing computational complexity.
  * Trained neural network surrogates to approximate quantum constraints for efficient classical solvers.

Open Source
======
* **[vmc_torch](https://github.com/sjdu10/vmc_torch)** -- A PyTorch library for variational Monte Carlo simulation of quantum many-body systems.
  * Modular framework supporting plug-and-play variational ansatzes (Tensor Networks, Neural Networks, and hybrids).
  * MPI-parallelized MCMC sampling and optimization for large-scale runs across multi-GPU/CPU clusters.

Awards & Fellowships
======
* 2022: **EAS Division Fellowship**, California Institute of Technology
* 2020: **Li Huirong Scholarship**, Peking University
* 2019: **Wang Lao Ji Scholarship**, Peking University
