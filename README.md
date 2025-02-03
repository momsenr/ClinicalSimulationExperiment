# Mitigation of Outcome Conflation in Predicting Patient Outcomes Using Electronic Health Records

**Authors**: S. Momsen Reincke, Camilo Espinosa, Philip Chung, Tomin James, Eloïse Berson, Nima Aghaeepour

## Introduction

This repository accompanies the paper "Mitigation of Outcome Conflation in Predicting Patient Outcomes Using Electronic Health Records". This notebook contains all the code and analyses to run the clinical simulation experiment. Additionally, we provide the models and results that were used to generate the dataset in Figure 2 and Supplementary Figure S9.

## Requirements

To run this notebook, ensure that you have the following packages installed:
- python (3.11)
- pytorch (2.0.0)
- cudatoolkit (11.8)
- numpy
- matplotlib
- seaborn
- torch
- sklearn
- scipy
- pickle
- scikit-learn

To install all dependencies with conda, you can use:

```bash
conda env create -f environment.yml
conda activate clinical_simulation
```

After this, start a jupyter notebook session and run ClinicalSimulationExperiment.ipynb.
.
