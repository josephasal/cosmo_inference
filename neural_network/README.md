# Code for the Neural network
* nn_training is tuning and training an ensemble neural network on the simulated data, then making a prediction of omega m and h. Includes plots of loss over epochs, true vs predicted values and residuals.
* Noisy data is the data from simulating distance modulus vs redshift, it contains some noise based on the mean error of the observational data
* Simulating data is how i simulated the data using the cosmology equaitons, i then saved this data to a csv to train a neural network
* Layer_neuron_tuning_results are the results of trying differenent combinations of layers, neurons and batch size to find which one had the lowest loss
