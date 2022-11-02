# Plan recommendation

What do you think about when you imagine the country's mobile communications market? I would venture to guess that there are several telecommunications companies competing for customers. However, when companies have already divided the market among themselves, it may make more sense to put efforts into retaining customers rather than attracting new ones.

The mobile operator found out: many customers use archival tariffs. He wants to build a system that can analyze customer behavior and offer users a new plan: "Smart" or "Ultra".

We have data on the behavior of customers who have already switched to these plans. You need to build a model for the classification problem that will select the appropriate plan.

Our task is to build a model with an **accuracy** value of at least 0.75.

The key steps are:
* Data exploration
* Splitting the data into samples
* Research the quality of different models
* Testing the quality of the model on a test sample
* Sanity checking the model

**Data Description**

Each object in the dataset is information about the behavior of one user per month. Known:  
* **calls** — number of calls,  
* **minutes** — total duration of calls in minutes,  
* **messages** — number of sms messages,  
* **mb_used** - Internet traffic used in Mb,  
* **is_ultra** - what plan did you use during the month ("Ultra" - 1, "Smart" - 0).


The project is made in **Jupyter Notebook**, Notebook server version: 6.1.4. Version **Python** 3.7.8.
Libraries used in the project:
* **Pandas**
* **NumPy**
* **Math**
* **scikit-learn**
* **IPython**
