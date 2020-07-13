# Risk Analysis - The probabilistic approach to safety

# Overview

Rather than using point values to represent random quantities, as in deterministic approaches, probabilistic approaches to risk assessment represent each random quantity by a probability distribution. Analysis results are presented as probability distributions, or as selected quantiles of a probability distribution.

The probabilistic approach to risk analysis estimates risk as a function of:
- The severity — or magnitude — of each consequence
- The likelihood (probability) of the occurrence of each consequence

In the safety domain, the consequences and types of events assessed are generally adverse (they represent losses, that we try to avoid). In other areas such as finance, events and their consequences may be either positive (profits) or negative (losses).

Consequences are expressed quantatively (for instance, the number of people potentially injured) and their likelihoods of occurrence are expressed as probabilities.

# Modules

1. Correlation Analysis

Before starting to create risk models, it is a good idea to visualize how the variables are related to one another. Risk models often involve correlated random variables, and exploring correlation between variables is an important part of exploratory data analysis. In this module, we learn how to measure the degree of linear dependency between two random variables using Python and the SciPy library. We also explore a number of warnings related to dependency, causality and correlation in risk. 

2. Linear Regression Analysis

Linear regression analysis means *fitting a straight line to data*. It’s a widely used technique to help model and understand real-world phenomena, which is easy to use and to understand intuitively. It allows prediction of future outputs from the phenomenon we are modelling. In this module, we learn how to use plots for exploratory data analysis, to determine whether a linear model might be suitable for the data, build univariate and multivariate linear models using the Python statsmodel library. We also present a number of possible pitfalls when using linear regression, including sample size issues, treatment of outliers and order of effect problems.

3. Statistical Modelling
4. Reliability Engineering
5. Reliability Analysis, including reliability data
6. Monte Carlo Methods for Risk Analysis
7. Copula Methods for Multivariate Modelling
8. Value at Risk - Measuring Financial Risk