# Kaggle-House-Prices

This repository contains analysis of the Iowa House Price dataset from Kaggle. This dataset is part of a [sample competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) on Kaggle with a leaderboard measuring how accurate submitted predictions (obtained by modeling the training set of the data) are for the fraction of the data set that is retained as test data.

### Contents:
- Exploratory Data Analysis (3 parts; Jupyter Notebooks using R kernel)
  - Part 1: [Initial data ingestion & NA exploration and processing](https://github.com/GoldenKnight09/Kaggle-House-Prices/blob/main/Exploratory_Data_Analysis_Notebooks/Exploratory%20Data%20Analysis%20-%20Part%201.ipynb)
  - Part 2: [Continuous variable exploration](https://github.com/GoldenKnight09/Kaggle-House-Prices/blob/main/Exploratory_Data_Analysis_Notebooks/Exploratory%20Data%20Analysis%20-%20Part%202.ipynb)
  - Part 3: [Categorical variable exploration](https://github.com/GoldenKnight09/Kaggle-House-Prices/blob/main/Exploratory_Data_Analysis_Notebooks/Exploratory%20Data%20Analysis%20-%20Part%203.ipynb)
- Feature Transformation, Normalization, & Regression Analysis (3 parts; Jupyter Notebooks using Python kernel)
  - Part 1: [Transformation & normalization of train and test data sets](https://github.com/GoldenKnight09/Kaggle-House-Prices/blob/main/Feature_Transformation_Normalization_%26_Regression_Analysis/Feature%20Manip%2C%20Transform%2C%20Normalize.ipynb)
  - Part 2: [Linear regression analysis](https://github.com/GoldenKnight09/Kaggle-House-Prices/blob/main/Feature_Transformation_Normalization_%26_Regression_Analysis/Linear%20Regression%20Analysis.ipynb)
  - Part 3: [Second order with interaction terms regression analysis](https://github.com/GoldenKnight09/Kaggle-House-Prices/blob/main/Feature_Transformation_Normalization_%26_Regression_Analysis/Second%20Order%20with%20Interaction%20Regression%20Analysis.ipynb)
- Machine Learning Analysis (2 parts; Jupyter Notebooks using Python kernel)
  - Part 1: [Random forest regression](https://github.com/GoldenKnight09/Kaggle-House-Prices/blob/main/Machine_Learning_Analysis/Random%20Forest%20Regression.ipynb)
  - Part 2: [Gradient boosting regression](https://github.com/GoldenKnight09/Kaggle-House-Prices/blob/main/Machine_Learning_Analysis/Gradient%20Boosting%20Regression.ipynb
  
## Key Learnings:
- Regression analysis revealed the main factors that influence house sale price were:
  - Above ground square footage
  - Overall house quality
  - Lot size
  - Age of house
- Utlizing machine learning using a gradient boosting regression method resulted in the best predictive modeling fit employing a model that included second order & interaction terms.
