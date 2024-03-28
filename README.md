# Lung-Cncer-Prediction-with-logistic-Regression
## Quick Start
This project utilizes logistic regression to distinguish between "Normal" and "Tumor" lung tissue samples based on gene expression data. It integrates datasets from four distinct studies into a singular analysis framework.

## Prerequisites
Python Libraries: pandas, matplotlib, seaborn, numpy, scikit-learn
Data: Available via Deep Learning for Genomics GitHub.
## Data Preparation
Merge: Datasets GSE87340, GSE60052, GSE40419, and GSE37764 are concatenated.
Clean: Remove samples with any missing values.
Standardize: Class labels normalized to "Normal" and "Tumor".
Refine: Extraneous columns, like 'ID', are discarded.
## Analysis Overview
EDA: Initial dataset inspection, class distribution visualization, and gene expression levels comparison.
Modeling: Logistic regression to classify samples, with a dataset split of 75% for training and 25% for testing.
Evaluation: Model accuracy, confusion matrix, and a detailed classification report.
## Execution Guide
Dataset Acquisition: Clone or download data from the specified GitHub repository.
Dependency Setup: Ensure all required libraries (pandas, matplotlib, seaborn, numpy, scikit-learn) are installed in your Python environment.
Run Analysis: Execute the analysis script from start to finish. This script includes data loading, preprocessing, EDA, model training, and evaluation steps.
## Outcomes
The logistic regression model's performance is quantified via test accuracy.
Model effectiveness is visually represented through a confusion matrix.
A classification report provides insights into the model's precision, recall, and F1-score.
