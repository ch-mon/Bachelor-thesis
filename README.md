# Bachelor thesis
This project contains the Python code we used for my Bachelor's thesis. The goal was to establish a relationship between the order parameter of a physical system and variables learned by the Machine Learning algorithms.
- First, we generated different configurations of the 2D Ising model and the 2D rod model via Monte-Carlo-Markov-Chain (MCMC) integration.
- Second, we analyzed these configurations via Principal Component Analysis (PCA).
- Lastly, we conducted a similar analysis by training and evaluating a Variational Autoencoder (VAE) on the configurations.

The different files contain code for:
1. Simulation of Ising model configurations via MCMC (using the Wolff-Cluster-Algorithm)
2. Simulation of rod model configurations via MCMC (using the Metropolis-Algorithm)
3. PCA Analysis on the Ising model configurations
4. PCA Analysis on the rod model configurations
5. Training and evaluating a VAE on Ising model configurations
6. Training and evaluating a VAE on rod model configurations
