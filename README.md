# Wine Quality Prediction

## Overview
This project uses machine learning techniques to predict the quality of wines based on their physicochemical properties. It explores different classification models and evaluates their performance through cross-validation.

## Dataset
The dataset used for this project contains several features that represent the chemical composition of wine samples, such as:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (target variable)

The dataset is loaded from the `WineQT.csv` file and contains 1143 entries.

## Models Used
The following machine learning models were evaluated:
- Support Vector Classifier (SVC)
- Random Forest Classifier
- Gradient Boosting Classifier
- XGBoost Classifier
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Multi-Layer Perceptron (MLP)

## Preprocessing
- The dataset is shuffled before training to ensure randomized data distribution.
- Missing values are handled using `SimpleImputer`.
- Features are scaled using `MinMaxScaler`.

## Model Evaluation
Cross-validation is performed to assess the performance of each model, with accuracy being the primary metric.

## Dependencies
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`

You can install the required dependencies using:
```bash
pip install -r requirements.txt
