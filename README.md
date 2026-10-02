# CodeAlpha Credit Scoring Model

## Project Overview

This project is developed as part of the CodeAlpha Machine Learning Internship.

The objective is to build a machine learning model that predicts the credit risk of a customer as either **Good** or **Bad** based on financial and personal information.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Joblib
- Google Colab
- Random Forest Classifier

## Dataset

The project uses a German Credit Risk dataset containing 1000 customer records.

The dataset includes features such as:

- Age
- Sex
- Job
- Housing
- Saving Accounts
- Checking Account
- Credit Amount
- Duration
- Purpose

The target variable is **Risk**, with two classes:

- Good
- Bad

## Data Preprocessing

The following preprocessing steps were performed:

1. Handled missing values.
2. Replaced missing categorical values with `Unknown`.
3. Removed the unnecessary index column.
4. Separated features and target.
5. Split the dataset into training and testing data.
6. Applied One-Hot Encoding to categorical features.

## Machine Learning Model

A **Random Forest Classifier** was used for credit risk prediction.

The dataset was divided into:

- Training data: 80% (800 records)
- Testing data: 20% (200 records)

## Model Performance

| Metric | Score |
|---|---:|
| Accuracy | 76% |
| Precision | 61.54% |
| Recall | 53.33% |
| F1 Score | 57.14% |
| ROC-AUC | 0.7615 |

## Feature Importance

The most important features in the trained Random Forest model included:

1. Credit Amount
2. Age
3. Duration
4. Checking Account
5. Job

## Project Files

- `CodeAlpha_credit_Scoring_Model.ipynb` — Complete Google Colab notebook
- `credit_risk_random_forest.pkl` — Trained Random Forest model
- `README.md` — Project documentation

## Conclusion

The project demonstrates how machine learning can be used to predict credit risk from customer financial and demographic information. Random Forest was trained and evaluated using multiple classification metrics including Accuracy, Precision, Recall, F1 Score and ROC-AUC.

## Internship

Developed as part of the **CodeAlpha Machine Learning Internship**.
