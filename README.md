Gas-consumption-outliers
========================

The goal of this project is to detect "anomalies", unusual events, in energy consumption of buildings. The data are registrations of energy consumption (gas and electricity), weather conditions, occupance/use of the building. For many buildings also data arc avallable on parts of the building. The specific datathat will be used are from building of the University of Amsterdam and its sister organization, the Hogeschool van Amsterdam (Professional College). Historical weather data are available from Schiphol airport weather station.

Occupance data are extracted from calenders and the internet. The practical goal of this project is to find algorithms for reducing the consumption of fossile fuel and the CO2 production.

What is an outlier
-------------

I'm looking for an unusual data point in a temporal series (e.g. sudden jump in the consumption), but also for an unusual pattern of changes (contiguous pattern indicative of a malfunction in the system).

Steps
-------------
I tried to describe as much as possible the steps I have done.

* <a href="http://nbviewer.ipython.org/github/denadai2/Gas-consumption-outliers/blob/master/1-Dataset.ipynb">Dataset description</a>
* <a href="http://nbviewer.ipython.org/github/denadai2/Gas-consumption-outliers/blob/master/3-%20Regression_NN.ipynb">Neural network predictions</a>


Other steps in progress
-------------
These are the steps I'm also trying. I tried them only for few hours. I'm reading various papers.
* <a href="http://nbviewer.ipython.org/github/denadai2/Gas-consumption-outliers/blob/master/GES.ipynb">extreme studentized deviate (ESD)</a>
* ARMA-ARIMA methods for time series
* linear models - SVD comparison (in some days)

Now I need to verify these hyphotesis/papers:
-------------
* [Focused backPropagation algorithm for pattern recognition](http://www.cs.colorado.edu/~mozer/Research/Selected%20Publications/reprints/Mozer1989.pdf)
* [Hybrid ARIMA-NNs](cs.uni-muenster.de/Professoren/Lippe/diplomarbeiten/html/eisenbach/Untersuchte Artikel/Zhan03.pdf)
* [A Feed-Forward Neural Networks-Based Nonlinear Autoregressive Model for Forecasting Time Series](http://www.scielo.org.mx/pdf/cys/v14n4/v14n4a8)
* [Novel FTLRNN with Gamma Memory for Short-Term and Long-Term Predictions of Chaotic Time Series](http://www.hindawi.com/journals/acisc/2009/364532/)
* [Gamma memory](http://scholar.google.com/scholar?q=http://dx.doi.org/10.1016/S0893-6080%2805%2980035-8): in order to not use Tapped delay memories
* [An artificial neural network (p, d,q) model for timeseries forecasting](https://www.sciencedirect.com/science/article/pii/S0957417409004850)
* [Recurrent NN](http://erikbern.com/?p=589)
