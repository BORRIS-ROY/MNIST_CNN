## MNIST_CNN
# Fully connected Neural Network and Convolutinal Net
The aim of the project is to develop a neural network classifier (or regressor), involving setting up a model, optimising the amount of regularisation, investigating its performance, and devising a new model.

The model has been developed complex enough to *overfit* the training data: that is the loss/error-rate on the training set should be below your target loss/error-rate, and the loss/error-rate on the validation set should be higher than this (preferably higher than your target error-rate).

L2 regularisation has been implemented to train the initial model with different amounts of regularisation.
A small amount of regularisation may improve the validation set performance of the overfitted model; too much regularisation may make performance on the validation set worse.
The model is trained multiple times, applying different amounts of regularisation, and a graph showing the effect of different amounts of regularisation.

The model is trained with the choosen amount of regularisation on different amounts of training data. In addition, a plot that represents the performance (loss/error-rate) of the model on the validation set against the size of the training set on a log-log plot.

The second part sees the introduction of what is believed to be a better neural network architecture for the problem (i.e., a convolutional net).
Repeat regularisation experiment, and determine whether it has better validation set performance than the first model, for an intermediate size of training set (e.g. 2000 or 4000 for the MNIST data).
Repeat learning curve experiemnt. Confirm if the model have a different learning curve from the first. Plot of the learning curves for the first and second model on the same graph to compare them. 

The plots represent the loss and error rate as a function of training epochs.
