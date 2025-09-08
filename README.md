<h1 align="center">🔋 Generative DRL EIS Recovery</h1>

<p align="center">
<em>Generative Deep Reinforcement Learning for Electrochemical Impedance Spectroscopy (EIS) State Recovery – PyTorch Implementation</em>
</p>

---

## 📌 Project Overview
**Electrochemical Impedance Spectroscopy (EIS)** is an essential diagnostic tool in **battery systems**, **fuel cells**, and **material degradation studies**.  
This repository demonstrates how **Generative Deep Reinforcement Learning (DRL)** can recover **missing or corrupted EIS states** using a **PyTorch**-based pipeline.

---

## 📂 Repository Structure

- **`data/`** – Raw EIS state datasets (`EIS_state_1.xlsx` – `EIS_state_5.xlsx`)  
  **Columns:**
  - `Frequency` *(Hz)*
  - `Z_real` – Real impedance Z′ *(Ω)*
  - `Z_imag` – Imaginary impedance Z″ *(Ω)*
  
- **`notebooks/`** – Jupyter notebooks for:
  - Data loading & preprocessing
  - PyTorch DRL model training
  - EIS state recovery visualization  
  **Main notebook:** `generative_DRL_EIS_Recovery.ipynb`

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/YoungwoongYoun/generative-DRL-EIS-recovery.git
cd generative-DRL-EIS-recovery

# Install dependencies
pip install numpy pandas matplotlib jupyter torch

