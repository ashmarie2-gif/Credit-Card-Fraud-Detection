# Credit-Card-Fraud-Detection
Credit card fraud detection using machine learning (Random Forest & Logistic Regression)

## Overview
This project analyzes credit card transactions to detect fraudulent activity using machine learning models. Fraud detection is critical in financial services, where missed fraud can result in financial loss.

## Dataset
The dataset contains anonymized transaction data with 31 features. The target variable "Class" indicates:
- 0 → Non-fraud
- 1 → Fraud

The dataset is highly imbalanced, with fraudulent transactions making up less than 1% of the data.

## Approach
- Performed exploratory data analysis (EDA)
- Addressed class imbalance using undersampling
- Built and compared two models:
  - Random Forest
  - Logistic Regression
- Evaluated performance using:
  - Confusion Matrix
  - ROC Curve
  - Precision-Recall Curve

## Results
- Both models achieved strong performance (AUC ~ 0.98–0.99)
- High recall ensured most fraudulent transactions were detected
- Both models produced similar results, indicating the dataset is highly separable

## Key Insights
- Fraud detection requires focusing on recall to minimize missed fraud
- Logistic Regression performed similarly to Random Forest, making it a simpler and interpretable alternative
- Feature importance analysis highlighted key variables influencing fraud detection

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Author
Ashley James
