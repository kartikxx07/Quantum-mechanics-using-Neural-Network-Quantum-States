# Quantum-mechanics-using-Neural-Network-Quantum-States
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
![Python](https://img.shields.io/badge/python-3.9+-blue.svg)
![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange.svg)

This repository contains my MSc dissertation project completed at **Queen Mary University of London (Aug 2025)**.  
The work explores the use of **Neural Network Quantum States (NNQS)** — specifically **Restricted Boltzmann Machines (RBMs)** and **Feed-Forward Neural Networks (FFNNs)** — to approximate the ground state properties of the 1D Heisenberg spin-1/2 chain using **Variational Monte Carlo (VMC)** optimization in the **NetKet** framework.

---

## 📄 Contents
- `nnqs.ipynb` → Jupyter notebook implementing RBM and FFNN ansätze with NetKet  
- `dissertation.pdf` → Full dissertation report  

---

## 🧠 Project Overview
Quantum many-body systems are notoriously difficult to simulate due to the exponential growth of the Hilbert space.  
This project applies **machine learning methods** to quantum simulation:

- Implemented **RBM** and **FFNN** wavefunction ansätze  
- Optimized parameters via **Variational Monte Carlo (VMC)** sampling  
- Benchmarked convergence, accuracy, and scalability on the **1D Heisenberg spin-1/2 model**  

---

## 🔑 Key Results
- Both RBM and FFNN accurately approximated the ground state energy of an 8-site chain  
- Achieved **<1% error** compared to exact diagonalization benchmarks  
- RBMs converged **faster**, while FFNNs offered **more stable and expressive** approximations for larger systems  
- Demonstrated potential of NNQS for **scalable quantum simulation** at the intersection of machine learning and quantum physics  

---

## 📜 License
This project is licensed under the [MIT License](./LICENSE).  
