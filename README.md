# Supervised Machine Learning, Predicting Housing Prices: Overview

* Defined a rule that determines whether a house is expensive or not
* Random Forest classifier using GridsearchCV to reach the best model.
* A function was written that takes a DataFrame of housing data as an input, and based on the rule defined, outputs a list with predictions about whether a house is expensive or not (1 or 0)
* Used Scikit-Learn’s accuracy_score to check how well my rule makes predictions on the test set (95%)

## Code and Resources Used

**Python Version:** 3.8

**Packages:** pandas, seaborn, matplotlib, sklearn

**Enviroment:** google colab

**Data:** Obtained from [WBS coding school](https://www.wbscodingschool.com/)


## Data Cleaning

After obtaining the data, I needed to clean it up so that it was usable for my analysis. I made the following changes and created the following variables:

* Deleting columns where there was a huge amount of missing data

## Model Building

First, I transformed the categorical variables into dummy variables. I also split the data into train and tests sets with a test size of 20%.

I tried the following model:

* **Random Forest** – With the sparsity associated with the data, I thought that this would be a good fit.

## Model performance

The **Random Forest** model reached a 95.8%

## Model deployment

In this step, I am building a small web-app that acts as an interface for inputing data about a house to the model and can display the model prediction.
Publishing this web-app (together with the modelling pipeline) online for everyone to use.

* **Streamlit**

**(Still working on)**















