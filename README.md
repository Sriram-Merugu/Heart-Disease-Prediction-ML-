# Heart-Disease-Prediction-ML
This project aims to predict heart disease using logistic regression. It utilizes the heart disease dataset (heart_disease.csv) 
containing various attributes such as age, sex, cholesterol levels, blood pressure, and other factors.

# Code Overview

The heart_disease dataset is loaded using pandas and the first five rows are displayed.
A logistic regression model is fitted to the data, with the target variable "AHD" predicted based on the "Age" feature.
The "Sex1" column is created to replace the numeric values of sex (1 for male, 0 for female) with more descriptive labels.
A cross-tabulation is performed to show the frequency of counts for each combination of "Sex1" and "AHD," and the results are normalized and displayed.
Odds ratios and logarithmic odds ratios are calculated and added to the cross-table.
Another logistic regression model is fitted, this time predicting "AHD" based on the "Sex1" variable.
Model summaries are generated, including the coefficients, standard errors, p-values, and goodness-of-fit statistics.
A third logistic regression model is fitted, predicting "AHD" based on multiple features such as age, sex, cholesterol levels, blood pressure, fasting blood sugar, resting ECG, slope, oldpeak, number of major vessels (Ca), exercise-induced angina (ExAng), chest pain type, and thalassemia type (Thal).
Scatter plots and regression lines are created to visualize the relationship between age, cholesterol levels, and heart disease.
A plot of partial residuals for age is generated.
The final logistic regression model is fitted with all the available predictor variables, and the corresponding summary statistics are provided.
Predictions are made using the fitted model on a subset of the dataset, and the results are converted to binary outcomes.
The predicted outputs are stored in a pandas Series object.

# Usage

To use this code, follow these steps:

Ensure you have Python and the required libraries (pandas, statsmodels, seaborn, matplotlib) installed.
Download the heart_disease.csv dataset and place it in the same directory as the code file.
Execute the code and observe the results.
Feel free to explore and modify the code to fit your specific needs.

