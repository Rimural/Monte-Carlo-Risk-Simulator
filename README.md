# Monte-Carlo-Risk-Simulator
A Python-based Monte Carlo simulator comparing hypothetical strategies through profitability, drawdown, volatility, and probability of ruin.

## Features
- simulate thousands of possible outcomes
- calculate average profit and max drawdown
- measure standard deviation of simulated profits
- estimates the probability of bankroll ruin
- calculates approximate 95% confidence intervals for ruin probability
- compares multiple strategies

## How To Run

run monte_carlo_risk_simulator.py using Python 3

The simulator uses Python's random library and needs no additional packages

## Limitations
- Assumes independent outcomes with fixed probabilities and payoffs.
- Stops simulation when the bankroll reaches zero
- Uses a normal approximation for confidence intervals, which can be inaccurate for rare events
- Does not model actual financial markets, transaction costs, or changing market conditions

## Future Improvements
- Use NumPy for faster simulations
- Use pandas to organize results
- Add visualizations
- Explore more realistic models
