# CryptoCurrencyPricePredictor
Bitcoin Price Predictor
WHAT IS BITCOIN?
Bitcoin is a digital currency unlike physical currency, there is no third party in-between the transactions like a bank. Bitcoin is a decentralized cryptocurrency and its transactions are made between peer to peer.

WHY BITCOIN?
Recently, Bitcoin has gained a lot of attention from the media and the public for its recent price hike. As Bitcoin has been viewed as a Digital gold and is traded through many cryptocurrency exchanges like Coinbase, coindcxgo, etc.,
we thought it is a good idea to do something in the current trend and come up with something to predict the price of the bitcoin.

STEPS:-
          1) At first we need to collect the past 1-year historical data of bitcoin prices from the Yahoo Finance website then we use that as our main dataset and uploaded it as the source file dataset for predicting future prices in the Google colab platform.
          2)Then we have imported the pandas' library and for this bitcoin prediction, we have used the Facebook prophet model. We have imported prophet as well (which sends and receives the data set securely)
          3)The Facebook Prophet model only works with data that contains the time-series format in a column called “ds” and continuous values in a column called “y”. So the credentials were created for the data needs to receive accordingly.
          4)And the most important thing is we have fit the data into the Facebook prophet model
          5)The make_future_dataframe method in Prophet model has a parameter named ‘periods’, we can use it to set the amount of time we need to make predictions. Now let’s make predictions for the next 365 days:
          6)Now we have derived the output of price prediction in the form of graphical representation.
The accuracy of the program we have written will be around 60-70 which was verified for few weeks with the predicted values we got was with 67% of accuracy.
