# Forecasting Future Stock Prices
Using historical data to simulate future stock prices, mainly using yahoo finance data. 

These 2 methods of using single-day forecasting and multi-day forecasting (bootstrapping) are quite intuitive, however, there are certain limitations, such as:

1. We assume that history would repeat itself exactly, which includes all the past extreme events, but it is also possible that potential future extreme events are not in the historical dataset as well. Basically, tail risks would be underestimated.
2. There is not forward looking volatility. It fails to adapt to sudden market changes, for example shocks like the 2020 COVID crash.
3. Path dependency is ignored where autocorrelation is ignored. For example, real markets show momentum and mean-reversion which will not be captured here. 

Therefore, one may usually prefer other more advanced models, such as the Black-Scholes Model, Laplace Transform and Monte Carlo Simulation, which you can find in my other repository "European Option Pricing". 
