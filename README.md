# EEG-Based Indicators of Consciousness

This repository contains the code and materials for the Master's Thesis:
**"Indicators of consciousness based on Differential Equation Systems"**,  
authored by **J. Ángel Sayáns-Crespo** (2025), within the Master in Omics Data Analysis and Systems Biology (MADOBIS), University of Seville and UNIA.

## Overview

The project explores two main approaches to study states of consciousness from EEG data:

1. **Informational Structures (IS)** and **Invasion Graphs (IG)** based on Lotka–Volterra differential equations (implemented in R).
2. **Machine learning classifiers** (Random Forest and XGBoost) trained on EEG-derived time series features (implemented in Python).

The five studied conditions are: `wake`, `sleep`, `swsleep`, `xenon`, and `propofol`.

## Folder Structure

- `/R_scripts/` – Code for IS and IG generation  
- `/Python_scripts/` – ML training and evaluation scripts  
- `/data/` – EEG matrices (J, SS, JSS) [not included]  
- `/results/` – Output figures and performance metrics

## Requirements

### R (v4.4.2)
- tidyverse
- ggplot2
- car
- dunn.test
- R.matlab
- reticulate
- plotly
- stats

### Python (v3.11.12)
- numpy
- pandas
- matplotlib
- sklearn
- xgboost
- cesium

> 📌 Make sure to install all required packages before running the scripts.

## Data

The EEG data are from Massimini et al. (2005, 2010) and are not publicly available.  
They can be requested directly from the author.

## Code

- All code is organized and commented for clarity.  
- R was used for IS/IG modeling and statistical analysis.  
- Python was used for feature extraction and supervised classification.  
- Scripts are provided as `.R`, `.ipynb`, or `.py` files with example usage.

## Citation

If you use this material, please cite:

> Sayáns-Crespo, J. Ángel (2025). *Indicators of consciousness based on Differential Equation Systems*. Master’s Thesis, University of Seville and UNIA.

## Contact

For data access or questions, contact: **[añade tu email aquí]**


