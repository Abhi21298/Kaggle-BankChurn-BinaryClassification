# Kaggle-BankChurn-BinaryClassification

## Kaggle Competition - January 2024 - Season 4 Episode

### This is my first ever entry into Kaggle Competition. :-) 
### So, this is a very naive attempt on Binary Classification with a Bank Churn Dataset.

## About Dataset
The bank customer churn dataset is a commonly used dataset for predicting customer churn in the banking industry. It contains information on bank customers who either left the bank or continue to be a customer. The dataset includes the following attributes:

### Input Columns - 
    Customer ID: A unique identifier for each customer
    Surname: The customer's surname or last name
    Credit Score: A numerical value representing the customer's credit score
    Geography: The country where the customer resides (France, Spain or Germany)
    Gender: The customer's gender (Male or Female)
    Age: The customer's age.
    Tenure: The number of years the customer has been with the bank
    Balance: The customer's account balance
    NumOfProducts: The number of bank products the customer uses (e.g., savings account, credit card)
    HasCrCard: Whether the customer has a credit card (1 = yes, 0 = no)
    IsActiveMember: Whether the customer is an active member (1 = yes, 0 = no)
    EstimatedSalary: The estimated salary of the customer

### Output Column - 
    Exited: Whether the customer has churned (1 = yes, 0 = no)

## Evaluation - 
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

### My results -
Achieved a score of 0.87998 while the highest was around 0.91

### I compared a basic Logistic regression model and a neural network (128, 32, 8, 1) with 4 layers and evaluated their performance. NN performed with 86% train and 85% test accuracy. Logistic regression provided a score of 85%

### Areas identified for improvement - 
Definitely perform more plotting (Visualizations are key)
Analyse feature importance to simplify model
Write better structured code
Explore more models for evaluation

