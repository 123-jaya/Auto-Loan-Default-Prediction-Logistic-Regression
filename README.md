# Auto Loan Default Prediction using Logistic Regression

## Overview

This project uses **Logistic Regression**, a machine learning classification algorithm, to predict the **probability of auto loan defaults** based on the borrower's **age group**.

The dataset contains grouped loan information such as total loans issued, number of bad loans, and number of good loans. The model converts this grouped data into individual samples and trains a logistic regression model to analyze loan risk.



## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn



## Dataset

The dataset includes the following fields:

| Column          | Description                         |
| --------------- | ----------------------------------- |
| Age_Group       | Age range of borrowers              |
| Age_Mid         | Midpoint of the age group           |
| Total_Loans     | Total loans issued                  |
| Bad_Loans       | Number of defaulted loans           |
| Good_Loans      | Number of successfully repaid loans |
| Bad_Probability | Probability of loan default         |



## Project Workflow

1. Load the loan dataset
2. Expand grouped data into individual loan samples
3. Split the data into training and testing sets
4. Standardize the features using `StandardScaler`
5. Train a **Logistic Regression** model
6. Evaluate the model using different performance metrics



## Model Evaluation Metrics

The following metrics are used to evaluate the model:

* Confusion Matrix
* Accuracy
* Precision
* Recall
* F1 Score
* ROC Curve and AUC Score
* Log Loss
* Precision-Recall Curve
* Calibration Curve



## How to Run the Project

### Install Required Libraries

```
pip install pandas numpy matplotlib scikit-learn
```

### Run the Program

```
python code.py
```



## Output

The model generates several evaluation results and plots such as:

* Confusion Matrix
* ROC Curve
* Precision-Recall Curve
* Calibration Curve
* Loan default probability predictions



## Learning Outcome

This project demonstrates:

* Binary classification using Logistic Regression
* Data preprocessing and dataset expansion
* Model evaluation techniques
* Visualization of model performance




