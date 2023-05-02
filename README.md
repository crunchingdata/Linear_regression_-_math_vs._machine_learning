# Project 2 overview: Linear regression and model performance
* Implemented linear reggression for revenue prognostic through machine learning and math.
* Controlled accuracy of the linear regression through MSE, MAE, coefficient of determination and RMSE.
* Compared linear regression trough machine learning with linear regression through math.

## Code and resources used
* Python 3.9.15.
* Packages: pandas, numpy, math, seaborn, matplotlib.pyplot, statistics, sklearn.model_selection, sklearn.linear_model.
* dataset: 500 rows of daily revenue by temperature of a ice cream shop in IceCreamData.csv

## Data cleaning
* Created a column with random values for comparison of obtained measures.
* Just a overview was requiered, because of non null-values:
![](/images/scatterplot_with_pairplot.jpg)

## EDA

![](/images/scatterplot_with_math_linear_regression.jpg)
* asd
![](/images/scatterplot_with_corridor_68_data_math.jpg)
*asdsa
![](/images/ML_scatterplot_train_data.jpg)
![](/images/ML_scatterplot_test_data.jpg)
![](/images/ML_red_vs_Math_blue_scatterplot.jpg)

## Model Building
## Model performance
The Random Forest model far outperformed the other approaches on the test and validation sets.
* Random Forest : MAE = 11.22
* Linear Regression: MAE = 18.86
* Ridge Regression: MAE = 19.67
![](/images/ML_scatterplot_random_data.jpg)
