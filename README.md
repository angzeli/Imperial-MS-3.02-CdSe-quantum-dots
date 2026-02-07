# 🔬 Imperial-MS-3.02 — CdSe Quantum Dots

## 📌 Overview

This repository contains the experimental documentation, analysis code, and figures for a Measurement Science laboratory investigating the optical properties of CdSe quantum dots (QDs).

The work focuses on extracting key physical parameters from spectroscopic data and relating them to quantum confinement and nanocrystal growth mechanisms.

It supports both data analysis and viva preparation, and includes the full Python analysis pipeline, generated figures, and presentation materials.

---

## 🧪 Experiment Summary

CdSe quantum dots were synthesised via the hot-injection method and characterised using optical spectroscopy techniques:
- 🔹 UV–Vis absorption spectroscopy
- 🔹 Photoluminescence (PL) emission spectroscopy
- 🔹 Excitation spectroscopy

The experimental objective is to connect spectral features to particle size, band-gap energy, and growth behaviour, using established physical models.

---

## 📊 Key Analysis Performed

The analysis pipeline includes:
- Pre-processing of raw UV–Vis and PL datasets
- Extraction of:
	- Band-edge absorption peaks
	- PL emission peaks
 	- Stokes shift
	- Full width at half maximum (FWHM)
- Estimation of:
	- Optical band-gap energy
	- Particle radius using the Brus equation
	- Comparison of size-dependent optical properties
- Growth mechanism analysis:
	- Diff️ Diffusion-controlled vs surface-controlled growth
	- Reaction-limited regimes
	- Ostwald ripening vs secondary nucleation
	- Comparison across different Cd:Se precursor ratios (1.33:1, 1:3, 1:5)

---

## 🗂 Repository Structure
```python
├── Data/                      # Raw and processed experimental datasets
├── Figures/                   # Generated plots and analysis figures
├── Python Analysis.ipynb      # Fully commented Jupyter notebook (main analysis)
├── MS.02 Quantum Dots Viva Slides.pdf
├── README.md
```

📈 All figures used in the notebook are fully reproducible from the provided code.

---

## 🔁 Reproducibility & Good Practice
- Analysis performed entirely in Python (Jupyter Notebook)
- All processing steps are clearly commented
- Both raw and processed datasets are included
- Figures are generated programmatically for consistency


---

## ⚙️ Requirements
- Python 3.x
- Standard scientific Python stack:
	- numpy
	- matplotlib
