# Bitcoin_USD_Prediction_and_Classification
I used a generalized linear model with decision trees as weak learners in order to predict future closing prices for the dataset. I then used a linear regression model, with and without Lowess distribution, to show the differences in model fit, after a line graph revealed the vacillating values given by linear regression. Additionally, I used two different classification models to generate confusion matrices after creating a binary value to measure whether or not there was an overall loss during the day, determined by opening and closing prices. I also calculated the surprise and entropy of each binary outcome occurring. Overall, one of the greatest challenges in this project was adapting data to DMatrices, which are a data structure native to XGBoost, and instead I ended up using a route that was more integrated with other libraries. I look forward to being able to create another iteration of this project with the original approach.

I obtained my dataset from https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data. Additional sources of information include:

https://github.com/dmlc/xgboost/blob/master/demo/guide-python/generalized_linear_model.py

https://seaborn.pydata.org/tutorial/regression.html

https://campus.datacamp.com/courses/extreme-gradient-boosting-with-xgboost/regression-with-xgboost?ex=4

https://www.youtube.com/watch?v=YtebGVx-Fxw&list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF&index=8
