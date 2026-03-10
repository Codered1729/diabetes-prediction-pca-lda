# Diabetes Prediction using PCA and LDA

This project explores dimensionality reduction techniques and their impact on classification performance using the Diabetes dataset.

## Objective

Compare two dimensionality reduction techniques:

- Principal Component Analysis (PCA)
- Linear Discriminant Analysis (LDA)

and evaluate their performance using Logistic Regression.

## Dataset

Pima Indians Diabetes Dataset

Features include:

- Glucose
- Blood Pressure
- BMI
- Insulin
- Age
- Diabetes Pedigree Function

Target variable: Outcome (0 = Non-diabetic, 1 = Diabetic)

## Methods Used

- Data preprocessing and feature scaling
- Dimensionality reduction (PCA and LDA)
- Logistic Regression classification
- Model evaluation using accuracy and classification report

## Results

| Method | Accuracy |
|------|------|
| PCA + Logistic Regression | 70% |
| LDA + Logistic Regression | 77% |

LDA performed better due to supervised dimensionality reduction.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

## Visualization

PCA projection of the dataset:

(Add scatter plot image here)

## Future Improvements

- Try advanced models (Random Forest, XGBoost)
- Perform hyperparameter tuning
- Deploy as a web application
