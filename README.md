# Diabetes Prediction 

## Overview
This project uses a **Support Vector Machine (SVM)** classifier to predict whether a patient is diabetic, based on the **PIMA Diabetes Dataset**.

## Tech Stack
- Python
- NumPy & Pandas — data handling
- Scikit-learn — preprocessing, model training & evaluation

## Workflow
1. **Data Collection & Analysis** — Loaded and explored the PIMA Diabetes dataset (8 medical features + Outcome label).
2. **Data Standardization** — Scaled features using `StandardScaler` for better SVM performance.
3. **Train/Test Split** — Stratified split to preserve class balance.
4. **Model Training** — Trained an SVM classifier with a linear kernel.
5. **Evaluation** — Measured accuracy on both training and test sets.
6. **Prediction System** — Built a simple system to predict diabetes for new patient input data.

## Dataset
PIMA Indians Diabetes Dataset — 768 samples, 8 medical predictor features (e.g., Glucose, BMI, Age), with binary Outcome (0 = Non-Diabetic, 1 = Diabetic).

## Results
The model achieves solid accuracy in predicting diabetes based on patient health metrics.
