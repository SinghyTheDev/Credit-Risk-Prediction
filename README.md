# Credit Risk Prediction

## Description
Credit scoring is crucial for financial institutions to assess the creditworthiness of individuals or businesses. The goal of this code is to assist financial institutions, such as banks, in predicting the credit risk of potential customers to enable more informed decisions when considering loan applications. This code trains a variety of ML models using a dataset containing records of 1000 bank customers. There are quite a few missing values in the dataset however effort are made to fill these missing values using appropriate methods. The models hyperparameters are tuned to find the most optimal hyperparameters.

## Data Analysis and Preparation
The code begins with data analysis using various visualizations and statistical summaries to gain insights into the dataset.

Missing values are handled by imputing the mean for certain columns. Categorical data such as 'SavingAccounts', 'Housing', and 'Sex' are converted to numerical values to enable compatibility with ML models.

## Artificial Neural Network Model 1
This models accuracy is 65%.

## Artificial Neural Network Model 2
This models accuracy is 68%.

## Decision Tree Model 1
This models accuracy is 70.1%.

## Decision Tree Model 2
This models accuracy is 70%.

## Model Comparison and Recommendation
Model comparison based on k-fold cross-validation show the recommended model is Decision Tree 1.


## Conclusion
Out of all the models, the Decision Tree 1 model is recommended based on the k-fold cross-validation evaluation metric. The dataset had lots of missing values, so with a more complete dataset the models likely yield more optimal accuracies.
