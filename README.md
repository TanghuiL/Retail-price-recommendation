Retail price recommendation system

This notebook shows how to build a sale price predictive model to provide recommendation for retail pricing. The data is the training set from the "Mercari Price Suggestion Challenge" on Kaggle. 

https://www.kaggle.com/c/mercari-price-suggestion-challenge/data

LightGBM is used for buidling the model. 
As a gradient boosting framework that uses tree based learning algorithms, LightGBM is designed to be distributed and efficient with the following advantages: 
1. Faster training speed and higher efficiency
2. Lower memory usage
3. Parallel and GPU learning supported
4. Capable of handling large-scale data

The model performance is evaluated using the metric, mean_squared_error, from sklearn. 