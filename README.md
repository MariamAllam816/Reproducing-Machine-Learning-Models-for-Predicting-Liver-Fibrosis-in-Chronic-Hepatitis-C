# Reproducing-Machine-Learning-Models-for-Predicting-Liver-Fibrosis-in-Chronic-Hepatitis-C
This repository contains a full end-to-end reproduction attempt of the machine learning workflow described in the following peer-reviewed paper:

Akella A., & Akella S. (2020)
Applying Machine Learning to Evaluate for Fibrosis in Chronic Hepatitis C. bioRxiv. 
DOI: https://doi.org/10.1101/2020.11.02.20224840

🔗 Paper link: https://www.medrxiv.org/content/10.1101/2020.11.02.20224840v1

Project Goal

The goal of this notebook is to replicate the experimental pipeline used in the paper to evaluate multiple machine-learning algorithms for detecting significant/advanced liver fibrosis in Egyptian HCV patients.

Specifically, the notebook:

Loads and preprocesses the original HCV Egyptian Cohort Dataset

Reconstructs the three classification experiments (A, B, C) exactly as described

Performs oversampling, standardization, and hyperparameter tuning

Trains 9 ML models:

Logistic Regression

Naïve Bayes

Decision Tree

Random Forest

Extreme Gradient Boosting

k-Nearest Neighbors

Support Vector Machine

Multi-Layer Perceptron

Soft Voting Ensemble

Evaluates each model using:

Accuracy

Precision

Recall

F1 Score

AUC (when applicable)

Confusion Matrix

The pipeline closely follows the methodology reported in the original study.

Dataset Used

The dataset used in this notebook is the official UCI release of the HCV Egyptian Cohort:

🔗 Hepatitis C Virus (HCV) for Egyptian Patients Dataset — UCI Machine Learning Repository
https://archive-beta.ics.uci.edu/dataset/503/hepatitis+c+virus+hcv+for+egyptian+patients

n = 1,385 patients

28 clinical and laboratory features

Includes histological fibrosis staging (F1–F4)

Only one files was used:

HCV-Egy-Data.csv

What This Notebook Demonstrates

Understanding of proper ML experiment setup

Ability to reconstruct published methods

Handling class imbalance, feature selection, and hyperparameter tuning

Comparing multiple model families under controlled conditions

Extracting evaluation metrics and visualizing results

Reproducibility of scientific ML research
