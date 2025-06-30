# An Overview
Cleaned the dataset, removed outliers, and pre-processed the data in a format suitable to the objective

Performed extensive EDA or Exploratory Data Analysis to understand the relationships between the variables and data points

Fit the processed data into various models including Logistic Regression, Random Forest, LightGBM, XGBoost to make predictions and arrive at the best model through comparison

Charted a comparison table for the ease of determining the best model and accuracy

# About the Dataset
The data is related to direct marketing campaigns of a Portugese banking institution.

The marketing campaigns were based on phone calls.

Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be subscribed ('yes') or not ('no') subscribed.

Target or dependent variable is 'y' column, a binary feature which represents if client has subscribed to a term deposit ('yes'/'no')

# Data Cleaning
After the data was loaded in with pandas, it was cleaned, and the following changes were made:

Column ‘Duration’ was converted into hours format for ease of analysis

Outliers from the column ‘Duration’ were removed using IQR or Inter Quartile Range method

# EDA (Exploratory Data Analysis)
EDA was performed extensively to gather insights into the data
