# Subspace Method Based on Neural Networks in Weak Form (SNNW)

Codes associated with the manuscript titled  
**"Subspace method based on neural networks for solving the partial differential equation in weak form"**  
authored by *Pengyuan Liu, Zhaodong Xu, and Zhiqiang Sheng*.  

---

## Overview
This repository provides a modular and user-friendly implementation of the SNNW method,  
developed with **PyTorch 2.0.0**, and designed for ease of use and modification.  

In this version, we provide an example for solving the **one-dimensional Helmholtz equation**.    

---

## Abstract
In this paper, we propose a subspace method based on neural networks for solving the partial differential equations (PDEs) in weak form.
The method uses neural network-based functions as basis functions to span a subspace, within which an approximate solution is sought. 
The related algorithms are developed to address both linear and nonlinear PDEs with various boundary conditions in weak form.
To improve the approximation capabilities of the subspace, multiple training strategies are employed.
Numerical experiments demonstrate that the proposed method achieves high accuracy with minimal computational cost, requiring only 100 to 2,000 training epochs in most cases. The method offers significant advantages in both accuracy and computational efficiency.
