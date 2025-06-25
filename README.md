# Practical-Assessment-2

This assessment applies the CRISP-DM Framework to a used car problem to identify the correct features to build a model to predict use car prices.

Jupyter File (CRISP-DM, also copied below): https://github.com/msking2/Practical-Assessment-2/blob/main/CRISP-DM%20User%20Car%20Prices.ipynb

Jupyter File (Code File): https://github.com/msking2/Practical-Assessment-2/blob/main/Use%20Car%20Prices%20Juypter%20Notebooks%20File.ipynb

Outcome: The most influential features that affected the price of a car was the following:

year
cylinder
odometer
drive

The model that was used that resulted in the lowest error was ridge regression, using OneHotEncoder on drive and PolynomialFeatures degree = 2.

The MSE training and test error were the following:

MSE Train: 56325034.59 
MSE Test: 56332212.29
