# Predict Loan Status - Data Preprocessing and Classification

## Overview
This repository focuses on predicting loan status by employing a comprehensive data preprocessing pipeline and utilizing popular classification models. The workflow includes handling missing values, addressing outliers, conducting statistical tests, and implementing machine learning algorithms like Logistic Regression, Support Vector Machines (SVM), XGBoost, and RandomForest.

## Repository Contents

1. **Data Preprocessing:**
   - **Missing Values:**
     - Impute missing values using Forward Fill (FFill), Backward Fill (BFill), Fill by Median, and KNN Imputer.
   - **Outlier Handling:**
     - Use Quantile-Based Method and Winsorization to manage outliers.

2. **Statistical Tests:**
   - **Chi-squared Test:**
     - Assess the independence of categorical variables for loan status prediction.
   - **Correlation Analysis:**
     - Explore the relationships between numerical features and loan status.

3. **Modeling:**
   - **Logistic Regression:**
     - Implement logistic regression for binary classification.
   - **Support Vector Machines (SVM):**
     - Utilize SVM for robust classification.
   - **XGBoost:**
     - Employ the XGBoost algorithm for enhanced predictive performance.
   - **RandomForest:**
     - Harness the power of RandomForest for accurate and stable predictions.

## Instructions

1. **Data Preparation:**
   - Ensure your dataset is in the required format.
   - Adjust the file paths in the preprocessing and modeling scripts accordingly.

2. **Data Preprocessing:**
   - Run the data preprocessing script to handle missing values and outliers.

3. **Statistical Tests:**
   - Execute the statistical tests script for chi-squared test and correlation analysis.

4. **Modeling:**
   - Run each modeling script (Logistic Regression, SVM, XGBoost, RandomForest) to train and evaluate the respective classification models.

5. **Results and Analysis:**
   - Review the generated results, model performance metrics, and analysis in each script.
