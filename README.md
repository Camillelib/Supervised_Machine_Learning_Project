# Supervised Machine Learning Project
Classifying a dataset using an optimised ML model with python

<div><img src="https://angeliquepanagos.com//wp-content/uploads//2016/01//Superma-7660041_630x210.jpg" style="width: 4000px;"></div>

## Overview
Using several machine learning models, can we predict the type of a supermarket based on sales data?

## Process followed

### Librairies used
* pandas
* numpy
* matplotlib.pyplot
* seaborn
* sklearn
* xgboost

### Steps
<b>1. Data collection</b>
<p>Dataset imported from : https://www.kaggle.com/devashish0507/big-mart-sales-prediction</p>

<b>2. Data cleaning:</b>
 * Deleting 2 columns
 * Deleting ~6000 empty rows  
 * Cleaning the item fat content column
  
<b>3. Data visualisation: </b>
Understanding the dataset and features.

1. General Product Categories
2. Breakdown Per Store Type:
* Item visibility
* Total sales
* Other features: location and age
 
<b> 4. Data transformation </b>

* Identify and correct correlations
* Categorize columns containing text using LabelEncoder
* Standardize numerical columns using BoxCox
* Identify and correct outliers

<b> 5. Model building </b>

* Splitting the dataset 70/30 for testing and training

* Building several models and identifying the best one based on its accuracy score:


* Improving the model chosen using RFE:


## Results
The best model to classify outlets into 4 types for this dataset would be logistic regression. Overall, the 2 most important features identified are the item visibility and outlet sales. 
