# GoDaddyy-Microbusiness-Density-Forecasting-using-XGBoostRegressor

The goal of this competition is to predict monthly microbusiness density in a given area. You will develop an accurate model trained on U.S. county-level data. Your work will help policymakers gain visibility into microbusinesses, a growing trend of very small entities. Additional information will enable new policies and programs to improve the success and impact of these smallest of businesses.

I first read the training data using pandas python library. I then check for missing data and perform basic exploratory data analysis. 

I later import xgboost and use it to make predictions on the training data and find the mean absolute and mean squared error. I tune the hyperparameters and then make predictions on the test dataset. I finally export the predictions to a submission.csv file.
