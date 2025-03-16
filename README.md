
# Loan Default Prediction - Machine Learning Model


📌 Project Overview


This project aims to develop a machine learning model to predict loan defaults based on customer financial and demographic data. It uses advanced predictive analytics to help financial institutions assess loan risks effectively.
📂 Project Structure

├── data/                  # Raw and processed datasets
├── notebooks/             # Jupyter notebooks for EDA and modeling
├── models/                # Saved trained models
├── src/                   # Source code for data processing & training
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── train_model.py
│   ├── evaluate_model.py
│   ├── deploy_model.py
├── requirements.txt       # List of dependencies
├── README.md              # Project documentation


🚀 Key Features

Data Preprocessing: Handles missing values, outliers, and categorical encoding.
Feature Engineering: Creates relevant financial risk indicators.
Imbalanced Handling: Uses SMOTE and class weighting.
Machine Learning Models:
Logistic Regression
Random Forest
XGBoost (Best Performing)
Support Vector Machine (SVM)
Evaluation Metrics:
Accuracy, Precision, Recall, F1-score
AUC-ROC Curve, Confusion Matrix
Model Deployment: Flask/FastAPI for real-time scoring.


📊 Dataset Overview

Feature	Description
Credit Score	Numeric score representing creditworthiness
Annual Income	Borrower’s yearly income
Loan Amount	Total loan requested
Debt-to-Income Ratio	Monthly debt payments divided by monthly income
Employment Length	Number of years employed
Default Status (Target)	1 = Default, 0 = No Default


🔧 Installation & Setup

Clone the repository:
git clone https://github.com/your-repo/loan-default-prediction.git
cd loan-default-prediction
Install dependencies:
pip install -r requirements.txt
Run the model training:
python src/train_model.py
Evaluate the model:
python src/evaluate_model.py


📈 Results

Best Model: XGBoost with 98% AUC-ROC and low false negatives.
Feature Importance: Credit score, debt-to-income ratio, and income are the strongest predictors.
Deployment: The trained model can be deployed as an API for real-time predictions.


📌 Next Steps

Improve feature engineering (e.g., credit utilization ratio).
Integrate real-time scoring API with financial applications.
Monitor model drift for periodic retraining.


👨‍💻 Contributors
Nawaraj Adhikari

Feel free to contribute by submitting a pull request!
