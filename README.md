# Customer-Churn-Prediction

## Project Overview
This project aims to predict **customer churn** in a telecom company using **machine learning models**. The dataset consists of customer demographics, account details, and service usage information.

## Dataset
We use the **Telecom Customer Churn dataset** available [here](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

### Features:
- **Customer Information**: Gender, tenure, contract type, payment method, etc.
- **Service Details**: Internet service, phone service, additional features.
- **Financial Data**: Monthly charges, total charges.
- **Target Variable**: `Churn` (1 if the customer left, 0 otherwise)

## Project Workflow
### 1. Data Preprocessing
- Dropped **irrelevant columns** like `customerID`.
- Converted **categorical features** into numerical values.
- **Scaled** numerical features for better model performance.

### 2. Model Training & Evaluation
Implemented and compared multiple models:
- **Logistic Regression** ✅
- **Random Forest Classifier** ✅
- **XGBoost Classifier** ✅

### 3. Model Performance
- **Accuracy Score**: Evaluated model performance on test data.
- **Confusion Matrix**: Visualized true positives, false positives, etc.
- **Classification Report**: Checked precision, recall, and F1-score.

## Installation & Setup
To run this project, install the required libraries:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```
Run the Jupyter Notebook:
```sh
jupyter notebook customer_churn_prediction.ipynb
```

## Results & Insights
- **Churn Drivers**: Contract type, payment method, and monthly charges impact churn rates the most.
- **Best Model**: XGBoost outperformed other models with higher accuracy.
- **Recommendations**: Offer discounts on long-term contracts, improve customer support.

## Contribution
Feel free to fork this repository, improve the model, and submit pull requests!

## License
This project is open-source under the MIT License.

