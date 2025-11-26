# Learning Classical Phase Space with Energy-Based Models

This repository documents my Master's thesis project on using **Energy-Based Models (EBMs)** to learn classical phase space distributions and to study whether these models can also preserve the underlying **geometric (symplectic) structure** of physical systems.

---

## Abstract

What if a machine could not only learn to fit physical data—but also uncover the hidden geometric structure behind it?

This work takes a step toward that vision by combining classical phase space theory with modern energy-based learning. I investigate whether EBMs, trained solely on samples from a distribution, can capture both the statistical and structural properties of physical systems. In particular, I explore whether these models can implicitly respect the **symplectic structure**—a defining geometric property of phase space—without being explicitly told to do so.

I evaluate both **quadratic** and **neural** EBMs, analyzing their gradients, Jacobians, and local deviations from symplectic constraints. In addition to model outputs, I study the parameter space of trained networks across random seeds to identify statistical patterns in the learned weights. Using techniques such as principal component analysis (PCA) and element-wise structure evaluation, I reveal both the capabilities and limitations of these models in preserving geometric structure.

By blending physics, geometry, and machine learning, this work opens a path toward structure-aware generative models and lays the groundwork for future explorations in phase space learning and quantum–classical transitions.

---

## Repository Structure (planned)

 - `code/` – training scripts for quadratic and neural EBMs.  
- `figures/` – generated plots (energy landscapes, symplectic error, PCA, etc.)  

This README will be updated as the repository is populated with code and figures.
