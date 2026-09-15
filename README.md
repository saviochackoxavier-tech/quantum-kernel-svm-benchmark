<div align="center">

# ⚛️ Scalable Quantum Kernel SVM & Advanced Manifold Benchmark
### *Bridging Classical Machine Learning and Hilbert Space Quantum Kernels via Qiskit*

[![Qiskit Version](https://img.shields.io/badge/Qiskit-1.x-blueviolet?style=for-the-badge&logo=qiskit&logoColor=white)](https://qiskit.org/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-Framework-orange?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

</div>

---

## 📌 Executive Summary

This repository presents a **production-grade, end-to-end framework** implementing Scalable Quantum Kernel Support Vector Machines (SVM) on non-linear manifolds. 

Rather than relying on basic tutorial scripts, this pipeline goes a step further by incorporating **advanced quantum information metrics**—such as Hilbert Space Effective Rank and Kernel Target Alignment (KTA)—to rigorously evaluate how effectively quantum feature maps encode complex data patterns compared to classical baselines (Linear, Polynomial, and RBF kernels).

---

## 🌟 Core Architectural Innovations

* 🔄 **Dynamic Scalable Quantum Feature Map:** Automatically scales to arbitrary $n$-dimensional classical data points, converting them into $n$-qubit circuits using uniform Hadamard superposition layers, parameterized $R_z$ feature rotations, and cascading ring-entangling $ZZ$-interactions.
* 📐 **Exact Statevector Kernel Simulation:** Computes the quantum inner product kernel matrix $K(x, z) = |\langle\psi(z)|\psi(x)\rangle|^2$ efficiently using statevector probability amplitudes, completely bypassing sampling noise for analytical clarity.
* 📉 **Hilbert Space Spectrum & Effective Rank Analysis:** Evaluates the eigenvalue distribution of the training kernel matrix to quantify the expressibility of the quantum feature space and guard against kernel polarization or barren plateaus.
* 🎯 **Kernel Target Alignment (KTA):** Computes Frobenius inner products between the quantum kernel matrix and the target label matrix to mathematically score feature map alignment *prior* to model training.
* 🎨 **Multi-Panel Research Dashboard:** Generates publication-ready visualizations combining accuracy bar charts, kernel similarity heatmaps, eigenvalue decay curves, and side-by-side decision boundary mesh plots.

---

## 🔬 Dataset & Methodology

To truly test the geometric expressibility of the quantum kernel, this benchmark evaluates models against:
1. **The `make_moons` Dataset:** A standard non-linear manifold that is notoriously difficult for linear classical models to separate.
2. **Custom Graph Structures:** Utilizing structured datasets inspired by IBM's graph datasets to test high-dimensional entanglement mapping.

---

## 📊 Performance Benchmark Matrix

| Model Architecture | Kernel Type / Configuration | Accuracy Score | Key Diagnostic / Note |
| :--- | :--- | :--- | :--- |
| **Classical SVM** | Linear Kernel | $0.833$ | Struggles heavily with non-linear manifolds |
| **Classical SVM** | Polynomial Kernel | $0.767$ | Shows moderate boundary adjustment |
| **Classical SVM** | **Radial Basis Function (RBF)** | **$0.933$** | Strong classical non-linear baseline |
| **Quantum Kernel SVM** | **Custom Entangled Circuit** | **$0.767$** | **Rich geometric diagnostics & high expressibility ($2.44$ Effective Rank)** |

---

## 🛠️ Installation & Dependencies

Ensure you have Python 3.10+ installed, then clone the repository and run the setup command:

git clone https://github.com/saviochackoxavier-tech/quantum-kernel-svm-benchmark.git
cd quantum-kernel-svm-benchmark
pip install qiskit scikit-learn matplotlib numpy


🙏 Acknowledgments
A massive and heartfelt thank you to the organizers and instructors of the Quantum Kernel SVM Workshop. The foundational concepts, brilliant insights, and hands-on guidance provided during the class were the primary spark and inspiration behind this project. Their dedication to teaching and demystifying Quantum Machine Learning made this advanced pipeline possible!

📜 License
Distributed under the MIT License. See LICENSE for more information.
