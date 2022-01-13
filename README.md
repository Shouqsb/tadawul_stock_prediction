# tadawul_stock_prediction

## Abstract
Saudi stock market is being large goal and attract many investors as one of goal of 2030 to be expanded and include more investors so, we decide to apply machine learning on this major (Tadawul) to predict stock price and can be use it by many organizations.


## Data
Saudi Stock Exchange (Tadawul) dataset which used in machine learning project taken from Kaggle. The data is from Saudi stock market companies since 2000-01-01 until 5-3-2020. It was collected from Saudi Stock Exchange (Tadawul). It contains 14 column and more than half million row also, As there are many sectors , and we decide to choose two sectors which are Energy and Communication service.
The dataset found at [Kaggle](https://www.kaggle.com/salwaalzahrani/saudi-stock-exchange-tadawul).

## Algorthim
* Retype some column’s names to make them more consistent
* Change ```date``` data type
* Handling with nulls values ```pandas```
* Visualization the data using ```matplotlib.pyplot```
* Filter the sectors by (Energy and communication services)
* apply the model on two companies in each sector

*Models*
We used different machine learning algorithms on one company which is National Shipping Company of Saudi Arabia Co.(BAHRI)‏ in energy sector to compare each model to find the best one which achieves best results.


Linear Regression :
* True Prediction Percentage : 33%	

Random Forest :
* True Prediction Percentage : 55%

Decision Tree :
* True Prediction Percentage : 44%

SVM :
* True Prediction Percentage : 22%

Long short-term memory (LSTM) :
* True Prediction Percentage : 71%


## Findngs and Result
As the above results, the LSTM model gives best results , thus, we apply the LSTM model on the oldest four companies in Energy and Communication Service sectors.


## Tools
* `pandas` for data manipulation
* `sklearn` for modeling
* ```matplotlib```  for plotting


