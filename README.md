# Electricity-price-forecast-with-PyTorch
A machine learning project to use Pytorch, and in particular an LSTM implemented therein to forecast electricity prices
This is work in progress, over the next weeks more and more pieces will appear. I will explain here how to use them.
- The notebook "getting_the_data.ipynb" is about downloading the official data and saving it in a .csv
- In "price_data.csv" price data downloaded that way is saved
- The notebook "The naive LSTM.ipynb" includes the setup, training and evaluating of a LSTM-based model. The class "LSTM_predictor_improved" defines the best version of the model.
- 
In the future I will improve the model so it also uses weather forecast data. When I am happy about the model, I will put a .py file here so it can be used directly to get a forecast in a single step.
