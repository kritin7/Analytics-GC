# Analytics-GC
## Problem Statement
* We are given 10,000 points for training your model. 
* The columns x1, x2, x3, and x4 are the independent variables, and they respectively represent OHLC ( Open - High - Low - Close) price data for a financial instrument
* Your task is to correctly predict the binary values (0 or 1) in the column titled ‘y’.
## Accuracy
* Final accuracy for train set using ARIMA is 54.91%
* Last 500 points of test set were predicted using our ARIMA model
## Bonus question
* y-label is the comparision between the current and next entry closing price
* y-label = 1 indicates that next closing price is greater than the current closing price
* y-label = 0 indicates that next closing price is lesser than the current closing price
