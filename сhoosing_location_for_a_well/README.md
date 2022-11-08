# Choosing location for a well
  
Ok, so we work for an oil company. We need to decide where to drill a new well.

We have been provided with oil samples in three regions: in each of 10,000 fields, where the quality of oil and the volume of its reserves have been measured.  
Our task is to build a machine learning model to help determine the region where mining will bring the most profit.
  
The key steps of our project will be:

* Loading and preparing data
* Training and validation of the model
* Preparation for profit calculation
* Calculation of profit and risks. Selecting a region for field development

**Data Description**

*Features*
  
*id* — unique well identifier
*f0, f1, f2* - three signs of points (we don't know what they mean, but the signs themselves are significant)
  
*Target feature*
  
**product** — volume of reserves in the well (thousand barrels)
  
Conditions of the problem:
Only linear regression is suitable for training the model (the rest are not predictable enough).
During the exploration of the region, 500 points are explored, from which, using machine learning, the best 200 are selected for development.
The budget for the development of wells in the region is 10 billion rubles.
At current prices, one barrel of raw materials brings 450 rubles of income. The income from each unit of the product is 450 thousand rubles, since the volume is indicated in thousands of barrels.
After assessing the risks, we need to leave only those regions in which the probability of losses is less than 2.5%. Among them, choose the region with the highest average profit.
  
The project is made in **Jupyter Notebook**, Notebook server version: 6.1.4. Version **Python** 3.7.8.
Libraries used in the project:
* **Pandas**
* **NumPy**
* **SciPy**
* **scikit-learn**
* **IPython**
