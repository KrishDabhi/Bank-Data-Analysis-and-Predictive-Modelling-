# Bank Marketing Campaign Prediction

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-brightgreen)

Advanced machine learning pipeline for predicting bank marketing campaign outcomes using ensemble methods and hyperparameter optimization.

## 📋 Table of Contents
- Train Dataset
- Test Dataset
- The project file(Task4)

## 🎯 Project Overview

This project predicts the success of bank marketing campaigns (whether a client will subscribe to a term deposit) using advanced machine learning techniques. The pipeline includes comprehensive feature engineering, multiple model training, ensemble methods, and hyperparameter optimization using Optuna.

## ✨ Features

### Advanced Feature Engineering
- **Duration-based features**: Log, sqrt, squared transformations and granular categorization
- **Financial profile features**: Balance transformations and risk indicators
- **Campaign sophistication**: Mathematical transformations and efficiency metrics
- **Age intelligence**: Non-linear transformations and life stage categorization
- **Temporal features**: Monthly patterns and seasonal intelligence
- **Risk profiling**: Loan, housing, and default combinations
- **Interaction features**: Multi-variable combinations for enhanced predictive power

### Machine Learning Pipeline
- **Multiple algorithms**: XGBoost, LightGBM, CatBoost
- **Ensemble methods**: Weighted model combinations
- **Hyperparameter optimization**: Optuna-based optimization
- **Cross-validation**: Stratified K-Fold validation
- **Feature selection**: Multi-method feature importance analysis

## 📊 Dataset

The project uses the Bank Marketing dataset containing client information and campaign details:
- **Train dataset**: `train.csv`
- **Test dataset**: `test.csv`
- **Target variable**: `y` (whether client subscribed to term deposit)

### Key Features Include:
- Client demographics (age, job, marital status)
- Financial information (balance, housing, loan status)
- Campaign details (duration, contacts, previous outcomes)
- Temporal data (day, month of contact)



## 🚀 Installation

### Prerequisites
- <img width="86" height="20" alt="image" src="https://github.com/user-attachments/assets/66a08801-39f4-4a24-810c-ee20bf73b44a" />
- Pandas
- Numpy
- <img width="124" height="20" alt="image" src="https://github.com/user-attachments/assets/b3bb12c7-9e97-456e-92f4-86a7a8a8d29e" />
- <img width="124" height="20" alt="image" src="https://github.com/user-attachments/assets/39b3c368-5386-4817-9b94-ca2f1b4fe3fc" />
- <img width="152" height="20" alt="image" src="https://github.com/user-attachments/assets/d75e222c-82f1-4765-8e64-c038bd0e217c" />


- <img width="152" height="20" alt="image" src="https://github.com/user-attachments/assets/d82ced2d-6c6f-4610-96b0-925ea6c1395f" />
### Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
pip install xgboost lightgbm catboost optuna
pip install scipy plotly
