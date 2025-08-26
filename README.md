# Breast Cancer Prediction Web App

## Project Overview
This web application predicts whether a patient has breast cancer based on clinical and cytological measurements. Using machine learning (XGBoost), the app outputs the probability of cancer and provides key metrics to assess model performance.

## Features
- Predict probability of breast cancer (0–1)
- Display model performance metrics:
  - **Accuracy** – Overall correctness
  - **ROC-AUC** – Model discrimination ability
  - **Recall / Sensitivity** – Detecting actual cancer cases
  - **Specificity** – Correctly identifying healthy patients
  - **Confusion Matrix** – Counts of TP, TN, FP, FN
- Future enhancement: Upload histopathology images to automatically extract features

## Dataset
- **Wisconsin Breast Cancer Dataset (WBCD)**
- **Samples:** 569
- **Features:** 30 numerical features per patient (e.g., `radius_mean`, `perimeter_mean`, `area_mean`, `smoothness_mean`, `concavity_mean`, `fractal_dimension_mean`)

## Model
- **XGBoost Classifier**
- **Performance:** Accuracy ≈ 0.97, ROC-AUC ≈ 0.97
- Trained on numerical features from WBCD
