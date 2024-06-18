#Shell Stock Price Prediction using LSTM

- Yfinance was used to get the stock price dataset
- An Moving Average or the context of previous 100 days price was used to predict the nth day's price
- A Custom LSTM Model was created with 4 LSTM layers coupled with Dropout Layers and one Dense Layer to get the output.
- 50 epochs were run reducing the loss upto 0.028 and in 2nd iteration 20 epochs were run
- Predicted and Actual Values were evaluated by plotting a graph
- Finally Recursive Prediction was applied to predict the next 25 days price.
- Since there is very little Information to have correlation as it is completely dependent on one feature that is the price itself, predictions were partially Accurate
- Learnt about Moving Averages , LSTM and Forecasting
- Tech : Numpy , Pandas , Sklearn , yfinance , Python
