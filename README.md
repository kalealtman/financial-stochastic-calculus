# financial-stochastic-calculus
Scripts created for use in Palle Jorgenson's MATH 4250 stochastic calculus class. Number labels correspond to homework problems in [Kerry Back's A course in Derivative Securities](url)

Scripts are labeled according to their content. They contain the following:
- __binomial-model-Americans-and-Monte-Carlo:__
plot the value of an option price using a binomial model for various step sizes to show the price convergence for large N. Determine the N required for the binomial model to achieve penny accuracy with the Black-Scholes option price. Calculate the European and American prices of the same put option to find the parameters have the most impact on early exercise premium of American options. Modeled European call option prices at various strikes using a Monte Carlo simulation of the GARCH model.

- __call-on-forward-price:__
using Black's formula and the market price of a call option on a forward contract, calculates the implied volatility of the forward price.

- __compute-call-options:__
takes various methods to compute the price of a call option and ensures they arrive at the same answer

- __delta-hedged-simulations-and-Mertons:__
computes the gain/loss at different percentiles for a delta-hedged call option on a forward contract. Also calculates the price of a call option using Merton's formula.

- __exchange-rate-simulation:__
using Brownian motion, simulate the path of a foreign exchange rate under the risk-neutral measure. Using this, can calculate the profit of a delta-hedged portfolio given simulated paths of the underlying asset and foreign exchange rate. Can do the same with a forward-hedged portfolio.

- __exotic-option-hedging-portfolios:__
Simulates the price of an asset to observe the quality of its hedge with a standard European call and a down-and-out option, considering the cost of each options in the profitability on an end-of-year basis. Adds to that by considering a down-and-in call, and compares again. Builds new hedging simulation with 4 different combinations of exotic hedging to compare in the same way. Priced a floating strike call option using Monte Carlo simulation, an American put option with a binomial model, an average price call option with Monte Carlo simulation, and a European basket call option with a binomial model.

- __exotic-options:__
provides pricing functions for various exotic options and explores their inherent special characteristics. For forward-start option, plots price as strike set date gets closer to maturity date. For call-on-call compound, computes value changes with large jumps in underlying asset price. For dividend paying American options, plots early exercise premium amount against dividend value. Prices simple chooser option using put-call parity. Compares chooser value to a straddle of the same options. Calculates the minimum required fee for a lookback option. Simulates the price of an asset to observe the quality of its hedge with a standard European call and a down-and-out option. 

- __greeks-option-plots:__
plots the value of a call option using the Black-Scholes formula against various values of Delta, Gamma, and volatility to observe the relationship

- __Heston-stochastic-volatility:__
function to model the price of a European call option using the Heston stochastic volatility model in a Monte Carlo simulation, as well as the delta of that option. Tested on various strike prices of the option.

- __implied-volatility-and-hedging:__
takes option price data from Yahoo Finance to calculate the market implied volatility and plot the expected volatility "smile" and "smirk" for various strike prices. Also includes a function that calculates the gains and losses for a hedge of a call option that delta and gamma hedges with the underlying asset and another call option.

- __modeling-volatility:__
modeling the volatility of the same underlying stock using a "mixture of normals" approach, GARCH model, and Heston stochastic volatility

- __stochastic-sums:__
for a specified stochastic process (including a Brownian motion), sums the squared changes over a discrete time interval

