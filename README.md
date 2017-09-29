# Credit Card Fraud Detection
A project on techniques with imbalanced classification

## Project Introduction
It is often that the data we retrieve have imbalanced label and we are asked to make classification. These scenarios are troublesome since not only the models we usally use bring poor result, but also the evaluation metric we often used, accuracy, is not adequate for imbalanced data sets due to the impact of the minority class. This project aims to demonstrate some techniques used to combat these situations, such as resampling or using PR (Precision-Recall) curve to evaluate model. 

## Data Description
The project take use of The Instacart Online Grocery Shopping Dataset 2017, 

   1. Extract only the first 14000 transactions from **order_products__train.csv**.
    
   2. Added a column of product_name corresponding to product_id from **products.csv**.
   
   3. Added a column of user_id corresponding to order_id from **orders.csv**. 

The file name of the preprocessed data is **Market Basket-Instacart.csv**, the variable names are trivial.

## Link to jupyter notebook in repository
[Notebook](http://rpubs.com/jimmycy93/308611)
