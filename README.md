# 📊 Customer Churn Prediction

This project aims to predict customer churn using various machine learning models. It leverages classification techniques to help businesses understand and reduce churn rates, which is crucial for customer retention strategies. Multiple ML Algorithms/Models have been employed which was later fed to a voting classifier to determine the best possible outcome. This Churn Prediction in applied on Ensemble Models.

## 📁 Project Structure

``` bash
├── Churn.ipynb          – Jupyter notebook containing the full pipeline from data preprocessing to model evaluation.
├── README.md            – Overview and usage guide for the project.
└── WA_Fn-UseC_-Telco-Customer-Churn.csv # Telco Customer Churn Dataset available on Kaggle
```

## 🚀 Features

Data Cleaning and Preprocessing

Exploratory Data Analysis (EDA)

Label Encoding for Categorical Features

Feature Scaling using StandardScaler

## Model Building:

CatBoost

Random Forest

XGBoost

## Model Evaluation:

Accuracy

Classification Report

## 📌 Requirements

Install dependencies using:
```bash
pip install -r requirements.txt
```

Key Libraries Used:

```
pandas
numpy
catboost
xgboost
scikit-learn
```

## 🛠️ How to Run

Clone the repository:
```
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction
```

Install dependencies (create a virtual environment if needed):
```
pip install -r requirements.txt
```

Open the Jupyter notebook:
```
jupyter notebook Churn.ipynb
```

Run all cells to execute the full pipeline.


## 🧹 TODO

Deploy best model using Flask/FastAPI

Export trained model with joblib or pickle

Add a Streamlit-based interactive UI
