# Loan_Delinquency_Prediction

## Table of Contents

1. [Project Description](#desc)
2. [Install](#install)
3. [Code](#code)
4. [Run](#run)
5. [Data](#data)

<a name="desc"></a>
## Project Description

Financial Service Institutions rely on data-driven risk analysis to identify beforehand the potential issues that could negatively impact their organization. It is important for these lending institutions to assess the counterparty of their loan agreement and have some mitigation strategies in place. This involves ‘Loan Delinquency Prediction’ which is a statistical model used to identify the likelihood a customer might default based on their past credit behavior and financial status. A customer is called delinquent when they fail to make the minimum monthly payment on their loan and is called a defaulter if they stay delinquent over a period of time determined by the Institution servicing the loan.

To solve this problem, the project aims at analyzing the past loan data of a lending institution and using the data to develop a model to predict the probability of a customer defaulting on a loan. It helps the clients by providing them with an idea of how much exposure they have with the counterparties of their loan agreement. This result can help these institutions to adjust their capital, future deals in the market with a consideration that other parties may default.

<a name="install"></a>
## Install

This project requires Python and the following Python libraries installed:

* numpy
* pandas
* seaborn
* matplotlib
* os
* sklearn
* xgboost
* scipy
* hvplot
* tensorflow

This project requires Python and the following R libraries installed:

* tidycensus
* tidyverse
* sf
* dplyr

You will also need to have software installed to run and execute a Jupyter Notebook.

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.
Otherwise, you could execute the code on Google Colaboratory.

<a name="code"></a>
## Code

The template code for Exploratory Data Analysis is provided in the ``` EDA2.ipynb ``` notebook file. The template code for the Exploratory Data Analysis combined with census data is provided in the ``` Census-EDA.R ```. The model is present in ```modelling.ipynb``` Python file. 

<a name="code"></a>
## Run

In a terminal or command window, run one of the following commands:

```
ipython notebook modelling.ipynb
```
or

```
jupyter notebook modelling.ipynb
```

or open with Juoyter Lab

```
jupyter lab
```

This will open the Jupyter Notebook software and project file in your browser.

or else download and upload the file on Google Colaboratoty. 

<a name="data"></a>
## Data

The dataset was distributed by LendingClub, a US peer-to-peer lending company headquartered in San Francisco, California. The dataset has more than a million records with 72 attributes related to Loan payment by its customers for the year 2007-2017. This dataset’s interest attribute is the ‘Loan status’, which indicates whether a customer is late on a payment. Other candidates of interest include ‘Loan Amount’, ‘Installment’, ‘Annual Income’, ‘Interest Rate’, etc., which may predict the loan delinquency by a given customer.

We also combined the dataset from LendingClub with the Census data to obtain additional demographic information and show a relation between demographics and delinquency rates. To perform this, we used the zip codes provided in the census data and joined our dataset on the zip codes present in the census data.
