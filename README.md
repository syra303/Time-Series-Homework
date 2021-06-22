# Time-Series-Homework

## Time-Series Analysis
Based on your time series analysis, would you buy the yen now?

Is the risk of the yen expected to increase or decrease?

Based on the model evaluation, would you feel confident in using these models for trading?

Based on my time series analysis looking, I would buy the yen now with the expectation that the price of the Yen will continue to increase in the coming days. Looking at the Garch model, it looks like volatility will also be increasing within a five day period so high price swings to the downside and upside should be expected.

I would not be confident using the ARMA and ARIMA models for trading as the P-values for both models were above 0.05 leading me to be less confident in the features being used in these models.


## Regression Analysis

With an out-of-sample rmse of 0.415 and an in-sample rmse of 0.596, it appears our model has a smaller average error when running data it has not seen vs the data it had been training with. Since it is expected that the training data should have an rmse that is less than the testing data, it could be that our sample data for the test data was too small and that as more data is added to our test data we would then see our out-of-sample rmse rise and eventually be greater than our in-sample rmse.