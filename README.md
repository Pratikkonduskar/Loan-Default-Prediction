# Loan Default Prediction

## Overview

This project predicts the likelihood of loan default using the German Credit Dataset. The objective was to develop a machine learning solution capable of identifying high-risk borrowers and supporting data-driven lending decisions.

The project focuses not only on model accuracy but also on maximizing recall to reduce the risk of approving potentially risky applicants.

---

## Problem Statement

Financial institutions face significant losses when borrowers default on loans. Identifying high-risk applicants early can improve risk management and lending strategies.

This project uses machine learning techniques to predict whether a borrower is likely to default based on historical credit information.

---

## Features

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training and Evaluation
* Hyperparameter Tuning
* Threshold Optimization
* Risk Classification

---

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## Machine Learning Pipeline

Data Collection → Preprocessing → EDA → Feature Engineering → Model Training → Hyperparameter Tuning → Threshold Optimization → Prediction

---

## Models Evaluated

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting

Gradient Boosting achieved the strongest overall performance and was selected as the final model.

---

## Key Results

* Best Model: Gradient Boosting Classifier
* PR-AUC: 0.615
* Recall Improved: 0.48 → 0.79 through threshold optimization
* Significant reduction in false negatives

The focus on recall ensured that potentially risky borrowers were identified more effectively.

---

## Challenges Faced

* Balancing precision and recall.
* Handling limited dataset size.
* Selecting appropriate evaluation metrics.
* Understanding business trade-offs in credit risk prediction.

---

## Key Learnings

* Credit risk modeling fundamentals.
* Hyperparameter tuning using GridSearchCV.
* Threshold optimization techniques.
* Precision-Recall trade-offs.
* Business-oriented model evaluation.

---

## Future Improvements

* Ensemble modeling approaches.
* Model explainability using SHAP.
* Real-time API deployment.
* Automated risk reporting dashboards.

---

## Author

Pratik Konduskar

GitHub: https://github.com/pratikkonduskar
LinkedIn: https://www.linkedin.com/in/pratik-konduskar
