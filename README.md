# Unit-10-Homework

## Regression Analysis 

In sample RMSE is 0.6 and the out of sample RMSE is 0.4. Usually the out of sample RMSE is higher than the in sample RMSE, which is not the case here. The higher the number the lower the accuracy, so the in sample data model is less accurate than the out of sample data. This is unusual because the im sample model is using actual data from the sample, the train data, while the out of sample model is using the test data.

## Time Series Analysis

Because the p value in the ARMA model is above .05, I don't feel confident in using the ARMA model for trading. The AIC and BIC values are also very high, when it's more reliable and valuable when thoe values are lower. The ARIMA model also doesn't seem to be good fit as the AIC and BIC values are very high, meaning they judge a dataset with larger parameters, and the larger the parameters, the harder it is to evaluate the data accurately. According to the GARCH model, it looks like investing in the Yen looks very risky, as the yens risk is assumed to increase over time. I would not feel comfortable using ARMA or ARIMA for trading purposes.
