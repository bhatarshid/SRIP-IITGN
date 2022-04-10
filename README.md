# SRIP-IITGN

We will start by defining a simple PyTorch MNIST dataloader and afterwards set everything up to train. We will need the following functions to train a NN:
  1. A function that initializes the neural networks weights and returns a list of layer-specific parameters.
  2. A function that performs a forward pass through the network (e.g. by loop over the layers).
  3. A function that computes the cross-entropy loss of the predictions.
  4. A function that evaluates the accuracy of the network (simply for logging).
  5. A function that updates the parameters using some form gradient descent.

All of these will then be tied together in a training loop.
