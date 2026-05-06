# Physics-Guided Machine Learning (PGML) and Data-Driven AHP for Centrifugal Pump Predictive Maintenance

This repository contains the source code, synthetic datasets (Digital Twin), and empirical validation data used in our research article.

## 📌 Project Overview
This project proposes a hybrid framework combining **System Dynamics (Digital Twin)**, **Random Forest Machine Learning**, and an **Autonomous Analytical Hierarchy Process (AHP)** to extract root causes of mechanical degradation in centrifugal pumps and autonomously formulate maintenance priorities without human expert bias.

## 📂 Repository Structure
* `Digital_Twin_PGML_Framework.ipynb`: The main Google Colab notebook containing Phase 1 (Data Generation) to Phase 4 (External Validation).
* `Dataset_Digital_Twin_Fixed.xlsx`: 4,000 hours of run-to-failure synthetic data generated via physical differential equations.
* `Centrifugal_pumps_measurements.csv`: Real-world condition monitoring benchmark data from Hellenic University.
* `/Figures/`: High-resolution visual outputs including Time-Series degradation, Confusion Matrix, 3D PCA Clustering, and Head-to-Head Radar Charts.

## 🚀 How to Run
1. Open the `.ipynb` file in Google Colab or Jupyter Notebook.
2. Ensure you have the required libraries installed (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).
3. Run the cells sequentially to reproduce the synthetic data, ML classification metrics, and AHP consistency ratios (CR < 0.10).

## 📊 Key Results
* **Machine Learning Accuracy:** 99.83% diagnostic precision across 4 failure states.
* **Autonomous AHP:** Successfully generated a highly consistent decision matrix (CR = 0.0131) directly from Gini Impurity values.
* **External Validation:** Achieved >90% structural root-cause overlap when benchmarked against real-world factory datasets.
