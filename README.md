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

 

Selected Features (Refined per instructor consultation):
   - Identifiers & Temporal: Serial Number, List Year, Date Recorded

   - Geographic & Location: Town, Address

   - Valuation & Financials: Assessed Value, Sale Amount, Sales Ratio

   - Classification Attributes: Property Type, Residential Type

   (Note: Excluded metadata identifiers and trailing blank columns programmatically in Python).

 

Summary of Planned Pre-Processing (Midterm Deliverable):
   - Train/Test Split: Programmatic 70% Train / 30% Test split using Scikit-Learn; test partition left untouched in cold storage.

   - Missing Value Imputation: Impute missing entries in 'Property Type' and 'Residential Type' using explicit indicator labels ('Unspecified' / 'Non-Residential'); address nulls filled with 'Unknown Address'.

   - Categorical Encoding: One-hot encode nominal categories ('Property Type', 'Residential Type').

   - Normalization & Scaling: Apply log-transformation (log1p) to skewed monetary fields ('Sale Amount', 'Assessed Value'), followed by StandardScaler standardization.

   - Visual Verification: Generate Matplotlib side-by-side distribution histograms comparing raw vs. normalized distributions and class balance counts.

 

Proposed Downstream Machine Learning Problem (Finals):
   - Supervised Regression: Train regression models (Linear Regression, Random Forest, XGBoost) to predict property 'Sale Amount' using assessed valuations, location, and property characteristics.

   - Binary Classification: Classify whether a real estate transaction is undervalued ('Sales Ratio' < 0.70) versus standard market valuation.
