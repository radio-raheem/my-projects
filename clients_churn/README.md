# Clients churn

Clients started leaving the bank. Every month. A little, but noticeable. Banking marketers figured it was cheaper to keep current customers than to attract new ones.

It is necessary to predict whether the client will leave the bank in the near future or not. We have historical data on customer behavior and termination of agreements with the bank.

Our task is to build a model with *F1*-measure value of at least 0.59.

Data source: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

Our key steps:
* Data preparation
* Research task. Training different models without taking into account imbalance
* Fight imbalance. Training Different Models Given Imbalance
* Model testing
* Checking the model for sanity
* Checking AUC-ROC metric

**Data description**  

**Features**

*RowNumber* — row index in the data 
*CustomerId* — unique customer ID 
*Surname* - surname 
*CreditScore* - credit score 
*Geography* - country of residence 
*Gender* - gender 
*Age* — age 
*Tenure* - how many years a person has been a client of the bank 
*Balance* — account balance 
*NumOfProducts* - the number of bank products used by the client 
*HasCrCard* - the presence of a credit card 
*IsActiveMember* — client activity 
*EstimatedSalary* — estimated salary

**Target feature** 

**Exited** — the fact that the client has left


The project is made in **Jupyter Notebook**, Notebook server version: 6.1.4. Version **Python** 3.7.8.
  
Libraries used in the project:
* **Pandas**
* **NumPy**
* **MatPlotLib**
* **scikit-learn**
* **IPython**
