# Plotting of Gaussian Distribution with Matplotlib & LaTeX Fonts

This repository demonstrates how to make publication–ready plots using as an example the description of a **Gaussian distribution** in Python using `matplotlib`, with **Helvetica** and sans–serif fonts for both text and math elements, which is required by publishers such as *Nature*.

The script also highlights how to:
- Shade the ±1σ, ±2σ, and ±3σ confidence intervals.
- Add a secondary x–axis in **units of standard deviation**.
- Export plots in both **linear** and **logarithmic** scale.

---

## Features

- 📐 **Gaussian distribution visualization**  
  - User–defined mean `μ` and standard deviation `σ`.  
  - Shaded confidence regions with areas computed via numerical integration (`scipy.integrate.quad`).  

- 🎨 **Professional styling**  
  - Helvetica for text and sans–serif math fonts for equations.  
  - Seaborn color palette (`hls`) for consistent styling.  
  - Minor ticks, inward ticks, and publication–grade axis formatting.  

- 🔁 **Dual axis system**  
  - Bottom x–axis: variable in physical units.  
  - Top x–axis: deviation from the mean in multiples of σ.  

- ⚙️ **Flexible output**  
  - Linear and logarithmic y–axis versions.  
  - Export to both PDF and high–resolution PNG.  

---

## Requirements

- Python ≥ 3.7  
- A LaTeX distribution installed (e.g. TeX Live, MiKTeX) with the following packages:  
  - `helvet`  
  - `sansmathfonts`  
  - `upgreek`  
- Python dependencies:  

```bash
pip install numpy scipy matplotlib seaborn

---

## 📚 License
This project is licensed under the MIT License.
