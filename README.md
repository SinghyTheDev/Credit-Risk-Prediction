# Credit Risk Prediction Jupyter Notebook

## Description
Credit scoring is crucial for financial institutions to assess the creditworthiness of individuals or businesses. This Jupyter notebook implements credit risk prediction models trained using a dataset containing records of 1000 bank customers. The goal is to assist a bank manager in predicting the credit risk of potential customers, facilitating more informed decisions when considering loan applications.

## Data Analysis and Preparation
The notebook begins with exploratory data analysis to understand the distribution of credit risk among customers. It utilizes various visualizations and statistical summaries to gain insights into the dataset.

Missing values are handled by imputing the mean for certain columns. Categorical data, such as 'SavingAccounts', 'Housing', and 'Sex', are converted to numerical values for machine learning model compatibility.

## Artificial Neural Network (ANN) - Model 1
The notebook implements an Artificial Neural Network (ANN) to predict credit risk. The model's training accuracy is 65.9%, and testing accuracy is 65%.

## Artificial Neural Network (ANN) - Model 2
A second ANN with a different architecture achieves a training accuracy of 71.6% and testing accuracy of 68%.

## Decision Tree - Model 1
The Decision Tree model achieves a training accuracy of 73.7% and testing accuracy of 70.1%.

## Decision Tree - Model 2
A second Decision Tree model achieves a testing accuracy of 69.3%.

## Decision Tree Tuning and Decision Making
Tuning the depth of the best-performing Decision Tree indicates that a depth of 2 or 3 is optimal.

## Model Comparison and Recommendation
Model comparison based on accuracy metrics and k-fold cross-validation suggests that the first Decision Tree model is preferable, with an overall accuracy of 73.7%. The recommendation for the bank manager is to use the Decision Tree model due to its interpretability and relatively high accuracy.


## Conclusion
The Decision Tree model is recommended based on the provided data and evaluation metrics.
