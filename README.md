# Stock-Prediction-LSTM-model
Model to predict the stock prices of TESLA (TSLA) using the data of last 4 years 
- Recurrent Neural Networks have been used in the project
- LSTM ( To keep track of trends)
- Custom algorithm has been made to keep in track of last 50 days trend to make a prediction for the next day
- Data has been obtained from https://finance.yahoo.com/quote/TSLA/history?period1=1439683200&period2=1597536000&interval=1d&filter=history&frequency=1d
- Data has been taken from August 16 2015 to August 15 2020. The test data has consists of days from 13 July 2020 to August 15 2020.
  Train data consists of data from August 16 2015 to  13 July 2020.
- Goal is to predict stock prices for the 24 days(13/07/2020-14/08/2020) based on train data.
- There are 5 hidden layers and and one input layer and one output layer.
- LSTM has been used with a timestamp of 50 days ( To keep in track the trends)
If you have any suggestions to improve the model please do let me know.

