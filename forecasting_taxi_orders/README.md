# Forecasting taxi orders
  
The taxi service has collected historical data on taxi orders at airports.
To attract more drivers during the peak period, you need to predict the number of taxi orders for the next hour.
We need to build a model for such a prediction.

The value of the *RMSE* metric on the test set should not exceed 48.

We need:

1. Load the data and resample it one hour at a time.
2. Analyze the data.
3. Train different models with different hyperparameters. Make a test set of 10% of the original data.
4. Check the data on the test set and draw conclusions.


The data is in the `taxi.csv` file.
The number of orders is in the `num_orders` column.

The project is made in **Jupyter Notebook**, Notebook server version: 6.1.4. Version **Python** 3.7.8.
Libraries used in the project:
* **Pandas**
* **NumPy**
* **statsmodels**
* **scikit-learn**
* **MatPlotLib**
* **Light GBM**
* **IPython**
