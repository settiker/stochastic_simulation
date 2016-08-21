# Simulation Methods for Stochastic Systems

##Projects 

###<1>Monte Carlo (MC) and  Markov chain Monte Carlo (MCMC) simulations
Finding the line of best-fit for the relationship between estimated variance and MC sample size, 
and adapting our MC solution to provide integral and error estimates for the given function. 
Secondly, implementing stratification and importance sampling and comparing the different MC integral
estimates and their sample variances. Finally, implementing Metropolis-Hastings algorithm, 
and plotting the sample paths for the algorithm using different proposal pdfs.

###<2>Mixture models simulations
Implementing a 2D Random number generator(RNG) for a Gaussian mixture model(GMM) PDF, 
Expectation Maximization (EM) algorithm and comparing the quality and speed of GMM-EM 
estimation on samples of different GMM distributions. Also, applying our GMM-EM algorithm 
to fit the data to a GMM pdf, plotting final GMM pdf, and overlaying the contour plot 
with a scatterplot of the data set.

###<3>Samples and test simulations
Generating IID samples of the random variable (RV) having Weibull distribution using the 
inverse CDF method. Secondly, implementing Rejection sampling routines(RSR) for a given 
RV which has a bimodal distribution, generating samples and tracking the rejection rate 
of our rejection sampling RNGs for each envelope function. Finally, implementing RSRs for 
the standard half-normal RV and Beta RV, generating samples of each RV, testing and 
verifying the two sets of samples for independency.

###<4>Gas Bootstrap Confidence Intervals
Generating a set of {Number of heads} obtained by flipping a fair as well as an unfair coin 
multiple times, for which Scatter plots and Histograms are plotted. Also, resampling a given 
data set with replacement for multiple times, calculating the mean in each of these cases, 
sorting and calculating 95% Bootstrap confidence interval for both the cases of fair and unfair coins.  
