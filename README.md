
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

### Logistic Regression:
- **Accuracy**: 68.67%
- **Classification Report**:
  ```
              precision    recall  f1-score   support

           0       0.88      0.69      0.78      4687
           1       0.38      0.66      0.48      1313

    accuracy                           0.69      6000
   macro avg       0.63      0.68      0.63      6000
weighted avg       0.77      0.69      0.71      6000
  ```

### Random Forest:
- **Accuracy**: 79.82%
- **Classification Report**:
  ```
              precision    recall  f1-score   support

           0       0.86      0.89      0.87      4687
           1       0.55      0.47      0.50      1313

    accuracy                           0.80      6000
   macro avg       0.70      0.68      0.69      6000
weighted avg       0.79      0.80      0.79      6000
  ```

### XGBoost:
- **Accuracy**: 80.18%
- **Classification Report**:
  ```
              precision    recall  f1-score   support

           0       0.85      0.91      0.88      4687
           1       0.56      0.42      0.48      1313

    accuracy                           0.80      6000
   macro avg       0.71      0.66      0.68      6000
weighted avg       0.79      0.80      0.79      6000
  ```

The models provide insights into customer default risks, with XGBoost and Random Forest showing the highest accuracy.
