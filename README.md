# Forecasting-United-States-Energy-Consumption-Trends-A-SARIMA-Approach

The paper’s goal is analysis and forecast of United States energy consumption from January 2000 to 
December 2023, using a Seasonal Autoregressive Integrated Moving Average (SARIMA) model. This 
paper uses a compiled monthly series of total US energy consumption, obtained from the Energy 
Information Administration (EIA), to fit a prediction model that captures seasonal variations and timeseries trends. The SARIMA model was identified by following the Box-Jenkins methodology. After 
ensuring data is stationary, we analyzed autocorrelation and partial autocorrelation plots of a
transformed version of the original data to identify initial model orders. In the project the data was 
transformed with log transformation and was differenced to account for seasonality and to achieve 
stationarity. To estimate parameters, we used Maximum Likelihood Estimates (MLE) to determine 
parameter significance, Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC).
These values led us to explore more models and pick the final one. Each model’s residuals were 
examined to determine if residuals resemble white noise. The selected model was applied to predict and 
visualize multiple time points in the future alongside a prediction and confidence interval calculation.
