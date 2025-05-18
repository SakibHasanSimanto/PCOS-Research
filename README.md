# Trustworthy ML for Healthcare Diagnosis Using Tabular Deep Neural Networks and Causal Inference: Application to PCOS Diagnosis

## Overview

This repository presents a framework for developing trustworthy machine learning models for healthcare diagnosis, with a focus on Polycystic Ovary Syndrome (PCOS). The approach integrates tabular deep neural networks with causal inference techniques to enhance reliability and interpretability in clinical settings.

## Data Information

The repository contains several `.csv` files used in various stages of model development:

- **PCOS_data_simple.csv** – The original dataset sourced from Kaggle.
- Additional preprocessed datasets – Derived from the original data for downstream tasks such as modeling and analysis.

> For detailed preprocessing steps, please refer to the corresponding code notebooks.

## Code Information

The project is structured into multiple Jupyter notebooks, each representing a distinct phase of the pipeline:

- **`PCOS Diagnosis Phase 1.ipynb`**  
  Data preparation and preprocessing.  
  *[Phase 1]*

- **`PCOS Diagnosis Phase 2.ipynb`**  
  Implementation of various models including:  
  - Classical ML models  
  - Advanced tabular deep learning models  
  - Prototypical networks  
  - Model-Agnostic Meta-Learning (MAML)  
  *[Phase 2]*

- **`PCOS Diagnosis Phase 2: Causal ML.ipynb`**  
  Causal inference modeling using the CNBE (Causal Neural Bayesian Estimator) approach.

- **`PCOS Diagnosis Phase 3: Bayesian Neural Network.ipynb`**  
  Development and evaluation of Bayesian Neural Network models.  
  *[Phase 3]*

- **`PCOS Diagnosis System 1.ipynb`**  
  Documentation and accessibility of all models *except* CNBE.  
  *[Clinical Utility A]*

- **`PCOS Diagnosis System 2.ipynb`**  
  Documentation and accessibility for the CNBE model.  
  *[Clinical Utility B]*





