# Sequential Gaussian Variational Inference for Nonlinear State Estimation and Its Application in Robot Navigation

Welcome to the repository for implementing Sequential Gaussian Variational Inference (S-GVI) algorithms. Our work has been accepted by *IEEE Robotics and Automation Letters (RA-L)* and will be published soon. We are organizing the code for public sharing and will update this repository shortly.

## Abstract

Probabilistic state estimation is essential for robots navigating uncertain environments. Accurately and efficiently managing uncertainty in estimated states is key to robust robotic operation. However, nonlinearities in robotic platforms pose significant challenges that require advanced estimation techniques. Gaussian variational inference (GVI) offers an optimization perspective on the estimation problem, providing analytically tractable solutions and efficiencies derived from the geometry of Gaussian space. We propose a Sequential Gaussian Variational Inference (S-GVI) method to address nonlinearity and provide efficient sequential inference processes. Our approach integrates sequential Bayesian principles into the GVI framework, which are addressed using statistical approximations and gradient updates on the information geometry. Validations through simulations and real-world experiments demonstrate significant improvements in state estimation over the Maximum A Posteriori (MAP) estimation method.

## Repository Overview

This repository will include:
- **Implementation of S-GVI Algorithms**: Core algorithms and modules for sequential inference.
- **Simulation and Experiment Data**: Datasets and scripts used for validation.
- **Documentation**: Detailed instructions and guidelines for using the code.

## Prerequisites

Before using the code, ensure you have the following:

- **Knowledge**: Understanding of probabilistic state estimation and variational inference.
- **Software**:
  - Python 3.8 or higher
  - [NumPy](https://numpy.org/)
  - [SciPy](https://scipy.org/)
  - [Matplotlib](https://matplotlib.org/) for visualizations
- **Hardware**: A computer capable of running Python scripts efficiently.

## Installation

Once the code is available, follow these steps to set up your environment:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/minwons/SGVI.git
   cd SGVI
