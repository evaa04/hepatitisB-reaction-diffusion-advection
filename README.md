# 🧬 Hepatitis B Reaction–Diffusion–Advection Model
<p align="center">
  <img src="figures/liver_first.png" width="100%">
</p>
Finite-difference implementation of a multi-scale mathematical model (0D → 3D) of chronic Hepatitis B infection, including simulation in segmented real-liver geometry.

---

## 🚀 Project Overview

This project implements a previously developed reaction–diffusion–advection model describing viral dynamics and immune response.

Main features:

- Multi-scale implementation (0D, 1D, 2D, 3D)
- GPU acceleration 
- Real-liver 3D segmented geometry
- Fully reproducible scientific notebooks

---

## 🧠 Mathematical Model

The model describes the spatio-temporal evolution of:

- Viral load (q₁)
- Helper T cells (Tₕ)
- Cytotoxic T cells (T𝚌)
- Cytokine concentration (q₃)

Transport mechanisms:
- Diffusion
- Advection
- Nonlinear reaction terms

Numerical discretization:
Finite Difference Method (explicit scheme).

---

## 📊 Results

<p>
  <img src="figures/step_model.jpg" width="100%">
</p>

### 0D — Temporal Dynamics
[View implementation](code/Step1_model1.ipynb)

### 1D — Spatial Propagation
[View implementation](code/Step2_model1_definitivo_vectores.ipynb)

### 2D — Spatial heterogeneity
[View implementation](code/Step3_model1_CILINDRO_barrera.ipynb)

### 3D — Real liver segmentation
<p>
  <img src="figures/liver_3D.png" width="10%">
</p>
[View implementation](code/modelo_higado.ipynb)


---

## 🧪 Reproducibility

All simulations are implemented in Python using NumPy/CuPy and structured as step-by-step Jupyter notebooks.  
The repository allows full reproduction of results from 0D to 3D simulations.
