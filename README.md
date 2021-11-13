# Time-Series-forecasting-using-Tensorflow
Time series problems deals with data over time.

Problem types :

- Classification - output is in Discrete form (a label)
- Forecasting - output is in Continuous form (a number)

In forecasting the price of Bitcoin, your data could be the historical price of Bitcoin for the past month and the label could be today's price (the label can't be tomorrow's price because that's what we'd want to predict).

Steps followed :
- Get data
- Format Data Part 1: Creatining train and test sets for time series data
- Modelling Experiments :

  0. Model 0 : Naive Model (baseline)
  1. Dense Model 1 (window = 7, horizon = 1)
  2. Same as Model 1 (window = 30, horizon = 1)
  3. Same as Model 1 (windwo = 30, horizon = 7)
  4. Conv1D (window = 7, horizon = 1)
  5. LSTM (window = 7, horizon = 1)
  6. Same as 1 (but multivariate data) (window = 7, horizon = 1), extra data => Block Reward Size 
  7. N-BEATS Algorithm (window = 7, horizon = 1)
  8. Ensemble (multiple models optimized on different loss functions) (window = 7, horizon = 1)
  9. Future prediction model (model to predict future values) (window = 7, horizon = 1)
  10. Same as 1 (but different data) (window = 7, horizon = 1)
