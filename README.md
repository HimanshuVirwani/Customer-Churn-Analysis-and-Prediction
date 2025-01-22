# Customer-Churn-Analysis-and-Prediction

This project analyzes customer behavior and churn across two datasets: `ecommerce_customer_data` and `internet_service_churn`. The analysis involves data preprocessing, visualization, and churn prediction using multiple machine learning models to identify the best-performing model for each dataset.

---

## Project Overview

1. **Data Preprocessing**
   - Handle missing values.
   - Drop irrelevant columns.
   - Merge datasets on `Customer_id`.

2. **Data Visualization**
   - Churn distribution across datasets.
   - Churn distribution by gender and age group.
   - Payment method distribution.
   - Product category distribution.

3. **Feature Engineering**
   - Created custom age groups.
   - One-hot encoding for categorical features.
   - Standardized numerical features.

4. **Machine Learning**
   - Models used:
     - Random Forest
     - Gradient Boosting
     - Logistic Regression
     - Support Vector Machine (SVM)
     - XGBoost
   - Performance metrics: Accuracy, Precision, Recall, and F1 Score.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git

2. Install required libraries:
   ```bash
   pip install pandas seaborn matplotlib scikit-learn xgboost tabulate

## Datasets
Ecommerce Customer Data: ecommerce_customer_data_custom_ratios.csv
Internet Service Provider Churn Data: internet_service_churn.csv
