# Loan Default Prediction Using Gaussian Naive Bayes

## Overview

This project implements a machine learning model to predict whether a loan will be **fully paid** or **not fully paid** using the Gaussian Naive Bayes algorithm. The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and performance visualization.

The objective is to assist in identifying loans with a higher risk of default, enabling better credit risk assessment and informed lending decisions.

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- One-Hot Encoding of categorical variables
- Gaussian Naive Bayes classification model
- Model evaluation using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - ROC Curve
- Data visualization with Matplotlib and Seaborn

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Dataset

The dataset contains loan applicant information and loan characteristics used to predict whether a loan is:

- **0** – Fully Paid
- **1** – Not Fully Paid

## Project Structure

```
Loan-Default-Prediction/
│── Loan_Default_Prediction.ipynb
│── README.md
│── requirements.txt
└── dataset.csv
```

## How to Run

1. Clone the repository.
2. Install the required dependencies.
3. Open the Jupyter Notebook.
4. Run all notebook cells sequentially.

## Results

The Gaussian Naive Bayes model was trained and evaluated using standard machine learning metrics. Performance was assessed using the ROC Curve, Confusion Matrix, Classification Report, and Accuracy Score to determine its effectiveness in predicting loan repayment outcomes.

## Author

**Angel Mathenge**
