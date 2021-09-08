# Stock price prediction

The dataset is collected from [Yahoo!Finance](https://finance.yahoo.com) using [yfinance](https://github.com/ranaroussi/yfinance)

## Abstract

Stock price prediction has always been a hot research area due to its underlying connection with the economy, business, and politics, etc. In this project, 6 related indicators along with stock prices of APPLE company are selected to predict the stock price of APPLE in May 2020 using data from the past three years, which includes prices of two related futures (gold and crude oil), the overall trend of the stock market (the DJIA Index and the NASDAQ 100 Index) and subjective factors (Twitter sentimental score, and ratings). Three RNN LSTM models are trained using data from the past 60 days to compare performances of different input features. The result shows that combining highly correlated indicators as input can improve performance, and the mean squared error and R2 score of the RNN-5 model are 1.429 and 0.701 respectively. Finally, the RNN-1 model is used to predict based on the combination of both truth and predicted stock prices, and the result shows that the model is not capable of predicting long-term prices far into the future.

## Notice

The correct order of looking at these ipynb files should be
1. Data acquisition and storage
2. Data preprocessing
3. Data exploration
4. Data inference

These files are reorganized and may not contain all the raw codes used to test functions in the experiment.

Most of the running results can be seen in each output cell, however, some codes are not run here (upload data to the cloud, processing tweets, etc.) as they are already done and saved in correct formats.

In the *Data inference.ipynb* file, the *"Build and train LSTM models"* section should be skipped to avoid retraining the models.

