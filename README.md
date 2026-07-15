# UNSW-NB15 Machine Learning Labs

## Overview

This repository contains a collection of Machine Learning laboratory experiments performed using the UNSW-NB15 Network Intrusion Detection Dataset. The project serves as a centralized workspace for exploring and implementing various machine learning concepts in the domain of cybersecurity and network intrusion detection.

The repository will be continuously updated with new laboratory exercises, experiments, visualizations, and model implementations throughout the course.

---

## Dataset

**Dataset:** UNSW-NB15 Network Intrusion Detection Dataset

The UNSW-NB15 dataset was developed by the Australian Centre for Cyber Security (ACCS) and contains both normal network traffic and multiple categories of cyberattacks. It is widely used for research in intrusion detection systems and cybersecurity-focused machine learning applications.

**Dataset Source:**
https://www.kaggle.com/datasets/dhoogla/unswnb15

---

## Project Objectives

* Explore Machine Learning concepts using a real-world cybersecurity dataset.
* Perform data preprocessing and cleaning.
* Apply feature engineering techniques.
* Evaluate different feature selection methods.
* Compare feature scaling techniques.
* Build and evaluate machine learning models for intrusion detection.
* Analyze network traffic patterns and attack behavior.
* Gain practical experience in cybersecurity-focused data science workflows.

---

## Topics Covered

### Data Preparation

* Data Loading
* Data Cleaning
* Duplicate Detection and Removal
* Missing Value Analysis
* Data Exploration

### Feature Engineering

* Traffic-based Feature Creation
* Packet Statistics
* Network Flow Metrics
* Custom Cybersecurity Features

### Feature Selection

* Correlation Analysis
* Mutual Information
* SelectKBest
* Random Forest Feature Importance

### Feature Scaling

* StandardScaler
* MinMaxScaler
* RobustScaler

### Machine Learning

* Logistic Regression
* Decision Trees
* Random Forests
* Support Vector Machines (Future)
* K-Nearest Neighbors (Future)

### Advanced Topics

* Dimensionality Reduction (PCA)
* Attack Classification
* Anomaly Detection
* Model Explainability
* Cybersecurity Analytics

---

## Repository Structure

```text
unsw-nb15-machine-learning-labs/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── dataset/
│   └── dataset_link.txt
│
├── notebooks/
│   └── UNSW_NB15_Feature_Engineering_Selection_Scaling.ipynb
│
├── reports/
│   ├── UNSW-NB15_Preprocessing_Report.docx
│
└── images/
    ├── slide01_cover.png
    ├── slide02_dataset_overview.png
    ├── slide03_data_exploration.png
    ├── slide04_data_cleaning.png
    ├── slide05_feature_engineering.png
    ├── slide06_feature_selection.png
    ├── slide07_feature_scaling.png
    └── slide08_pipeline.png
```

---

## Current Work

### Lab 1: Feature Engineering, Selection, and Scaling

Implemented:

* Duplicate analysis and removal
* Feature engineering for network traffic metrics
* Feature selection using Mutual Information
* Feature importance analysis using Random Forest
* Feature scaling using:

  * StandardScaler
  * MinMaxScaler
  * RobustScaler
* Binary intrusion detection using machine learning models

---
---
## Repository Contents

| Resource | Description |
|-----------|------------|
| Jupyter Notebook | Complete implementation of preprocessing, feature engineering, feature selection, and scaling |
| Preprocessing Report | Detailed explanation of methodology, results, and observations |
| Carousel Infographic | Visual storytelling of the dataset preprocessing journey |
| Dataset Source | Kaggle link for UNSW-NB15 dataset |
| Visual Assets | Carousel slides and project graphics |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook
* Kaggle

---

## Future Improvements

* Multi-class attack classification using `attack_cat`
* Intrusion Detection System (IDS) simulation
* Anomaly detection using Isolation Forest
* PCA visualization of attack clusters
* Explainable AI using SHAP
* Streamlit dashboard for cybersecurity analytics

---

## Disclaimer

This repository is intended for educational and research purposes. The dataset is publicly available and belongs to its respective creators. All experiments are conducted solely for learning machine learning and cybersecurity concepts.

---
---
## Key Results

- Original Records: 175,341
- Duplicate Records Removed: 78,519
- Remaining Records: 96,822
- Missing Values: 0
- New Features Created: 4
- Features Selected: Top 20 Features
- Scaling Techniques Evaluated:
  - StandardScaler
  - MinMaxScaler
  - RobustScaler
- Machine Learning Task: Binary Intrusion Detection
---
## Author

Machine Learning and Cybersecurity Laboratory Repository based on the UNSW-NB15 Dataset.
