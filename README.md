# EECE-5644-Assignment-02

## Overview

This assignment revolved around training a multivariate linear regression on customer data from a telecom company "Telco". Given a clean dataset indicating which services a customer subscribed to, and their monthly bill, the coefficients of the model represent the monthly price of the respective services. 

## Getting the Dataset

The dataset [telco.csv](telco.csv) is already present in the repository, however, if need be, it can be downloaded from [https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data)

## Running the Assignment

Dependencies must first be installed by running 
```
pip install -r requirements.txt
```

The cleaning notebook [assignment02.ipynb](assignment02.ipynb) can then be run.

## Findings

A multivariate model that takes in which services a customer subscribes to, can be used to explain 99.8% of the variation in the monthly charges that a customer recieves. This is a large upgrade compared to the ~70% of variation that a single-variable model, based only on the number of services a user was subscribed to could explain.