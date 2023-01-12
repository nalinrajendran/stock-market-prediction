# stock-market-prediction
A LSTM model to predict the closing prices of the desired stocks. 




# Predicting Stock Values using LSTM.
- Predicting stock price or movement is a very challenging task. Personally, I don't believe any of the stock prediction models available should be taken for granted or relied upon without careful consideration. 
- Models might, however, be able to accurately forecast changes in stock price the majority of the time, but not always.
Predicting the swings of the stock price is a more sensible course of action. 
- The findings you get have a huge impact on the model's hyperparameters. 
- Running certain hyperparameter optimization techniques (such as Grid search or Random search) on the hyperparameters would therefore be a very excellent idea. 
- Some of the most important hyperparameters are listed here.
-- The learning rate of the optimizer.
-- Number of layers and the number of hidden units in each layer.
-- The optimizer. I found Adam to perform the best.


## INSTRUCTIONS:

- Run the stocks.ipynb file for the stock prediction of the karur-vysa stocks.
- For the purpose of understanding and not using it for the realtime implementation, I have remove the API calls for the realtime stock data and replaced with an old CSV data.


### PRICE HISTORY OF DATA:
![image](https://user-images.githubusercontent.com/51052614/212008204-7e7177f8-34de-4cc2-9aef-b0ca8ffac03b.png)

### PREDICTED PRICE OF THE STOCK:
![image](https://user-images.githubusercontent.com/51052614/212008419-ea50f1f8-8e4c-45ec-872a-e3bc97f5c790.png)


## Real Stock Price:
![image](https://user-images.githubusercontent.com/51052614/212008504-5f37aa8a-7b44-4aab-847d-46816d4427b1.png)

