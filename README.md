# Reverse_MNIST-GAN
I tried to train a network in the reverse way starting from labels uptil an image gets generated. This is an approach similar to GANs.

## GANs (Generative Adversarial Networks):
GAN is a neural network used for Synthetic data generation. 

Its architecture consists of 2 networks to be trained:

1.) The Generator Network -> This network is used for generating images or music or any other kinds of data. You can have a look at the reverse_mnist notebook to understand the working of the generator network.

2.) The discriminator network -> This network is used as a classifier that tells whether the generator performed its work well or not, i.e. it is used for categorising the generated data into valid or invalid. (True or False)

There are 2 different loss functions for each of Generator and Discriminator.

This notebook doesn't show a GAN. But it is a different approach of an idea to create images, but I think this approach won't be valid for fake data generation where the data looks real and similar to our dataset. And this can be achieved through GANs.
