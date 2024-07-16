# SalaryPrediction
Developed a Salary Prediction based on a dataset that included the years of experience of each professional in the industry. Used a simple linear regression machine learning algorithm that I implemented from scratch.

# Simple Linear Regression from Scratch

This project demonstrates a simple linear regression implementation from scratch using Python. The dataset used in this example is `salary_data.csv`, which contains two columns: `YearsExperience` and `Salary`. The goal is to predict the salary based on years of experience.

## Requirements

- Python 3.x
- pandas
- matplotlib
- numpy

You can install the required libraries using pip:

```bash
pip install pandas matplotlib numpy

## Files

salary_data.csv: The dataset containing YearsExperience and Salary.
SimpleLinearRegressionScratch.ipynb: The Python script that performs linear regression from scratch and visualizes the results using matplotlib.
SimpleLinearRegression_scikit.ipynb: The Python script that performs linear regressions using the scikit-learn library, and visualized the results using Seaborn.
regression_plot_prediction_matplotlib.png: Plot that shows the relationship between years of experience and salary plus the Simple Linear Regression Line using Matplotlib.
regression_plot_seaborn.png: Plot that shows the relationship between years of experience and salary plus the Simple Linear Regression Line using Seaborn.
plot_matplotlib.png: Plot that shows the relationship between years of experience and salary using Matplotlib. 
 
## Usage

Ensure that salary_data.csv is in the same directory as SimpleLinearRegressionScratch.ipynb: or SimpleLinearRegression_scikit.ipynb depending on if you would like to use the algorithm implemented by Scratch, or the one utilizing Scikit-learn.

## Description

The script performs the following steps:

1. Load and visualize the data:
- The dataset is loaded using pandas.
- A scatter plot is created to visualize the relationship between years of experience and salary.
2. Calculate the regression coefficients:
- The mean of YearsExperience and Salary is calculated.
- The deviations from the mean (errors) are computed.
- The slope (b1) and intercept (b0) of the regression line are calculated using the least squares method.
3. Predict the salary:
- Using the calculated coefficients, the salary is predicted for each value of years of experience in the dataset.
4. Plot the results:
- A scatter plot of the actual data and the regression line is created.
- The plot is displayed and saved as an image file (regression_plot.png).

## Evaluate the model:
The Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² (coefficient of determination) are calculated and displayed.

