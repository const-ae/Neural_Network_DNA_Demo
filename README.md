# Neural Network for Sequence Data

This project is an example how the recent advancements in Neural Networks
can be applied to sequence data, namely DNA.

We will take a collection of sequences plus information if they are 
bound by a transcription factor as input data and after training
a convolutional neural network we will be able to make predictions 
for new sequences. In addition we will extract what the network learned
and make a plot of the motif.

# Preparation

To make sure everybody can play around with the example easily and you do not need to install the dependencies, please follow the instructions below.

The code for this tutorial is written in Python, please make sure you have a recent installation (https://www.python.org/downloads/).

Neural Networks are a complex topic and there are quite a few packages you need to install to get going. The easiest way to install packages in Python is to use [Anaconda](https://www.continuum.io/downloads). In the following I will assume that you have Python and Anaconda installed.

## Libraries

To run the the code in the tutorial you will need the following libraries:

* Jupyter / IPython
* Keras
* Theano
* Numpy

All of them can be installed with the following commands:

```Shell
$ conda install ...
```
