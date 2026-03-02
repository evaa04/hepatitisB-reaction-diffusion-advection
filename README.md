# 🧬 Hepatitis B Reaction–Diffusion–Advection Model

Finite-difference implementation of a multi-scale mathematical model (0D → 3D) of chronic Hepatitis B infection, including simulation in segmented real-liver geometry.

---

## 🚀 Project Overview

This project implements a previously developed reaction–diffusion–advection model describing viral dynamics and immune response.

Main features:

- Multi-scale implementation (0D, 1D, 2D, 3D)
- GPU acceleration (optional)
- Real-liver 3D segmented geometry
- Fully reproducible scientific notebooks

---

## 🧠 Mathematical Model

The system describes:

- Viral load dynamics
- Immune cell interactions
- Cytokine transport
- Spatial diffusion and advection

Discretization method:
Finite Differences (explicit scheme).

---

## 📊 Results

### 1D Spatial Dynamics
![1D result](figures/result_1d.png)

### 3D Simulation in Real Liver Geometry
![3D result](figures/result_3d.png)

---

## ⚙️ Installation

```bash
conda env create -f environment.yml
conda activate hb-pde
jupyter lab
