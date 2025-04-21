# 🧪 One-Mass Oscillator Optimization

This project involves modeling and optimization of a **one-mass oscillator system** using real-world data, and visualizing the results through a custom-built **Python GUI**.

---

## 📌 Project Overview

The main objective of this project is to fit a one-mass oscillator model to measured amplitude-frequency data by optimizing its parameters using various algorithms.

The governing equation for the oscillator model is:
V(ω) = F / sqrt((1 - ν²)² + 4D²ν²)


Where:
- **ω** = angular frequency  
- **ν** = ω_err / ω_eig  
- **D** = damping ratio  
- **F** = force amplitude

---

## 🧰 Features

- 📈 **Optimization Algorithms**:
  - Nelder-Mead
  - L-BFGS-B
  - Dual Annealing
  - Differential Evolution

- 🖥️ **Graphical User Interface (GUI)**:
  - Load data files (`df1.pkl`, `df2.pkl`)
  - Visualize real vs. predicted amplitude curves
  - Select optimizer and compare results
  - Display optimized parameters (frequency, damping, force)

- 📊 **Data Filtering & Preprocessing**:
  - Thresholding low amplitude values
  - Automatic initial guess generation

---

## 📦 Technologies Used

- Python 3
- `numpy`, `pandas`, `matplotlib`
- `scipy.optimize` (for various optimizers)
- `tkinter` / `PyQt5` (GUI framework - depending on your implementation)
- JupyterLab for data exploration and development

---

## 🏁 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/MilanMavani/One-Mass-Oscillator-Optimization.git
   cd One-Mass-Oscillator-Optimization
2. Install dependencies:
   ```bash
    pip install -r requirements.txt

## 📂 Poject Structure
  ```bash
    ├── gui.py                  # GUI application
    ├── optimization.py         # Optimization functions
    ├── one_mass_model.py       # Core oscillator model
    ├── df1.pkl / df2.pkl       # Input data files which is not added due to confidentiality
    ├── README.md               # This file

