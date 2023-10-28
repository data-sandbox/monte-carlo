# Monte Carlo Simulations 🎲

The Monte Carlo method (aka simulation) is a mathematical technique that utilizes randomness to estimate the outcome of an uncertain event. The method replaces any model parameter with a random variable from a probability distribution (such as a uniform or normal distribution). It then repeatedly computes the results many times over (commonly thousands of times), each time using a new value for the random variable(s) from the probability distribution.

By leveraging probability distributions, a Monte Carlo simulation builds a model of possible results and enables the measurement of uncertainty or risk in the model output.

This repo is a sandbox for experimenting with Monte Carlo simulations in Python:

- [Profit Projections](https://github.com/data-sandbox/monte-carlo/blob/main/profit_projection.ipynb) - Simulation to forecast future profits for a generalized business with a porfolio of products, with sales of each product modeled as a probability distribution.
