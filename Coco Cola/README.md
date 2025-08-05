IF YOU ARE UNABLE TO SEE THE NOTEBOOK PREVIEW PLEASE PASTE THE GITHUB LINK IN NBVIEWER: https://nbviewer.org/  


Coca_Cola_Live is a notebook where the stock price for coco cola has been prediceted.  
The data has been trained on the past 5 years of ohlcv as well as dividends and stock split for the company.  
Algorithms used: RandomForestRegressor and GridSearchCV.  
Live prediction has been made using the intraday data.  

    
Coca_Cola_Models is a notebook where in I have tried different trading strategies and have backtested them.  
The data set use was the same 5 year ohlcv data set with 1 day candles.  
Main Libraries Used: FinTA for technical analysis and Backtesting to back test the algorithm  
  
  
Coco_Cola_RF_Backtesting is a notebook where I have combined all the above notebooks into one.  
It uses FinTA for Technical Indicators, RandomForestRegressor with Grid Search for prediction and Backtesting for testing the predictions in real scenario.  
The model was trained on 4 years of data barring the latests year ie. 4 years from 1 Year ago and tested over the last year that was excluded from the training.  
The pkl file is shared so as to not waste time in training the model again and again.  
