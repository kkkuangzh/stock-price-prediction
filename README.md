# Stock price prediction


## Abstract

Stock price prediction has always been a hot research area due to its underlying connection with the economy, business, and politics, etc. In this project, 6 related indicators along with stock prices of APPLE company are selected to predict the stock price of APPLE in May 2020 using data from the past three years, which includes prices of two related futures (gold and crude oil), the overall trend of the stock market (the DJIA Index and the NASDAQ 100 Index) and subjective factors (Twitter sentimental score, and ratings). Three RNN LSTM models are trained using data from the past 60 days to compare performances of different input features. The result shows that combining highly correlated indicators as input can improve performance, and the mean squared error and R2 score of the RNN-5 model are 1.429 and 0.701 respectively. Finally, the RNN-1 model is used to predict based on the combination of both truth and predicted stock prices, and the result shows that the model is not capable of predicting long-term prices far into the future.

## Introduction

Time series prediction is a valuable and significant research field, among which stock price prediction is the most representative and well concerned one. The stock market is important and attracts much attention due to its specialty in finance and business industries. Although stock market is dynamic and hard to predict due to its intrinsic characteristics, many studies have been done trying to find the patterns of stock prices. Since it has proven that some indices have a certain de- gree of correlations with the stock price, the goal of this experiment is to forecast new stock prices using past values with the help of some correlated indicators.

## Method

## Results
