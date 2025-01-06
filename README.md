# Credit-Risk-Classification
This project is designed to classify credit risk based on a dataset from Kaggle, employing various machine-learning models for evaluation. The process involves data preprocessing, model training, and performance evaluation using key metrics.

## Dataset
The dataset used in this project is included in the repository (credit_risk_dataset.csv) and is publicly available on Kaggle at https://www.kaggle.com/datasets/laotse/credit-risk-dataset/data.
It contains features relevant to assessing credit risk.

## Project Workflow
The project follows these key steps:

### 1. Data Preprocessing
Missing Value Handling: Imputation of missing values where necessary.
Data Encoding: Convert categorical variables into numerical formats using encoding techniques.
Feature Scaling: Standardization or normalization of features to ensure uniformity.
Splitting the Dataset: The dataset is divided into training and test sets to evaluate model performance.

### 2. Model Training and Evaluation
The following machine learning models are trained and evaluated on the processed data:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN) Classifier
- Naive Bayes Classifier
- Support Vector Classifier (SVC)
- Gradient Boosting Classifier
- XGBoost Classifier, LightGBM, and CatBoost

### 3. Evaluation Metrics
Each model is assessed using performance metrics, including:

Accuracy,
Precision,
Recall,
F1 Score,
AUC-ROC Curve.

### 4. Results
The results of the model evaluations are compared to determine the best-performing algorithm for credit risk classification.

## Repository Contents
- Credit Risk Classification.ipynb: The Jupyter Notebook containing the code for the project.
- credit_risk_dataset.csv: The dataset used in the project.
- README.md: This file, describing the project details.
