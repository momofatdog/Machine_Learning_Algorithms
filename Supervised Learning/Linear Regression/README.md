# Linear Regression
This project covers the algorithm of linear Regression for lagged Time-Series variables. Time series forecasting has enormous commercial significance because stuff that is important to a business like demand and sales, number of visitors to a website, stock price etc are essentially time series data. We forecast the variable of interest in a multiple regression model using a linear combination of predictors. We predict the variable of interest in an autoregression model by utilizing a linear combination of the variable's historical values. The word autoregression refers to a regression of a variable against itself.

An autoregressive model of order p can be written as:

$$y_t = c+\phi_1y_{t-1}+\phi_2y_{t-2}+...\phi_py_{t-p}+\epsilon_t. $$

where $\epsilon_t$ is white noise. This is like a multiple regression but with lagged values of $y_t$ as predictors. We refer to this as an AR(p) model, an autoregressive model of order p.

## Data
I will use **Alphabet Inc (NASDAQ: GOOGL)** closing stock price as a sample time series data.

## Package 
I will use the following packages in this project:
* [matplotlib.pyplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
* [numpy](https://numpy.org)
* [pandas](https://pandas.pydata.org)
* [pandas_datareader](https://pandas-datareader.readthedocs.io/en/latest/)
* [plotly.express](https://plotly.com/python/plotly-express/)

## Reference

Mehta, I. (2020, May 16). Simple Linear Regression Fit And Prediction On Time Series Data With Visualization In Python | By Ishan Mehta | Medium. Medium. https://ishan-mehta17.medium.com/simple-linear-regression-fit-and-prediction-on-time-series-data-with-visualization-in-python-41a77baf104c.

Time Series Analysis In Python - A Comprehensive Guide With Examples - ML+. (2019, February 13). Machine Learning Plus. https://www.machinelearningplus.com/time-series/time-series-analysis-python/.

8.3 Autoregressive Models | Forecasting: Principles and Practice (2nd Ed). (n.d.). 8.3 Autoregressive models | Forecasting: Principles and Practice (2nd ed). https://otexts.com/fpp2/AR.html.

Alphabet Inc. (GOOGL) Stock Price, News, Quote & History - Yahoo Finance. (n.d.). Alphabet Inc. (GOOGL) Stock Price, News, Quote & History - Yahoo Finance. https://finance.yahoo.com/quote/GOOGL/.
