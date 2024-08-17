# Predicting Potential Personal Loan Customers for Thera Bank

## Problem Statement
Thera Bank aims to expand its customer base by converting liability customers (depositors) into personal loan customers. The goal is to identify potential customers who are more likely to accept a personal loan offer using a predictive model. By targeting these customers, the bank can increase the success ratio of its campaigns while minimizing costs.

## Project Overview
This project involves developing a machine learning model that predicts which liability customers are more likely to purchase a personal loan. The process includes thorough data exploration, feature analysis, model selection, and performance evaluation. By the end of this project, we aim to present a model that helps Thera Bank effectively target potential loan customers in future marketing campaigns.

### Steps Involved:
1. **Data Loading and Preprocessing:**
   - The dataset contains features like age, income, family size, education level, and more, along with a target variable indicating whether the customer accepted a loan.
   - Data cleaning and preprocessing tasks include handling missing values, outliers, and converting categorical data for model compatibility.

2. **Exploratory Data Analysis (EDA):**
   - Visualizing the distribution and relationships between different features using histograms, count plots, and correlation heatmaps.
   - Identifying key patterns and trends, such as which customer segments are more likely to accept loans.

3. **Feature Engineering and Selection:**
   - Assessing the importance of each feature using correlation and statistical analysis.
   - Preparing features for model training by normalizing, encoding, and transforming them as necessary.

4. **Modeling and Evaluation:**
   - Implementing multiple machine learning models such as logistic regression, decision trees, and ensemble models.
   - Evaluating model performance using metrics like accuracy, precision, recall, and AUC-ROC to choose the best-performing model.



## Key Findings
- The analysis reveals that features like income, credit card spending, and education level are critical predictors of loan acceptance.
- The model demonstrates a strong ability to predict potential customers, with a high **AUC-ROC score of .995**, and **accuracy of 98.6%** indicating reliable classification.

## Repository Structure
- `EDA and Predictive Modeling.ipynb`: The main notebook containing the entire workflow from data loading to model evaluation.
- `Data.xlsx`: The dataset used for the analysis.
