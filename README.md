# Multi-Input-Model-with-Keras-Functional-API
To practise creating a multi input model, I'm going to create a siamese network, with a base model that takes the output from two of the same classifiers as its multiple inputs. If the euclidean distance between the output vectors for both Inputs is almost 0, both images will be said to be identical. 
Here we will be using the Fashion MNIST Dataset, but since a siamese network requires a pair of images, we will modify the dataset before training on it.
