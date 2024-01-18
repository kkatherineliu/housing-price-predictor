I recently just finished Intro to Machine Learning, Intermediate Machine Learning, and Feature Engineering courses on Kaggle so I thought it was finally time to explore a real dataset.

This is the notebook I am working in to submit things into the beginner friendly [Kaggle Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data) which uses data from the Ames Housing Dataset.

I am slowly trying to apply the concepst I've learned in the courses to build a model that can perform well. Mostly focusing on data cleaning and feature engineering with the help of built-in Python libraries

Here are the general steps I will try to follow

**data cleaning**

- manipulate categorical data (one hot encoding, ordinal, target encoding)
- deal with missing data (imputation)

**creating a pipeline**

- split the training, validation, and testing data
- normalize or linearize features as necessary
- bundling the transformers for numerical and categorical information
- pipeline for preprocessing and training on the model

**choosing a model**

- linear regression? random forest/XGBoost?
- hyperparameters?

**measure the quality of the model** 

- visualizing the RMSE
- comparing different models/parameters
- Double-check the uses for cross-validation and see if they apply for this dataset

**other things to consider**

- real feature engineering (combining through + /)
- application of PCA and K-means clustering in this problem
- making use of MI to identify key features
