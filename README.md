# Parameter Optimization of SVM

## About SVM and Parameter Optimization

* Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.
* Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 
* We can perform this task using GridSearchCV for optimizing these parameters.
* In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository : 
[https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation)

This dataset is used for estimating the precise number of occupants in a room using multiple non-intrusive environmental sensors like temperature, light, sound, CO2 and PIR. It is a multi-variate classification Dataset.

Number of rows: 10129
Number of Attributes: 16

## Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.83 | rbf | 2.85 | 6.14 |
| 2 | 0.96 | linear | 7.39 | 1.56 |
| 3 | 0.89 | poly | 5.94 | 1.36 |
| 4 | 0.92 | linear | 7.65 | 2.73 |
| 5 | 0.86 | Linear | 5.99 | 8.25 |
| 6 | 0.84 | rbf | 2.78 | 1.81 |
| 7 | 0.93 | linear | 2.60 | 9.70 |
| 8 | 0.92 | linear | 4.44 | 9.99 |
| 9 | 0.97 | poly | 0.99 | 0.57 |
| 10 | 0.92 | linear | 3.98 | 7.32 |

## Convergence Graph
![graph](https://github.com/nishtha20k/Parameter-Optimization-SVM/blob/main/Convergence%20Graph.png)
