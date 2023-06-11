# DATA-CLEANING

This repository contains code and resources for cleaning the FIFA21 dataset. The dataset contains information about football players, including their attributes, performance statistics, and contract details.

Methods Used

1. Handling Missing Values: The dataset may have missing values in certain columns. We employ various techniques to handle these missing values, such as imputation or removing the rows with missing values, based on the specific requirements of the analysis.

2. Data Type Conversion: The dataset may have columns with incorrect data types. We carefully convert the data types of columns to ensure consistency and accuracy. For example, converting string representations of numbers to numeric data types.

3. Removing Duplicates: Duplicates in the dataset can skew the analysis. We identify and remove any duplicate rows to ensure that each player's information is unique.

4. Standardizing and Cleaning Text: Text columns often contain inconsistencies, such as leading or trailing whitespace, different capitalization, or special characters. We apply text cleaning techniques to standardize and clean these columns for better analysis and visualization.

5.Handling Outliers: Outliers in the dataset can significantly impact statistical analysis. We detect and handle outliers using appropriate methods, such as truncation or imputation, to ensure the validity of the results.

6.Feature Engineering: We create new features from the existing data that can provide additional insights or improve the analysis. This may involve calculating derived metrics, aggregating data, or creating categorical variables based on certain conditions.

7.Data Validation: We validate the dataset for integrity and correctness, ensuring that the data follows the expected patterns and rules. This includes checking for data inconsistencies, logical errors, or unrealistic values.
