
# Credit Risk Modeling

This project explores and builds models to predict the probability of a customer defaulting on their credit payments. It uses machine learning techniques and handles class imbalance to improve model performance.

## Dataset
The dataset used is from the UCI Credit Card Default Dataset, which includes features such as credit limit, payment history, and customer demographics.

[Dataset]([URL](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset?resource=download))

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


### Random Forest:
- **Accuracy**: 79.82%


### XGBoost:
- **Accuracy**: 80.18%


The models provide insights into customer default risks, with XGBoost and Random Forest showing the highest accuracy.
