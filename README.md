Gas-consumption-outliers
========================

The goal of this project is to detect "anomalies", unusual events, in energy consumption of buildings. The data are registrations of energy consumption (gas and electricity), weather conditions, occupance/use of the building. For many buildings also data arc avallable on parts of the building. The specific datathat will be used are from building of the University of Amsterdam and its sister organization, the Hogeschool van Amsterdam (Professional College). Historical weather data are available from Schiphol airport weather station.

Occupance data are extracted from calenders and the internet. The practical goal of this project is to find algorithms for reducing the consumption of fossile fuel and the CO2 production.

Steps
-------------
I tried to describe as much as possible the steps I have done.

* <a href="http://nbviewer.ipython.org/github/denadai2/Gas-consumption-outliers/blob/master/1-Dataset.ipynb">Dataset description</a>
* <a href="http://nbviewer.ipython.org/github/denadai2/Gas-consumption-outliers/blob/master/3-%20Regression_NN.ipynb">Neural network predictions</a>

Why
-------------
The results has a 14.14 RMSE, so it can't predict so well the gas consumptions, consecutively I can't run a good outlier detection mechanism. In blue you see the gas consumption, in green the prediction:<br />
<img src="https://i.imgur.com/sH0tPy6.png"><br />
I see that in some papers that even if they predict daily or hourly consumption in the electric power, they have errors like <a href="https://www.sciencedirect.com/science/article/pii/0301421595001166">MSE = 0.01</a>.

Why are my results so bad? What can I improve?

Other steps in progress
-------------
These are the steps I'm also trying. I tried them only for few hours. I'm reading various papers.
* <a href="http://nbviewer.ipython.org/github/denadai2/Gas-consumption-outliers/blob/master/GES.ipynb">extreme studentized deviate (ESD)</a>
* ARMA-ARIMA methods for time series
* linear models - SVD comparison (in some days)
