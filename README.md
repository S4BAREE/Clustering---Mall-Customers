# Clustering---Mall-Customers


## Intro 
The Dataset contains details of customers like age, sex, annual income, spending score,.. Spending Score is determined by the mall and the value of the spending score is between (1-100). The spending score near to 100 indicates that the customer has spent more money in the mall and when spending score is near 1 that indicates customer has spent less in the past in the mall. But the dataset does not tell in which category the customers belongs which indicates clustering should be performed.

## Overview 
When the mall advertisement team has to send advertisement to the customers on the new products and if the advertisement is send to 10000 customers there are chances that only 10% of the customers will buy the product which will not be efficient. Inorder to improve the efficiency the Customer data set should be analized to cluster the customers based on the annual income and spending score so that the the customers who spend more can be targetted first.

This project aims to predict the spending scores of customers in a mall. The spending score is a measure that indicates how likely a customer is to spend money in the mall based on their demographic and behavioral attributes

## Table of Contents
  ### Project Overview
  ### Data
  ### Methodology
  ### Code Structure
  ### Dependencies

 ### Project Overview
The goal of this project is to develop a machine learning model that can predict the spending score of mall customers. By analyzing customer attributes such as age, gender, annual income, and spending habits, the model aims to provide insights into customer behavior and assist in targeted marketing strategies.

### Data
The dataset used in this project contains information about customers in the mall, including their age, gender, annual income, and spending score. The data was collected through surveys and is provided in a CSV format. The dataset consists of X samples and Y features.
### Methodology
The following steps were followed in this project:

Data Exploration: Perform exploratory data analysis to gain insights into the data, identify any missing values or outliers, and understand the distribution of the features.

Data Preprocessing: Preprocess the data by handling missing values, scaling numerical features, and encoding categorical variables as necessary.

Feature Selection: Select relevant features based on their correlation with the target variable and eliminate any redundant or irrelevant features.

Model Selection: Choose an appropriate machine learning algorithm for spending score prediction, such as linear regression, decision trees, random forests, or gradient boosting.

Model Training: Train the selected model using the preprocessed data. Utilize appropriate techniques for model training, such as cross-validation or regularization, to optimize the model's performance.

Model Evaluation: Evaluate the trained model using appropriate evaluation metrics, such as mean absolute error (MAE) or root mean square error (RMSE), to assess its accuracy and generalization capabilities.

Model Deployment: Deploy the trained model to a production environment or integrate it into an application to provide spending score predictions for new customer data
### Code Structure
The codebase is organized as follows:

data/: Directory to store the dataset file.
notebooks/: Jupyter notebooks containing code for data exploration, preprocessing, model training, and evaluation.
src/: Source code directory.
data.py: Code for loading and preprocessing the data.
model.py: Implementation of the machine learning model for spending score prediction.
utils.py: Utility functions used throughout the project.
README.md: This file, providing an overview of the project and instructions for usage.
requirements.txt: List of dependencies required to run the project.
### Dependencies
The following dependencies are required to run the project:

Python 3.x
pandas
scikit-learn
matplotlib
seaborn








