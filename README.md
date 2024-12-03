# RNN-stock-price-prediction

Main objective:

- to compare and evaluate the performance of Long Short-Term Memory (LSTM), Vanilla Recurrent Neural Networks (VanillaRNN), and Gated Recurrent Units (GRU) in stock price prediction, based on standard error metrics such as root mean squared error(RMSE) and R-squared.

- trialling through all different dropout rate, learning rate, number of units and others to find best hyperparameter for each RNNs

Results :
- All RNN models were tested with 60-day windows and the loss function, mean squared error were used across the experiment. Overall, VanillaRNN with 60-day windows had best accuracy (R-squared = 0.66) compared to LSTM (R-squared = 0.63)  and GRU (R-squared = 0.55).

- Dataset can be found here: https://www.kaggle.com/datasets/rahulsah06/gooogle-stock-price
