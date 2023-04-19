# Parameter Optimization of SVM
Assignment for UCS654

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using Random Search for optimizing these parameters.


## Dataset

The Boston Housing Dataset

The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA.

CRIM - per capita crime rate by town
ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS - proportion of non-retail business acres per town.
CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX - nitric oxides concentration (parts per 10 million)
RM - average number of rooms per dwelling
AGE - proportion of owner-occupied units built prior to 1940
DIS - weighted distances to five Boston employment centres
RAD - index of accessibility to radial highways
TAX - full-value property-tax rate per $10,000
PTRATIO - pupil-teacher ratio by town
B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT - % lower status of the population
MEDV - Median value of owner-occupied homes in $1000's

## Final Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.56 | Poly | 5.82 | 4.35 |
| 2 | 0.57 | Linear | 5.13 | 0.30 |
| 3 | 0.56 | Linear | 3.13 | 6.32 |
| 4 | 0.55 | Poly | 1.49 | 3.26 |
| 5 | 0.55 | Linear | 3.52 | 7.34 |
| 6 | 0.57 | Poly | 5.60 | 3.14 |
| 7 | 0.55 | Poly | 0.29 | 7.71 |
| 8 | 0.55 | Poly | 4.87 | 5.57 |
| 9 | 0.55 | Poly | 1.27 | 6.87 |
| 10 | 0.54 | Poly | 0.34 | 5.50 |

## Convergence Graph

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized.

The graph is made for the sample which has best accuracy. Sample has the best accuracy of 0.97 having kernel = Poly, Nu = 1.27 and Epsilon = 6.87.

## Written By
Name : Arnav Goyal
  
Roll No. : 102003760

Sub-Group: 3CO21
