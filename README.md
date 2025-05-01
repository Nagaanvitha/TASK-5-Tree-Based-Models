# TASK-5-Tree-Based-Models
Decision trees &amp; Ensemble learning- Heart Disease Model

# Heart Disease Prediction Using Machine Learning
This project uses machine learning models to predict the presence of heart disease based on patient data. The dataset includes clinical attributes such as age, sex, chest pain type, cholesterol level, and more. The goal is to classify whether a patient is likely to have heart disease.

# Dataset
Source: Kaggle - Heart Disease Dataset

File: heart.csv

Target column: target (1 = presence of heart disease, 0 = absence)

# Features
Numerical: age, trestbps, chol, thalach, oldpeak

Categorical (One-hot encoded): cp, restecg, slope, ca, thal

Binary: sex, fbs, exang

# Project Structure
Data loading and exploration: Load dataset, visualize distributions, check for missing values.

Preprocessing pipeline:

Scale numerical features.

One-hot encode categorical features.

Pass through binary features.

Model training: Train and evaluate three models:

Logistic Regression

Random Forest

Support Vector Machine (SVM)

Evaluation:

Accuracy, confusion matrix, classification report

ROC AUC score and ROC curve plots

Model comparison summary

# Results
Visual comparison using ROC curves.

Accuracy and ROC AUC reported for each model.

Random Forest and SVM generally perform better due to their ability to capture non-linear relationships.

# How to Run
Download the dataset from Kaggle and place heart.csv in the appropriate directory.

Run the notebook cell-by-cell. Make sure necessary packages are installed (pandas, scikit-learn, seaborn, etc.).

Results and plots will be displayed during execution.

# Requirements
Python 3.7+

pandas

numpy

scikit-learn

matplotlib

seaborn

Install dependencies:

bash
Copy
Edit
pip install pandas numpy scikit-learn matplotlib seaborn
# Future Improvements
Add cross-validation for more robust model evaluation.

Tune hyperparameters using GridSearchCV or RandomizedSearchCV.

Include SHAP or LIME for model explainability.
