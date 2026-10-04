# Customer-Churn-Prediction
Machine learning project for predicting customer churn using Python and scikit-learn.

## Project Overview

This project uses machine learning to predict customer churn.

The notebook performs data exploration, preprocessing, visualization, model training, model evaluation, and feature analysis.

## Dataset

The dataset contains 1,200 customer records and 13 columns.

The target variable is `churn`, which indicates whether a customer has churned.

### Target Distribution

* No Churn: 1,020 customers
* Churn: 180 customers

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Machine Learning Models

Three classification models are trained and evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest

The models use preprocessing pipelines with:

* Missing-value imputation
* One-hot encoding for categorical variables
* Train/test splitting

## Model Evaluation

The models are evaluated using:

* Accuracy
* ROC-AUC
* Classification Report
* Confusion Matrix

## Feature Analysis

The project also includes:

* Random Forest feature importance
* Logistic Regression coefficients

These analyses help identify the customer characteristics that are most useful for predicting churn.

## Project Structure

```text
customer-churn-prediction/
│
├── main.ipynb
├── customer_churn.csv
├── requirements.txt
├── README.md
└── .gitignore
```

## How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Install the required packages

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

Open `main.ipynb` using Jupyter Notebook, JupyterLab, or VS Code.

### 4. Run all cells

Run the notebook from the first cell to the last cell.

## Project Goal

The goal of this project is to demonstrate an end-to-end machine-learning workflow for customer churn prediction, including data preprocessing, model comparison, evaluation, and model interpretation.
