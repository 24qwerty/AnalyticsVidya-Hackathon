# Santander-Value-Prediction

Santander has provided an anonymized data to predict a value of transactions for each potential customer.

The data consist of 4992 features with most entries with value 0. After cleaning the dataset, I have used LightGBM with 5 fold cross validation to predict target value from the given features. The solution scores 1.46 root mean squared error log error.
