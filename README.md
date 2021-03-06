# CS680 - Introduction to Machine Learning (U of waterloo course)

The course introduces the basics of machine learning and data analysis by helping us learn how to formalize a task as a machine learning problem, identify suitable algorithms to tackle different machine learning problems and apply different machine learning algorithms to datasets.

Various assignments were done such as:

  Assignment 1: Implementing k-nearest neighbours and linear regression using 10 fold cross validation and testing the implementations on some small datasets.

  Assignment 2: Implementing logistic regression using 10 fold cross validation and testing the implementations on some small datasets.

  Assignemnt 3: Implementing generalized linear regression and Gaussian process regression using 10 fold cross validation and testing the implementations on some small datasets.

  Assignment 4: Experimenting with fully connected neural networks and convolutional neural networks, using the Keras open source package. Comparing the accuracy of the convolutional neural network on the cifar10 dataset to the accuracy of simple dense neural networks with 0, 1, 2, 3 and 4 hidden layers of 512 rectified linear units each, using three different optimizers: RMSprop, Adagrad and Adam and by replacing each stack of (CONV2D, Activation, CONV2D, Activation) layers with 3x3 filters by a smaller stack of (CONV2D, Activation) layers with 5x5 filters.

  Assignment 5: Experimenting with various types of recurrent neural networks (RNNs) in PyTorch. Comparing the accuracy of the encoder implementation when varying the type of hidden units: linear units, gated recurrent units (GRUs) and long short term memory (LSTM) units. Comparing the accuracy of the decoder implementation when varying the information fed as input to the hidden units at each time step: i) previous hidden unit, previous character and category; ii) previous hidden unit and previous character; iii) previous hidden unit and category; iv) previous hidden unit. Comparing the accuracy of the seq2seq model with and without attention.

  Assignment 6: Implementing a variational auto-encoder (VAE) and a generative adversarial network (GAN) in PyTorch to generate images similar to those in the MNIST dataset. 
