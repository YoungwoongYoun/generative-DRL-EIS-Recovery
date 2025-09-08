<h1 align="center">🔋 Generative DRL EIS Recovery</h1>

<p align="center">
<em>Generative Deep Reinforcement Learning for Electrochemical Impedance Spectroscopy (EIS) State Recovery</em>
</p>

---

## 📌 Project Overview
**Electrochemical Impedance Spectroscopy (EIS)** is widely used in **battery diagnostics**, **fuel cell monitoring**, and **material degradation analysis**.  
However, EIS measurements are often incomplete or noisy.  
This project explores **generative deep reinforcement learning (DRL)** approaches to **recover or reconstruct missing EIS states** from partial measurements.

---

## 📂 Repository Structure

- **`data/`** – Excel files with EIS state data:  
  `EIS_state_1.xlsx` – `EIS_state_5.xlsx`  
  **Columns:**
  - Frequency *(Hz)*
  - Real impedance **Z′ (Ω)**
  - Imaginary impedance **Z″ (Ω)**
  
- **`notebooks/`** – Jupyter notebooks for analysis and model training:  
  - `generative_DRL_EIS_Recovery.ipynb`

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/your-username/generative-DRL-EIS-recovery.git
cd generative-DRL-EIS-recovery

# Install dependencies
pip install numpy pandas tensorflow matplotlib jupyter
