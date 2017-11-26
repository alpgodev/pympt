# pympt
Python Software for Modern Portfolio Theory

PyMPT is a free software package for portfolio optimization and analysis based on the Python programming language.

The project is hosted at github:
http://alpgodev.github.com/pympt

Portfolio optimization is a problem faced by anyone trying to invest money (or any kind of capital) in a group of investments (i.e. stock market). Typically, such investment have two competing goals:

- Maximize return
- Minimize risk

Maximizing return means selecting a group of investments that collectively result in the highest expected yield. Minimizing risk means selecting investments that are most likely to actually result in the yields we expect.

Implemented algorithms (portfolio optimization):

- Higher order moments optimization
- Tail risk optimization
- Optimal risk budgeting
- Index tracking and fund replication
- Robust optimal hedging of non-linear portfolios
- Mean absolute deviation (MAD) model
- Expected utility optimization using factor models (Infanger, 2010)
- Optimal hedging of illiquid assets

Implemented Risk Analytics:

- Tail risk analysis: robust VaR, expected shortfall and drawdown measures
- Ratios: Sharpe, Sortino, information, omega
- Diversification and concentration measures
- Risk and performance decomposition
- Non parametric estimation of the distribution of returns (Robust Kernel Distribution Estimation)
- Risk and performance back testing
- Reactive risk models: adaptive correlation and covariance matrices (risk pooling, regime changes)
- Robust risk models: patented noise covariance matrices filtering
- Correlation based systemic risk models
- Aggregation of heterogeneous data (frequency and length of the time series)
- Robust beta models
- Factor based scenario simulations and stress testing
- Generating shocks on correlations

## Installation

There are several options for installation:

* From scratch:

* pip install pympt

* From a fresh git checkout:

* python setup.py develop

* python setup.py install

## Dependencies

pip install cvxopt

pip install numpy

pip install scipy

pip install pandas

