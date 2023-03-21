# Boston Housing Dataset Analysis and Model Building
#### Introduction
In this project, we have analyzed the Boston Housing Dataset and built regression models using various algorithms. The Boston Housing Dataset contains information about different houses in Boston and the corresponding house prices. The goal is to build a model that can predict the price of a house given its characteristics.

#### Dataset
The Boston Housing Dataset contains 506 rows and 14 columns. The columns represent the following information:

- CRIM: per capita crime rate by town
- ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS: proportion of non-retail business acres per town
- CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- NOX: nitric oxides concentration (parts per 10 million)
- RM: average number of rooms per dwelling
- AGE: proportion of owner-occupied units built prior to 1940
- DIS: weighted distances to five Boston employment centers
- RAD: index of accessibility to radial highways
- TAX: full-value property-tax rate per $10,000
- PTRATIO: pupil-teacher ratio by town
- B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- LSTAT: % lower status of the population
- MEDV: Median value of owner-occupied homes in $1000's

#### Analysis
We have used various data analysis and visualization techniques to understand the data and identify any patterns or correlations. Some of the techniques used are:

Correlation matrix and heatmap to identify any correlations between the variables
Pair plot to visualize the relationship between each pair of variables

#### Models
We have built regression models using various algorithms such as:

- Linear Regression
- Ridge Regression
- Random Forest Regression
- XGBoost Regression
- Decision Tree Regression

For each algorithm, we have used pipelines to preprocess the data and train the model. We have also used hyperparameter tuning to find the best set of hyperparameters for each model.

#### Conclusion
In conclusion, we have analyzed the Boston Housing Dataset and built regression models using various algorithms. The XGBoost Regression model performed the best with an R2 score of 0.91. The other models also performed well with R2 scores between 0.66 and 0.85. The models can be used to predict the price of a house given its characteristics.
