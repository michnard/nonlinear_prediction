# Prediction of chaotic dynamical systems and Convergent Cross Mapping

### Notebook 1: Nonlinear prediction of chaotic dynamical systems

The method proposed by Sugihara and May (Nature, 1990) entails first choosing an embedding dimension, n, and then predicting future values by using a library of past observations. 

This method, like others that aim at predicting future values of chaotic dynamical systems, is based on Takens and Sauer theorems (see: http://www.scholarpedia.org/article/Attractor_reconstruction)

Complete description of the algorithm and commented code in the notebook, including an application on the Lorenz attractor

### Notebook 2: Convergent Cross Mapping applied to real data

This method (Sugihara et al., 2012) looks for the signature of time-series x_1 in time-series x_2 by checking if the second can be used to predict the first.

As an example, this method is applied the dataset included in statsmodels (https://www.statsmodels.org/dev/datasets/generated/interest_inflation.html), German inflation rate vs. interest 1972-1998 (measured each quartile). We prove that interest rate causes inflation, but not the opposite.

Finally, we compare the results with what obtained form a Granger causality test.
