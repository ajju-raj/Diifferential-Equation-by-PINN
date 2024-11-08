
# Solving Bessel's and Legendre's Differential Equations Using Physics-Informed Neural Networks (PINN)

## Overview

This project focuses on solving Bessel's and Legendre's differential equations using Physics-Informed Neural Networks (PINN). By integrating domain knowledge directly into the neural network, we achieve accurate solutions for these differential equations, leveraging the flexibility and power of deep learning in computational mathematics.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results](#results)
- [References](#references)

## Introduction

Physics-Informed Neural Networks (PINN) are an advanced neural network approach where physical laws, represented as differential equations, are incorporated into the loss function of the model. This project applies PINNs to solve:

- **Bessel's Differential Equation**: A type of second-order differential equation that appears in wave propagation and static potentials.
- **Legendre's Differential Equation**: A type of ordinary differential equation common in physics, especially in potential theory and spherical harmonics.

By solving these equations, we aim to demonstrate the potential of PINNs in mathematical and physical applications.

## Requirements

To run this project, ensure you have the following libraries installed:

- `Python 3.7+`
- `TensorFlow`
- `NumPy`
- `Matplotlib`
- `scikit-learn`
- `scipy`
- `pandas`
- `keras`

You can install the dependencies using:

```bash
pip install tensorflow numpy matplotlib keras scikit-learn scipy pandas
```

## Project Structure

- **file.ipynb**: Main script to solve Bessel's or Legendre's differential equations using PINNs (Different ipynb files from basic to main differential equation).
- **results/**: Directory to save and view model results and plots.
- **README.md**: Project documentation.

## Usage

To solve Bessel's or Legendre's differential equations, simply run the main script. The script allows you to choose between Bessel and Legendre equations using a command-line argument.

### Example

1. Clone the repository:
   ```bash
   git clone https://github.com/ajju-raj/bessel-legendre-pinn.git
   cd bessel-legendre-pinn
   ```

2. Run the model:
   ```bash
   python file.ipynb --equation bessel
   ```
   or
   ```bash
   python file.ipynb --equation legendre
   ```

The script will train a neural network on the chosen equation and output solution plots.

## Results

Results for each differential equation will be saved in the `Solution-Gallery/` folder. The output includes:

- Plots showing the true vs. predicted solution for Bessel's or Legendre's differential equation.
- Training loss over epochs.

Example results:

Results for both can be seen in the `Solution-Gallery/` folder.

## References

1. Raissi, M., Perdikaris, P., & Karniadakis, G. E. (2019). *Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations*. Journal of Computational Physics, 378, 686-707.
2. Differential equations and applications in physics textbooks.

## License

This project is licensed open source. Feel free to use and modify the code as required and contribute too.

---

For more projects, visit [github.com/ajju-raj](ajju-raj)!
