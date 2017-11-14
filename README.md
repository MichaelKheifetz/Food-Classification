# Fraud-Detection

# Introduction
This dataset consists of 56,000+ transactions and the objective is to build a binary classification model that will detect whether the transaction was a food expense transaction or not. The original variables in the dataset are the type of transaction, a description of this transaction, what country the transaction occured in, the amount, the amount on a daily basis, whether the transaction was a Receipt or Per Diem and the actual variable to be predicted, (Food vs Not Food).

# Data Cleaning
First, I look at the null values, outliers and create dummy variables and categorical variables for some features and bin them by count. I also engineer a feature. Imputation is done on null values using an advanced technique and the dataset is afterwards scaled. Additionally, the data is TfidfVectorized for one of the text features.


# Exploratory Data Analysis (EDA)
I look at a heatmap and several scatterplots to look for strongly correlated variables from a visual perspective to give additional insight into their behavior.


# Predictive Modelling
Feature Selection is done first for dimensionality reduction purposes. Afterwards, Random Forest and Support Vector Machine Models are fitted and used to predict. The parameters are also tuned using Randomized Grid Search for the Random Forest and multiple metrics are looked at for both models (ROC Curve, Sensitivity, Specificity, etc).

# Conclusion
The conclusion discusses the results and potential avenus for further investigation.
