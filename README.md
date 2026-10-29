# Electricity-price-forecast-with-PyTorch
A machine learning project to use Pytorch, and in particular an LSTM implemented therein to forecast electricity prices
This is work in progress, over the next weeks more and more pieces will appear. I will explain here how to use them.
- The notebook "getting_the_data.ipynb" is about downloading the official data and saving it in a .csv
- The notebook "The naive LSTM.ipynb" includes the setup, training and evaluating of a LSTM-based model. The class "LSTM_predictor_improved" defines the best version of the model.
- The notebook "getting_weather_data.ipynb" downloads past weather data
- The notebook "forward_model_using_weather.ipynb" develops a model that uses the weather differences to calculate corrections to today's electricity price in order to calculate tomorrow's electricity price. This gives a model that is significantly better than the trivial model, if only predicting 3 price corrections for each day and obtaining the rest from linear interpolation.

##Future work
- The model will be tweaked to improve performance. In particular the times for the 3 price corrections are somewhat arbitrary so far. These times will be tweaked in the future
- A standalone version will be written in the future. This standalone version will be a single .py file together with some extra files containing the weights of the model. The .py file will predict the electricity price of the day following day.
