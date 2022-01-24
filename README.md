# Prediction of chaotic dynamical systems and Convergent Cross Mapping

### Notebook 1: Nonlinear prediction of chaotic dynamical systems

The method proposed by Sugihara and May (Nature, 1990) entails first choosing an embedding dimension, $n$, and then predicting $y_t$ by using past observations $\vec y_p(t) = (y_{t-1}, y_{t-2}, \dots, y_{t-n}) \in \mathbb{R}^n$. 

This method, like others that aim at predicting future values of chaotic dynamical systems, is based on Takens and Sauer theorems (see: http://www.scholarpedia.org/article/Attractor_reconstruction)

Complete description of the algorithm and commented code in the notebook, including an application on the Lorenz attractor
