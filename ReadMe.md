# ⚡ MaxwellPy

*A Python library for simulating electromagnetic fields and interactions.*

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.9%2B-brightgreen)
![Status](https://img.shields.io/badge/status-experimental-orange)

---

## ✨ Overview
**MaxwellPy** is a Python toolkit for simulating and visualizing electromagnetic phenomena.  
It’s designed for **learning, prototyping, and research**, with a focus on clarity and extensibility.

With this library, you can:
- Compute electrostatic potentials & fields from **point charges**.
- Solve **Poisson’s equation** on grids for continuous charge distributions.
- Run **time-domain wave simulations** using the FDTD method.
- Visualize fields with intuitive plotting utilities.

---

## 🔧 Features
- ⚡ **Electrostatics:** point charges, dipoles, continuous charge densities.  
- 📐 **Numerical solvers:** Poisson equation (Jacobi, Gauss-Seidel, sparse solvers).  
- 🌊 **Wave propagation:** 1D/2D FDTD (Finite Difference Time Domain).  
- 📊 **Visualization tools:** potential maps, field vectors, streamlines.  
- 🔬 **Educational examples:** compare numerical vs. analytic solutions.  

---

## 📦 Installation
Clone the repository and install:

```bash
git clone https://github.com/yourusername/MaxwellPy.git
cd MaxwellPy
pip install -e .
