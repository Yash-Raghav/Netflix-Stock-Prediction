# Netflix-Stock-Predictions

A time series analysis of historical data of Netflix stocks. The model utilizes three diffferent approaches to calculate the values.

- All values together using the complete historical data
- Predicting a fixed number of values at once(e.g. 10), feeding these values as historical data to the model and predicting the next batch of values. 
  Practically produced results similar to actual historical data compared to the previous method
- Using sequence to sequence modeling (Using time distributed layer). The dense time distributed layer is applied at every time-step during model run. 
  Produced the most similar results to actual historical data
