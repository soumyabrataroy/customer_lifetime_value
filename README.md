# customer_lifetime_value

The code provided is a Python script that performs customer lifetime value (CLV) analysis on a retail dataset. It uses linear regression to predict the CLV of customers based on their purchase history.

The script begins by loading the retail dataset and filtering it to include only purchases made before December 1, 2011. It then calculates the sales revenue for each invoice and creates a summary dataframe that includes various statistics for each customer, such as the total sales, average sales, and purchase frequency.

The script then creates a new dataframe that contains the features that will be used to predict CLV, such as the customer's average sales in the last 3 months and the number of purchases they made in the last 3 months. It also creates a response dataframe that contains the customer's actual CLV in the next 3 months.

The script then splits the data into training and test sets and fits a linear regression model to the training data. It then uses the trained model to predict the CLV of the customers in the test set.

Finally, the script evaluates the performance of the model by calculating the R-squared and median absolute error for both the training and test sets. It also plots the predicted CLV values against the actual CLV values for the test set.

Overall, the code provided is a good example of how to use linear regression to predict CLV. It is well-documented and easy to understand.
