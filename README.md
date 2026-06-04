# CodeAlpha: Credit Scoring Model (Task 1)

## Project Overview
This repository contains the solution for Task 1 of my Machine Learning Internship at CodeAlpha. The objective of this project is to predict an individual's creditworthiness (Good or Bad credit risk) using historical financial data.

## Workflow Followed:
1. **Data Loading:** Used the German Credit Risk dataset loaded via Pandas DataFrame.
2. **Data Preprocessing:** Handled categorical textual data using One-Hot Encoding (`pd.get_dummies`).
3. **Data Splitting:** Divided the processed dataset into an 80:20 ratio for Training and Testing using `train_test_split`.
4. **Model Training:** Trained a `RandomForestClassifier` on the training dataset.
5. **Model Evaluation:** Evaluated performance using Precision, Recall, F1-Score, and ROC-AUC.

## Model Performance Results:
- **Overall Accuracy:** 78%
- **True (Good Credit) F1-Score:** 0.86
- **ROC-AUC Score:** 0.7449

## Technologies Used:
- Python 3
- Google Colab
- Pandas & NumPy
- Scikit-Learn
