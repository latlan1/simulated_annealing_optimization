# simulated_annealing_optimization

## Description
Using Simulated Annealing to optimize for best Wine quality

## Using Simulated Annealing to optimize model input parameters

There are various approaches that one can take to reverse-engineer a trained
machine learning model and we explore this problem by implementing simulated
annealing (SA). SA can be used to optimize over discrete search domains such as
over the wine characteristics like acidity and pH to find the best quality wine.
This example illustrates the potential of applying SA to other problems perhaps
with larger but sparser datasets.

## Notebook 1: optimization_of_wine_quality_compare_cooling_method

## Notebook 2: optimization_of_wine_quality_linear

This is the start of my foray into optimization techniques that can be used on empirical
datasets to find optimal ranges of parameters. Alternative techniques include Bayesian
optimization (can be used for model hyperparmeter optimization or for expensive cost
function calls) and BFGS optimization algorithm (to find the best input parameters to a pre-trained deep neural
net model).
