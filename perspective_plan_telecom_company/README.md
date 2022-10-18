# Determination of a prospective plan for a telecom company

Let's imagine that you are in charge of the commercial department of a telecom company. You need to decide which of the two cell phone plans to advertise more. Simply put, which of the two plans is better? What if we only have data for 500 customers?

No problem. Just give the data to your fellow analyst. And that analyst is me :)

So, our task is to carry out a preliminary analysis of the cell phone plans of a telecom company on a small sample of customers. We have the data of 500 users: who they are, where they are from, what plan they use, how many calls and messages each sent in 2018. It is necessary to analyze the behavior of customers and draw a conclusion - which plan is better. Based on this conclusion, colleagues from the commercial department of the company will adjust the advertising budget.  

The main steps of our project will be:
* Examining the provided data
* Data preprocessing
* Calculations and adding the results necessary for analysis
* Data analysis
* Hypothesis testing
* Formulation of main conclusions

The project is made in Jupyter Notebook, notebook server version: 6.1.4., Python 3.7.8.
The project used the Pandas, MatPlotLib, NumPy, Math, SciPy libraries, as well as the IPython module.


# Plan description

**"Smart" plan**

1. Monthly fee: 550 rubles
2. Included 500 minutes of calls, 50 messages and 15 GB of Internet traffic
3. The cost of services in excess of the tariff package: 1. minute of conversation: 3 rubles (Telecom company always rounds up the values of minutes and megabytes. If the user spoke only 1 second, a whole minute is counted in the tariff); 2. message: 3 rubles; 3. 1 GB of Internet traffic: 200 rubles.

**"Ultra" plan**
1. Monthly fee: 1950 rubles
2. Included 3000 minutes of calls, 1000 messages and 30 GB of internet traffic
3. The cost of services in excess of the tariff package: 1. minute of conversation: 1 ruble; 2. message: 1 ruble; 3. 1 GB of Internet traffic: 150 rubles.
