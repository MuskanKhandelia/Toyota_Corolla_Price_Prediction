# Toyota Corolla Price Prediction Model

This repository contains Python code to create and evaluate multiple linear regression, ridge regression, and lasso regression models for predicting the price of a Toyota Corolla. The models use various features such as Age_08_04, KM (Accumulated Kilometers on odometer), HP (Horse Power), cc (Cylinder Volume in cubic centimeters), Doors (Number of doors), Gears (Number of gear positions), Quarterly_Tax (Quarterly road tax in EUROs), and Weight (Weight in Kilograms).

## Machine Learning Lifecycle

The machine learning lifecycle steps were followed to build, train, and evaluate the models. Python packages such as pandas, seaborn, and sklearn were utilized for data cleaning, analysis, visualization, and model building.

## Data Insights

Insights generated from the analysis include:

- 'Age_08_04' has a good negative correlation with the target variable 'Price'.
- 'KM' and 'Weight' are moderately correlated with the target variable.
- Other variables do not have much correlation with the target variable.
- The data is not normally distributed; it is mostly skewed.
- There are too many outliers in the data.

## Model Performance

### Linear Regression Model:

- Training Accuracy: 0.86
- Mean Absolute Error: 1007.0
- Testing Accuracy: 0.86
- Mean Absolute Error: 1012.06

### Ridge Regression Model:

- Training Accuracy: 0.86
- Mean Absolute Error: 1006.96
- Testing Accuracy: 0.86
- Mean Absolute Error: 1011.88

### Lasso Regression Model:

- Training Accuracy: 0.86
- Mean Absolute Error: 1006.88
- Testing Accuracy: 0.86
- Mean Absolute Error: 1011.88

## Conclusion

The models exhibit similar performance across linear regression, ridge regression, and lasso regression. The training and testing accuracies are consistent, and the mean absolute errors are comparable. The models appear to be generalized and not overfitting the data.
