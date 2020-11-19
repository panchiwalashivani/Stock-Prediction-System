# Stock-Prediction-System
Stock Prices Prediction &amp; Portfolio Optimization using Machine Learning with Python &amp; Scikit Learn

# Stock Predictor and Portfolio Optimizer

A novice's attempt for (weekly) stock prices prediction and portfolio optimization.

### Technologies used - 
* Python 3
* Scipy
* Scikit-learn
* matplotlib

### Data Source
* [Quandl Data platform](https://www.quandl.com/)

### Major Features
* Prediction of stock prices on weekly basis (predicting next week's prices for a given stock)
* Optimizing portfolio distributions ( optimum ratio of each stock in a portfolio to potentialy maximize profits )

### Algorithms and implementation mechanisms
* Weekly prediction is being done using KNN Regressor using "Bollinger Band Value" and "Simple Moving Average" as input features.
* Stock porfolio optimizer is done for maximizing the "Sharpe Ratio" or "culumative returns", using scipy minimizer (minimizing for -1 * value)

### Testing and results
* This application has been tested for National Stock Exchange, India. The weekly predictions have upto 75 % corelation with the actual results, for the leading (largest market capitalization) stocks.

### TODO
* Add all dependancies in requirements.txt
* Creating web services
* Creating Web-based front-end.
* Improving accuracy by adding more Fundamental and Technical features



