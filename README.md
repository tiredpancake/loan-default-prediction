# Loan Default Prediction Using Machine Learning

## Overview

This project predicts loan defaults using several supervised machine learning algorithms. The objective is to compare different classification models and identify the most effective approach for predicting whether a loan is likely to default.

## Dataset

The project uses a loan dataset containing borrower information and loan-related features. The target variable is:

- **bad_loans** (0 = non-default, 1 = default)

Selected features:

- grade
- term
- home_ownership
- emp_length

## Data Preprocessing

The following preprocessing steps were applied:

- Missing value handling
- Label Encoding for categorical features
- Train / Validation / Test split
- Min-Max feature scaling
- Class balancing using SMOTE

## Machine Learning Models

The following models were trained and evaluated:

- Decision Tree
- K-Nearest Neighbors (KNN)
- AdaBoost
- Random Forest

## Hyperparameter Tuning

Model parameters were optimized using validation data.

Examples:

- Decision Tree: max_depth
- KNN: number of neighbors (k)
- AdaBoost: n_estimators
- Random Forest: GridSearchCV

## Evaluation

Models were compared using classification accuracy on the test dataset.

The project also visualizes:

- Model performance comparison
- Decision Tree structure

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Imbalanced-learn (SMOTE)

## How to Run

```bash
pip install -r requirements.txt
python main.py
```

## Learning Outcomes

This project demonstrates:

- Data preprocessing
- Feature engineering basics
- Handling imbalanced datasets
- Hyperparameter tuning
- Model comparison and evaluation
- Practical machine learning workflow

```

```
