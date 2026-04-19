[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19633120.svg)](https://doi.org/10.5281/zenodo.19633120)

This repository contains the source code, datasets and complete results as a supplement to the paper: 'Power Plant Efficiency Prediction Using MrMiMaxG Feature Engineering and Consensus Voting Mechanism'.

# A. Prediction Results Table

1. Boiler Efficiency Prediction Results Table
2. NPHR Prediction Results Table
3. WPPS Weight Percentage Reasoning

# B. Model Prediction Source Code and Results

The following table summarizes the experimental configurations across different datasets and feature engineering scenarios. Each configuration was tested using nine different models (M1–M9) for both **Boiler Efficiency** and **Net Plant Heat Rate (NPHR)**.

|      ID      | Dataset Source | Description                    |  Feature Engineering  | Target Variables |  Models  |
| :-----------: | :------------- | :----------------------------- | :--------------------: | :--------------: | :------: |
| **b.1** | Dataset 1 (D1) | Operational Dataset            |      None (No FE)      | Boiler Eff, NPHR | M1 – M9 |
| **b.2** | Dataset 2 (D2) | Emission Dataset               |      None (No FE)      | Boiler Eff, NPHR | M1 – M9 |
| **b.3** | Dataset 3 (D3) | Operational + Emission Dataset |      None (No FE)      | Boiler Eff, NPHR | M1 – M9 |
| **b.4** | Dataset 4 (D4) | D1 Selected Features           | **MrMiMaxG-CVM** | Boiler Eff, NPHR | M1 – M9 |
| **b.5** | Dataset 5 (D5) | D2 Selected Features           | **MrMiMaxG-CVM** | Boiler Eff, NPHR | M1 – M9 |
| **b.6** | Dataset 6 (D6) | D3 Selected Features           | **MrMiMaxG-CVM** | Boiler Eff, NPHR | M1 – M9 |
| **b.7** | Dataset 4 (D4) | D1 Selected Features           |     **EFA**     | Boiler Eff, NPHR | M1 – M9 |
| **b.8** | Dataset 5 (D5) | D2 Selected Features           |     **Corr**     | Boiler Eff, NPHR | M1 – M9 |
| **b.9** | Dataset 6 (D6) | D3 Selected Features           |     **EFA**     | Boiler Eff, NPHR | M1 – M9 |

> **Note:** Models M1 through M9 represent the different machine learning algorithms used in this study (e.g., XGBoost, Stacking Regressor, etc.). Above tabel to use make file name with code (e.g., b.1 - D1 - Boiler Efficiency - M1. This file used for ID b.1, Dataset 1 (D1), for target Boiler Efficiency and model prediction using M1).
