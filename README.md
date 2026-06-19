# loan-approval-prediction
Machine Learning project that predicts loan approval status using applicant financial and personal information.
# Loan Approval Prediction

## Overview

This project uses Machine Learning to predict whether a loan application will be approved based on applicant information such as income, education, employment status, assets, and credit score.

The goal is to automate the loan approval process and assist financial institutions in making faster and more accurate lending decisions.

---

## Features

- Data preprocessing and cleaning
- Handling categorical and numerical features
- Feature scaling and encoding
- Machine Learning model training
- Loan approval prediction
- Model evaluation and performance analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Dataset Information

The dataset contains the following features:

| Feature | Description |
|----------|-------------|
| no_of_dependents | Number of dependents |
| education | Education level |
| self_employed | Self-employed status |
| income_annum | Annual income |
| loan_amount | Requested loan amount |
| loan_term | Loan repayment term |
| cibil_score | Credit score |
| residential_assets_value | Value of residential assets |
| commercial_assets_value | Value of commercial assets |
| luxury_assets_value | Value of luxury assets |
| bank_asset_value | Bank asset value |
| loan_status | Loan approval status |

---

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preprocessing
6. Model Training
7. Model Evaluation
8. Loan Approval Prediction

---

## Project Structure

loan-approval-prediction/
│
├── project_loan_approval.ipynb
├── README.md
├── dataset.csv
└── requirements.txt

---

## Results

The model successfully predicts loan approval decisions based on applicant financial and personal information.

Evaluation metrics were used to measure model performance and prediction accuracy.

---

## Future Improvements

- Hyperparameter tuning
- Testing multiple ML algorithms
- Model deployment using Streamlit
- Real-time loan prediction web application
- Explainable AI (XAI) integration

---

## Skills Demonstrated

- Data Cleaning
- Feature Engineering
- Data Visualization
- Machine Learning
- Classification Models
- Model Evaluation
- Python Programming

---

---

## How to Run

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the notebook:

```bash
jupyter notebook project_loan_approval.ipynb
```

Execute all cells to train the model and generate predictions.
