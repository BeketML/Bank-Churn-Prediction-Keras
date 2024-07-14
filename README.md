# **Bank Customer Churn Prediction**

This repository contains data and code for predicting customer churn in a bank setting. The dataset used for this competition (both train and test) was generated from a deep learning model trained on the Bank Customer Churn Prediction dataset. While feature distributions are similar to the original dataset, they are not identical.

## **Files**

- **train.csv**: Training dataset with the target variable `Exited` indicating customer churn.
- **test.csv**: Test dataset where the objective is to predict the probability of `Exited`.
- **sample_submission.csv**: A sample submission file in the correct format.

## **Competition Details**

Feel free to use the original Bank Customer Churn Prediction dataset as part of this competition. This allows exploring differences between the generated dataset and the original, and to assess whether incorporating the original dataset in training improves model performance.

## **Dataset Description**

### **Features**

- **CustomerId**: Unique identifier for each customer.
- **Surname**: Customer's surname.
- **CreditScore**: Credit score of the customer.
- **Geography**: Customer's country of residence (`France`, `Spain`, `Germany`).
- **Gender**: Customer's gender (`Male`, `Female`).
- **Age**: Customer's age in years.
- **Tenure**: Number of years the customer has been with the bank.
- **Balance**: Bank balance of the customer.
- **NumOfProducts**: Number of bank products the customer uses.
- **IsActiveMember**: Whether the customer is an active member (`1` for yes, `0` for no).
- **EstimatedSalary**: Estimated salary of the customer.

### **Target Variable**

- **Exited**: Binary variable indicating whether the customer churned (`1` for yes, `0` for no).


