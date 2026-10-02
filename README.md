# ITAI-1371-ML-Dataset

Team: 14274 2_ITAI1371


Project Title: Exploratory Data Analysis & Real Estate Price Modeling

Project Link: https://github.com/W216988275/ITAI-1371-ML-MIDTERM.git 

Course: Mid Term - Exploratory Data Analysis

Dataset Source: Connecticut Real Estate Sales 2001-2021 (Kaggle)

Original Kaggle Dataset URL: https://www.kaggle.com/datasets/nrng19/real-estateLinks to an external site. 

Github Clean Dataset: https://github.com/W216988275/ITAI-1371-ML-DatasetLinks to an external site. 

Sample Dimensions: 25,000 records, 10 selected features


Group Members:

- Marisabel Morales

- Katherine Delores

- Joshua Balderas

# Project Description

For our Midterm project, our team selected a Real Estate Sales dataset from Kaggle. The dataset was reviewed and approved by our instructor. The working dataset contains approximately 25,000 records and 10 selected features, including property location, assessed value, sale amount, property type, residential type, sales ratio, and transaction date information.

The purpose of this project is to perform Exploratory Data Analysis (EDA) and data preprocessing using Python in Jupyter Notebook. The dataset will first be divided programmatically into 70% training data and 30% testing data. All EDA and preprocessing will be performed only on the training dataset, while the testing dataset will remain untouched.

The preprocessing process will include identifying and handling missing and invalid values, checking duplicate records, and preparing categorical and numerical features. Missing categorical values will be handled using an "Unknown" category. Feature engineering will also be performed by extracting Sale Year and Sale Month from the original transaction date.

Categorical features such as Town, Property Type, and Residential Type will be converted into numerical values using One-Hot Encoding. The Assessed Value feature will be normalized using a log transformation and then standardized using StandardScaler. Matplotlib visualizations will be used to compare the data before and after preprocessing.
For future machine learning work, the prepared dataset will be used to develop a Supervised Learning Regression model. The target variable will be Sale Amount, with the future objective of predicting real estate sale prices using property and transaction characteristics.

The final result of the Midterm will be a cleaned and processed training dataset that can be used during the Final Project to train and evaluate different machine learning regression models.
