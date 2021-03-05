# Customer-Churn-Prediction-Using-Artificial-Neural-Network

<p align="center">
<img width="500" alt="postgreSQL" src="https://user-images.githubusercontent.com/37532698/110115053-f7428980-7dce-11eb-8056-92ce38eb1c22.png"></p>

## Overview

Customer churn prediction is to measure why customers are leaving a business. I am using here Telco Customer Data from Kaggle. Will build a deep learning model to predict the churn and use precision, recall, f1-score to measure performance of the model.

## Steps:

1. Data Collection : Here I had used the [Telco Customer Data from Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn). 
2. Preprocess the data
    -  Convert the nominal and ordinal categorical values into numbers.
    -  Created dummy variables for categorical features having more than two categories.
    -  Train Test Split. Further preprocessing is done after the split to avoid data leakage.
    -  Feature scaling using min max scaling is done seperately for train and test data
    -  Oversampling using SMOTE to deal with class imbalance, as Churn=0 class is much more than Churn=1 
4. Create a Dense Artificial Neural Network with Dropout for regularization.
5. Do prediction for the test data and plot the output. Check the performance metrics.

# Results

For the customer churn prediction, we need to reduce the False Negative (ie. prediction will not churn by mistake). Therefore, need to improve recall. Here we got a recall of 74% for our model. You can see the whole pipeline [here](https://github.com/mpfouziya/Customer-Churn-Prediction-Using-Artificial-Neural-Network/blob/main/Customer_Churn_Prediction_Using_ANN.ipynb) 

<p align="center">
<img width="500" alt="postgreSQL" src="https://user-images.githubusercontent.com/37532698/110117923-03c8e100-7dd3-11eb-9a75-bde263530cd1.jpg"></p> 

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img src="https://user-images.githubusercontent.com/37532698/109387870-23689100-791d-11eb-9da1-3b18191a224e.jpeg" width=280>](https://keras.io/)  



