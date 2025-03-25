# Cosmological Parameter inference using MCMC and Nerual Networks
* This project uses both MCMC and NNs to infer cosmological parameters from the Lambda CDM model. The main parameters it estimates are dimensionless Hubble constant (h) and the matter density (omega m)
* The MCMC is done using the Metropolis Hastings algorithm and I have introduced various optimisations such as multiple walkers and an adaptive sapling algorithm to ensure a more robust sampling method.
* The neural network is trained on simulated data and is then used to predict h and omega m
