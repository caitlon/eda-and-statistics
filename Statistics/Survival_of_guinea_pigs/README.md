# Survival of Guinea Pigs: A Statistical Analysis

## Project Overview:

This project applies statistical analysis to a dataset about the survival rates of guinea pigs under different experimental conditions. 
The dataset is split into two groups: the "Control" group, which was left untreated, and the "Bacilli" group, which was exposed to a bacterial agent. 
The objective is to analyze and compare these groups using statistical measures and distributions, hypothesis testing, and confidence intervals.

## Features:

1. **Distribution fitting**: Project involves fitting different distribution models - namely normal, exponential, 
and uniform distributions - to the data, and visually comparing these fitted distributions with the actual data. 
This assists in selecting the best fitting distribution model for the given data.
2. **Parameter Estimation**: The parameters for the chosen distribution models are estimated using the method of moments.
The estimated parameters are then used to generate a synthetic dataset that follows the same distribution as the original data.
3. **Comparison of the original and synthetic data**: The synthetic data generated in the previous step is then compared
with the original data to validate if the synthetic data follows the same distribution as the original data.
4. **Confidence Interval Estimation**: Then calculated a 95% confidence interval for the mean of the two groups.
This gives an interval estimate for the population mean, providing a range of values within which the true mean of the population is
likely to lie with 95% confidence.
5. **Hypothesis Testing**: Finally, performed a hypothesis test to see if the true mean of the population equals a given value K, at a significance level of 5%.
