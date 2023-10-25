# Retail Analysis with Walmart Data

1. [Project Motivation](#ProjectMotivation)
2. [Installation](#installation)
3. [Data](#data)
4. [Implementation](#model)
5. [Results](#results)

## 1. Project Motivation <a name="ProjectMotivation"></a> 

**In this project we try to find the relations between items in market basket. Given a list of 7500 different shopping baskets, can we find which pairs of items are strongly correlated?**




## 2. Installation <a name="installation"></a>

- Python versions 3.*.
- Apriori module from Apyori library
- Python Libraries:
    - sklearn.
    - Pandas.
    - numpy.
    - seaborn
    - matplotlib.
    - datetime.

## 3. Data<a name="data"></a> 

There are 7500 different market baskets available from this <a href="https://www.kaggle.com/code/annadurbanova/market-basket-optimization-apriori-practice">Kaggle</a> dataset.



## 4. Implementation <a name="model"></a> 
In this project, we used Apriori module from Apyori library to find strong relations between pairs of items. There are three important measures we need to adjust the model, Support, Confidence and Lift.

<h2>Support:</h2>
Within a dataset, i.e. a list of transactions, how many transactions contain item A, so it is just the probability of item A occurring, which we can represent as below. Statistically speaking, it is a frequentist's estimate of the probability.

<h2>Confidence:</h2>
Out of the transactions that contains item A, how many also contains item B. The bigger the overlap, the greater the confidence we have that people who are buying item A also buys item B.  Statistically speaking, it is (estimated) conditional probably of item B given item A, i.e. P(B|A).

<h2>Lift:</h2>
The ratio between Confidence of A and Support B


## 5. Result<a name="results"></a>
The details of the results show in the code, in a table.
