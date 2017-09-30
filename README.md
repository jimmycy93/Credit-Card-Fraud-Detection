# Credit Card Fraud Detection
A project on techniques with imbalanced classification

## Project Introduction
It is often that the data we retrieve have imbalanced label and we are asked to make classification. These scenarios are troublesome since not only the models we usally use bring poor result, but also the evaluation metric we often used, accuracy, is not adequate for imbalanced data sets due to the impact of the minority class. This project aims to demonstrate some techniques used to combat these situations, such as resampling or cluster before predicting, as well as using PR (Precision-Recall) curve to evaluate model. The approaches for the project are :

   1. Randomly split the dataset into train, validation, and test set.
   2. Do basic EDA and feature engineering.
   3. Predict and evaluate with validation set.
   4. Resample the dataset. 
   5. Train on resampled train set then predict and evaluate with validation set.
   6. Try other different models.
   7. Compare the difference between the predictions and choose the best model.
   8. Find the optimised threshold of the chosen model.
   9. Predict on test set to report final result.

## Data Description
The project take use of The [Credit Card Fraud Data on Kaggle](https://www.kaggle.com/dalpozz/creditcardfraud/data), the data description on the webpage is as followed :

The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

The dataset has been collected and analysed during a [research collaboration of Worldline and the Machine Learning Group](http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. More details on current and past projects on related topics are available on http://mlg.ulb.ac.be/BruFence and http://mlg.ulb.ac.be/ARTML

Please cite: Andrea Dal Pozzolo, Olivier Caelen, Reid A. Johnson and Gianluca Bontempi. Calibrating Probability with Undersampling for Unbalanced Classification. In Symposium on Computational Intelligence and Data Mining (CIDM), IEEE, 2015

## Link to Jupyter Notebook in Repository
[Notebook](https://github.com/jimmycy93/Credit-Card-Fraud-Detection-Python-/blob/master/Kaggle%20Credit%20Fraud%20Detection.ipynb)
