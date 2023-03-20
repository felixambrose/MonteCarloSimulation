# MonteCarloSimulation
Notebook containing an example of portfolio optimisation using MC simulation.

1) Download stock data from the yahoo finance API
2) Extract the mean log return and the covariance matrix of the stocks over 300 days
3) Firstly, simulate over a 100 day period with random sampling of stock weights.

## Adjust the loop

1) Add an inner loop which, for each sample, simulates 50 times for each stock weights, and then we can aggregate mean daily returns and average volatility.
2) Plot Efficient Frontier 
3) Calculate Sharpe Ratio, and highlight optimised portfolio.
