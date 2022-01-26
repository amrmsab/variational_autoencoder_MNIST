#  Variational Bayes Auto-encoder on the MNIST dataset

In this repository, I reproduce the results in Kingma and Welling (2013) implementing a Variational
Autoencoder (Auto-Encoding Variational Bayes) to reconstruct MNIST digits.

The highlights are as follows:
1. I plot digit characterizations in the autoencoder's latent space illustrating that the trained model is able to group (cluster) MNIST images according to their class (label)

![alt text](https://github.com/amrmsab/variational_autoencoder_MNIST/blob/main/images/0to5.JPG?raw=true)


2. I use this latent space representation to see what `interpolating’ between numbers looks like. For example, we generate numbers between 0 and 5:

3. I reconstruct a digit image given only its top half.
