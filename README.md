# Prediction-of-Customer-Status

This is a Data Science Project which involved building a model which, given the necessary parameters, will be able to predict if the customer of a telecom company will "churn" (Leave the company) or not. The dataset used is from an actual telecom company consisting of over 7000 entries of customers. 

The most time consuming part was feature extraction to analyze which features were favoring the churn, which were against it and which were neutral. I plotted graphs for this for all the features and individually and manually decided which ones to keep and which ones to discard.

I used dummy variables for the textual data, but make sure you keep in mind about the "dummy variable trap".

I used GridSearchCV to train the model using various algorithms to obtain the best results.
