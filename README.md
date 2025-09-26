# data-analytics-linr
# Logistics Delivery Time Prediction

## Overview
This project focuses on building and evaluating a linear regression model to predict logistics delivery time based on the distance of the delivery. The process involves generating synthetic data, performing exploratory data analysis (EDA), visualizing the data, and implementing linear regression using two methods: scikit-learn's built-in model and a custom implementation using gradient descent.

## Project Contents
**Data Generation:** Synthetic data is generated to simulate a logistics delivery scenario, including distance and corresponding delivery times with added noise.

**Exploratory Data Analysis (EDA):** This section includes an examination of the generated data, checking for missing values, statistical summaries, and identifying potential outliers.

**Data Visualization:** Various plots (histograms, box plots, scatter plot, and heatmap) are used to understand the distribution of variables and the relationship between distance and delivery time.

**Linear Regression (scikit-learn):** A linear regression model is trained using the LinearRegression class from the scikit-learn library.

**Linear Regression (Gradient Descent):** A linear regression model is also implemented from scratch using the gradient descent optimization algorithm.

**Model Evaluation:** The performance of the scikit-learn model is evaluated using standard regression metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared. Residual analysis is also performed.

## Getting Started
### Prerequisites

To run this project, you will need:

- Python 3.6+
- Jupyter Notebook or Google Colab
- The following Python libraries: pandas, numpy, matplotlib, seaborn and scikit-learn
