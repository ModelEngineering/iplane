# TASKS
# Clean up existing code
* RandomContinuous: variate\_arr, dx\_arr, density\_arr
* Has predict method that estimates density for N X M array of points
* Calculates variate, dx, density
* Calculates entropy
* makeDCollection uses calcVariate, calcDx, calcDensity
# Evaluate the quality of empirical fits
* Multicomponent GMM
* Evaluate estimation of entropy with incremental grid sizes
# Evaluate the quality of GMM fits
* Estimator
  * Constructed with a sample
  * fit() estimates parameters
  * predict() for a value
  * plot compares predicted with actual
  * loss calculates squared error loss
* EmpiricalDistribution is an Estimator
  * Analyzes empirical distributions
  * Constructed with sample data (initiall 1-d)
  * CDF fit (with a spline?). Provide CDF value at designated variate.
  * Predict gives value of CDF
* RandomUniform
  * Parameters - lower, upper bound
  * Distribution - density_arr, dx
* How well can GMM fit a unifrom distribution? Look at distance of fit from distribution? Look at difference in entropy?
# Investigate culmulative entropy
* Calculate entropy for parts of a distribution
# Joint distribution
* Calculate joint distribution of GMM and categorical.
* Calculate condition distributions
* Calculate mutual information
# Reevaluate iplane analysis with solid calculations of entropy
