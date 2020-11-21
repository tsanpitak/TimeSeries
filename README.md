## Regression Analysis
### Model
Simple single lag regression model using train/test window to evaluate model

### Conslusion
Out-of-sample RMSE is smaller than In-sample RMSE, this suggest that the model may over-fit the data. We should use a sliding window with shorter training time frame to further test the model.

## Time Series Analysis
### Model
- Use Hodrick-Prescott Filter to shows trend/noise in the model 
- Create price forecasting models using ARMA, ARIMA, and volatility forecasting model using GARCH

### Conclusion

- Based on analysis, I will not buy the yen now. I might buy it a few days later or long straddle for the week.
- The risk of yen is predicted to increase
- I would have low confidence in using GARCH model to help trade derivative. However, I won't use ARMA or ARIMA for trading yen future.