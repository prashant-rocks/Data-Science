# Candy Dataset Analysis and Modelling : Predict the win percentage

![enter image description here](https://github.com/prashant-rocks/Data-Science/blob/master/Machine%20Learning/Regression-Model-Candy-Dataset/src/images/candy.jpg)

## What we are analyzing and achieving

 1. We are analyzing the data within the candy-dataset through different preprocessing technique like: shape, info, description etc.
 2. We see data through different graphs like: heatmap, jointplot, subplot to see how data is behaving and if it is tending to normalized or not.
 3. We will see how explanatory variables are explaining the target variable.
 4. We will clean data after analysis as well as standardize the same to provide weightage accordingly.
 5. We will try to create and compare models to better predict the target variable.


## Data Analysis and Modelling

 1. We see that there is not missing/null values and so we don’t need to fill any values.
 2. We have 3 continuous columns in last and rest categorical columns except competitorname.
 3. We can see continuous columns sugarpercent, pricepercent and winpercent are nearly normalized as mean is nearly equal to 50% value.
 4. We see that there is no collinearity issue as there are no two explanatory variables are highly correlated( corr value > .8 ) and so we don’t need to remove columns for the same.
 5. There is no collinearity issue as there are no two explanatory variables are highly correlated( corr value > .8 ) and so we don’t need to remove columns for the same.
 6. We decide to go with REGRESSION model technique to predict the target variable which is continuous.

## Conclusion

 1. We have applied two Regression approaches: Linear Regression and Decision Tree Regression.
 2. After evaluation through RMSE and R-Squared values, we observe that Decision Tree Regression better predict the data as it provides better RMSE values for both test as well as train data for the same algorithm.
 3. We also observe that dataset is small and so getting better value of RMSE/R-Squared value is dependent.

