# Heart Disease Prediction

![Heart Disease Prediction Banner](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSeW4PZEE8ej81ubST0KnwnIeOpEpyAC5cewA&s)  <!-- Replace with the URL of your banner image -->

## Project Overview

This project involves predicting the presence of heart disease based on various health metrics. The dataset used includes information such as age, sex, blood pressure, cholesterol levels, and more. The goal is to build a predictive model that can accurately classify whether a patient has heart disease.

## Data Cleaning

1. **Data Loading:** The data was loaded from a CSV file named `heart_disease_data.csv`.
   
2. **Checking for Missing Values:** The dataset was inspected for any missing values. No missing values were found, as confirmed by checking the count of non-null values for each column.
   
3. **Data Summary:** The data was summarized to understand the range and distribution of values. Descriptive statistics were generated to provide insights into the dataset's characteristics.

## Data Analysis

1. **Target Variable Analysis:** The distribution of the target variable, which indicates the presence of heart disease, was analyzed. The dataset contains two classes: 
   - `1` for patients with heart disease
   - `0` for patients without heart disease

2. **Feature Standardization:** To ensure that features are on the same scale, standardization was applied. This process scaled features to have a mean of 0 and a standard deviation of 1.

## Model Building

1. **Data Splitting:** The dataset was split into training and testing sets. The training set consisted of 80% of the data, and the testing set consisted of 20%.

2. **Model Selection:** A logistic regression model was chosen for classification. This model was trained on the standardized training data.

3. **Model Evaluation:** The model's performance was evaluated using accuracy scores:
   - **Training Data Accuracy:** 84.71%
   - **Testing Data Accuracy:** 78.69%

## Conclusion

The logistic regression model provides a reasonably accurate prediction of heart disease based on the available features. Further improvements could be made by experimenting with different algorithms or incorporating additional features.



