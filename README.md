# ML Models for Liver Fibrosis Prediction
Reproducing and benchmarking ML classifiers for predicting liver 
fibrosis severity in Hepatitis C patients using the HCV Egyptian dataset.

## Results
| Model | AUC | Accuracy |
|-------|-----|----------|
| KNN | 0.646 | 58.9% |
| Random Forest | 0.605 | 57.4% |
| Ensemble | 0.606 | 55.4% |

MI-based feature selection outperformed ANOVA (AUC 0.518 vs 0.489).

## Methods
- Feature selection: Mutual Information vs ANOVA F-test comparison
- Class imbalance: SMOTE + random oversampling
- Validation: 10-fold cross-validation
- Models: LR, NB, DT, RF, XGBoost, KNN, SVM, MLP, Ensemble

## Dataset
HCV Egyptian Patients Dataset — clinical blood markers + histological staging

Handling class imbalance, feature selection, and hyperparameter tuning

Comparing multiple model families under controlled conditions

Extracting evaluation metrics and visualizing results

The dataset used in this notebook is the official UCI release of the HCV Egyptian Cohort:

🔗 Hepatitis C Virus (HCV) for Egyptian Patients Dataset — UCI Machine Learning Repository
https://archive-beta.ics.uci.edu/dataset/503/hepatitis+c+virus+hcv+for+egyptian+patients


Reproducibility of scientific ML research
