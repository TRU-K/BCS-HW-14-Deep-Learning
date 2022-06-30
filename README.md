# Deep-Learning-HW
This repo contains homework for unit 14 of my fintech course.

## Overview
Contained within the jupyter notebook's of this repo, is an LSTM RNN model that utilises the Fear and Greed Index (FNG) of Bitcoin (BTC) in one model and the previous closing prices of BTC in the other. The goal is to predict future BTC prices and make a comparison between the two models and conclude which model performs this task better.

## Comparison
### Which model has a lower loss?
  The model using previous closing prices had a loss at 0.0096. While the model ulising FNG to predcit prices had a significantly higher loss of 0.1636
### Which model tracks the actual values better over time?
![Close](https://user-images.githubusercontent.com/99452833/176668982-ef059b47-86cd-4add-85bd-e862dc52a8b2.png)
![FNG](https://user-images.githubusercontent.com/99452833/176669107-f9eac620-945a-4d8d-9165-29cf15ea90b7.png)
As can be seen above the model utilising the previos close prices is much more effective at tracking actual values over a period of time.

## Model Analysis
### Which window size works best for the model?
I utilised a window size of 300 epochs as I found this to be an effective size to give great results.

## Conclusion 
By comparing these two models, that use different features to predict future close prices, there is a clear model that performs better which is the model using previous close prices. This model closely aligned with the actual close prices.
