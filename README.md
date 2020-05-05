# Bayesian_Optimizer_Option_Portfolios

Uses RobinHood API for stock and options data. 

Apply Bayesian Optimization techniques for constructing risk-defined options & derivatives portfolios.  

Implements a 2-stage approach such that the Bayesian optimizer first explores the parameter space to discover the most likely optimal subspace, and then in the second stage it exploits the parameter subspace discovered in Stage 1 to attempt to find an an optimized solution based on a custom defined objective function that maximizes on expected value across a range of future market outcomes.
