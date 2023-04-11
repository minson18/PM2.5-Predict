# PM2.5-Predict
2023 Data Mining HW1
## Introduction
* Competition from <https://www.kaggle.com/competitions/2023-data-mining-hw1/overview>  
* Using linear regression only numpy
* With Stochastic Gradient Decsent and Regularization
* Using AdaGrad as optimizer
## Environment
Using Google Colab
## Data Pre-proccessing
* Clean data: drop unneeded columns, replace invalid as -1
* Transform data into forms that rows into continuous hours, columns into air pollution indices
* Filled invalid element by the next hour's value
* Normalize data by columns
## Result
My model achieve the following performance on submission.  
The scoring metric is RMSE    
|Model|Private Score|Public Score|
|-----|-------------|------------|
|Linear Regression|unknown|3.17348|
