
# Credit Risk Modeling

This project explores and builds models to predict the probability of a customer defaulting on their credit payments. It uses machine learning techniques and handles class imbalance to improve model performance.

## Dataset
The dataset used is from the UCI Credit Card Default Dataset, which includes features such as credit limit, payment history, and customer demographics.

## Key Features:
- **Preprocessing**: 
  - Data cleaning (removing unnecessary columns, handling missing values)
  - Feature scaling using `StandardScaler`
  - Handling class imbalance with `SMOTE`
  
- **Models Implemented**:
  - Logistic Regression
  - Random Forest
  - XGBoost

- **Evaluation Metrics**: 
  - Classification report
  - Accuracy score

## Libraries Used:
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn` (for model training and evaluation)
- `xgboost`
- `imbalanced-learn` (for handling class imbalance)

## Results:
The models provide insights into customer default risks, with comparisons between the different algorithms' performance based on accuracy and other classification metrics.
