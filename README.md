#  Variational Bayes Auto-encoder on the MNIST dataset

In this repository, I reproduce the results in Kingma and Welling (2013) implementing a Variational Autoencoder (Auto-Encoding Variational Bayes) to reconstruct MNIST digits.

The highlights are as follows:
1. I plot digit characterizations in the autoencoder's latent space illustrating that the trained model is able to group (cluster) MNIST images according to their class (label)
In the image below, each digit image corresponds to one point. Digits of the same class have the same color.

![alt text](https://github.com/amrmsab/variational_autoencoder_MNIST/blob/main/images/latent_space.JPG?raw=true)

2. I use this latent space representation to see what `interpolating’ between numbers looks like. For example, we generate numbers between 0 and 5:

![alt text](https://github.com/amrmsab/variational_autoencoder_MNIST/blob/main/images/0to5.JPG?raw=true)

3. I reconstruct a digit image given only its top half. Below is the whole image of which we give only the top half to the model. The model then reconstructs the bottom half.

![alt text](https://github.com/amrmsab/variational_autoencoder_MNIST/blob/main/images/reconstruction.JPG?raw=true)
