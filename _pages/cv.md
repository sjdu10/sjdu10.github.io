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

Professional Experience
======
* **Graduate Research Assistant**, California Institute of Technology, 2022 -- present
* **Undergraduate Research Assistant**, Peking University, 2019 -- 2022

Skills
======
* **Programming**: Python, PyTorch, C/C++
* **HPC & Systems**: MPI, GPU Parallelization (CUDA)
* **Methods**: Markov Chain Monte Carlo, Numerical Linear Algebra, Tensor Networks, Variational Optimization

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
* **S. Du**, W. Liu, R. Peng, J. Gray and G. Chan. "Tensor Network Computations That Capture Strict Variationality, Volume Law Behavior, and the Efficient Representation of Neural Network States." Oral presentation at APS Global Physics Summit, Anaheim, CA, 2025.

Awards & Fellowships
======
* 2022: **EAS Division Fellowship**, California Institute of Technology
* 2020: **Li Huirong Scholarship**, Peking University
* 2019: **Wang Lao Ji Scholarship**, Peking University

Research Experience
======
* **Hybrid Tensor Network & Neural Network Model for Quantum Variational Monte Carlo**
  * Advisor: Prof. Garnet Kin-Lic Chan, Caltech
  * Performed high-performance large-scale GPU/CPU parallelized Monte Carlo simulations of quantum many-body systems.
  * Engineered a novel hybrid variational ansatz by integrating Tensor Networks (MPS/PEPS) with SOTA Neural Networks (e.g. Transformer), achieving state-of-the-art accuracy in ground-state energy for the Fermi-Hubbard model.
  * Architected a modular, open-source Python library supporting flexible ansatz structures, implementing efficient MCMC sampling based on MPI for large-scale optimization. ([vmc_torch](https://github.com/sjdu10/vmc_torch))

* **Bridging Tensor Networks and Machine Learning**
  * Advisor: Prof. Garnet Kin-Lic Chan, Caltech
  * Developed a unified framework treating Tensor Networks as high-dimensional neural architectures, enabling the application of modern ML optimization techniques such as Automatic Differentiation and Stochastic Natural Gradient Descent.
  * Engineered scalable implementations that leverage the structural inductive bias of Tensor Networks (e.g., entanglement entropy structure) to improve the trainability and interpretability of large-scale variational models.

* **ML-Assisted Algorithms for Quantum Many-Body Systems**
  * Advisor: Prof. Yi Zhang, Peking University
  * Formulated a novel hybrid algorithm that maps complex quantum ground-state searches onto low-dimensional classical constrained optimization problems, greatly reducing computational complexity.
  * Implemented a machine-learned surrogate model to represent quantum constraints, utilizing neural networks to approximate the low-dimensional constraint function in observable expectation value manifold for efficient classical solvers.
