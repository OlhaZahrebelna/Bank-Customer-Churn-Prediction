# Bank Customer Churn Prediction (Competition)

## Task
Predict whether a customer will continue using their bank account or close it (i.e., whether **churn** will occur).

To solve the task, you need to:
1. Train a **binary classification** model on the provided training data.
2. Generate predictions for the test set.
3. Create a **submission file** in the required format and upload it to the competition platform.

The winning team is the one that achieves the highest **Area Under the ROC Curve (ROC AUC)** score.

Good luck! 🚀

---

## Dataset Description

The dataset contains the following attributes:

- **ID**: Unique row identifier  
- **Customer ID**: Unique identifier for each customer  
  - This field contains duplicates across multiple rows for the same customer, so it is typically **dropped**.
- **Surname**: Customer’s last name  
- **Credit Score**: Numeric value representing the customer’s credit score  
- **Geography**: Country of residence (France, Spain, or Germany)  
- **Gender**: Customer gender (Male or Female)  
- **Age**: Customer age  
- **Tenure**: Number of years the customer has been with the bank  
- **Balance**: Customer’s account balance  
- **NumOfProducts**: Number of bank products used by the customer (e.g., savings account, credit card)  
- **HasCrCard**: Whether the customer has a credit card (1 = yes, 0 = no)  
- **IsActiveMember**: Whether the customer is an active member (1 = yes, 0 = no)  
- **EstimatedSalary**: Estimated salary of the customer  
- **Exited**: Target variable — whether the customer left the bank (1 = yes, 0 = no)

---

## Goal
Build a model that predicts the probability of `Exited = 1` for each customer in the test set and submit predictions for evaluation using **ROC AUC**.
