File containing all the code for the MCMC implementation.

* mcmc_functions contains all the code for the prior, likelihood, basic and adaptive mcmc, autocorrelation, gelman rubin, effective sample size
* run_mcmc is the code of me running the mcmcs and generating trace plots, stats and corner plots of each mcmc
* tuning_mcmc is me tuning the adaptive mcmc to the best paramaters to use to give the largest effect sample size by using 27 pilot runs
* adaptive_mcmc_results_final is a pickle file containing all the stats of the pilot runs so that i do not have to run it again

