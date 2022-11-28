# Sentiment classification of comments
  
The online store launches a new service. Now users can edit and supplement product descriptions, just like in wiki communities.
That is, clients propose their edits and comment on the changes of others.
The store needs a tool that will look for toxic comments and submit them for moderation.

We need to create a model that will classify comments as positive and negative. Here is a dataset with markup on the toxicity of edits.

Purpose: to build a model with the value of the quality metric *F1* not less than 0.75.

The main stages of our project will be:

* Loading and preparing data
* Training different models
* Evaluation of the quality metrics of F1 models
* Choosing the best model, testing it, checking the model for sanity
  
The project is made in **Jupyter Notebook**, Notebook server version: 6.1.4. Version **Python** 3.7.8.
The project used:
* **re**
* **Pandas**
* **NumPy**
* **scikit-learn**
* **MatPlotLib**
* **Spacy**
* **NLTK**
* **IPython**
