# Dynamical System Analysis and Visualization

This repository contains the graphical visualizations generated for the analysis of a nonlinear dynamical system under varying parameter conditions. The repository focuses on two complementary approaches:

1. **Statistical-based behavior classification** of numerical trajectories.
2. **Eigenvalue-based stability categorization** of the dynamical system.

The results are provided as PDF figures for different parameter-space discretizations, allowing comparison of the system behavior and stability patterns at different resolutions.

## Repository Contents

The repository currently contains the following main results:

### 1. Statistical-Based Classification

The statistical classification results categorize simulated trajectories into:

- **Non-Diverging**
- **Bounded(low-amplitude)**
- **Bounded periodic**

The classification is generated over discretized parameter spaces and visualized using 3D parameter-space plots.

Available parameter-space resolutions include:

- `8 × 8 × 8`
- `10 × 10 × 10`
- `15 × 15 × 15`

These plots illustrate how the distribution of non-diverging, periodic, and diverging responses changes across the parameter space.

### 2. Eigenvalue-Based Stability Categorization

The eigenvalue analysis evaluates the local stability characteristics of the system using the eigenvalues of the corresponding Jacobian matrix.

The corresponding results are provided for different parameter-space resolutions:

- `8 × 8 × 8`
- `10 × 10 × 10`
- `15 × 15 × 15`

These results provide a parameter-space representation of the stability characteristics obtained from the eigenvalue analysis.

## Purpose of the Repository

The results are provided to support the analysis of nonlinear dynamical behavior and parameter-dependent stability. In particular, the repository can be used to:

- Examine the distribution of different dynamical responses across parameter space.
- Compare statistical trajectory classification with eigenvalue-based stability analysis.
- Investigate parameter-dependent changes in system behavior.
- Assess the effect of parameter-space discretization on the obtained classifications.
- Reproduce and inspect the graphical results associated with the study.





