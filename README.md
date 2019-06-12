# Stock_Price_Prediction

This project predicts next day's SP500 index based on the previous index.
This is a Udacity nanodegree project. A project proposal is also uploaded.

Libraries used:
- numpy
- pandas
- talib
- sklearn
- matplotlib

talib is used to calculate the technical indicators as additional features.
To install this package with conda run:
conda install -c quantopian ta-lib

'SP500-index-prediction.cvs' is used as the original input data, which was
downloaded from Yahoo finance.
'Dow.cvs' and 'NASDAQ.cvs' are used as input data for robustness test, which were
downloaded from Yahoo finance.
