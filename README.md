# Bayesian_analysis

In this project, I am going to estimate generalized linear models (GLMs) for binary (Bernoulli) and Binomial response variables using the stan_glm function in the rstanarm package.

The four steps of a Bayesian analysis are:

1) Specify a joint distribution for the outcome(s) and all the unknowns, which typically takes the form of a marginal prior distribution for the unknowns multiplied by a likelihood for the outcome(s) conditional on the unknowns. This joint distribution is proportional to a posterior distribution of the unknowns conditional on the observed data
2) Draw from posterior distribution using Markov Chain Monte Carlo (MCMC).
3) Evaluate how well the model fits the data and possibly revise the model.
4) Draw from the posterior predictive distribution of the outcome(s) given interesting values of the predictors in order to visualize how a manipulation of a predictor affects (a function of) the outcome(s).

Firstly, I clean the data in python and use the cleaned data for further analysis in R. 
