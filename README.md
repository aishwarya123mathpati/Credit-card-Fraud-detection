# Credit-card-Fraud-detection

## Project Overview
This project focuses on detecting fraudulent transactions in credit card data using machine learning. The dataset is highly imbalanced, and this project demonstrates techniques to handle such challenges.

## Dataset
- **Source**: [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- The dataset contains 284,807 transactions, with 492 fraudulent cases (Class 1).

## Methodology
1. **Data Preprocessing**:
   - Standardized the `Amount` feature.
   - Dropped irrelevant features (`Time`, `Amount`).

2. **Modeling**:
   - Used a Random Forest Classifier for fraud detection.
   - Split data into 80% training and 20% testing.
   - Handled class imbalance using stratified sampling.

3. **Evaluation**:
   - Metrics: Confusion Matrix, Classification Report, and Accuracy Score.
4. **Dependencies**

  - pandas
  - numpy
  - scikit-learn
  - joblib
