# Neural Network for Sequence Data

This project is an example how the recent advancements in Neural Networks
can be applied to sequence data, namely DNA.

We will take a collection of sequences plus information if they are 
bound by a transcription factor as input data and after training
a convolutional neural network we will be able to make predictions 
for new sequences. In addition we will extract what the network learned
and make a plot of the motif.

The example are chosen such that it is not necessary to have a GPU and should learn just fine on CPU.

# Preparation

To make sure everybody can play around with the example easily and you do not need to install the dependencies, please follow the instructions below.

The code for this tutorial is written in Python and you will need a 2.7 or 3.5 installation (https://www.python.org/downloads/). If you have 

Neural Networks are a complex topic and there are quite a few packages you need to install to get going. The easiest way to install packages in Python is to use [Anaconda](https://www.continuum.io/downloads). In the following I will assume that you only have Anaconda installed.

## Libraries

To run the the code in the tutorial you will need the following libraries:

* Jupyter / IPython
* Keras
* Theano _or_ Tensorflow
* Numpy

## Installation Steps 

After the successful installation of Anaconda we will create a new conda environment to not pollute the default environment:

```Shell
$ conda create -n seqnn python=3.5 
$ activate seqnn
```

Download the `Neural_Network_DNA_Demo` either by cloning it with git

```Shell
$ git clone https://github.com/Artjom-Metro/Neural_Network_DNA_Demo.git
```

__OR__ download this [zip file](https://github.com/Artjom-Metro/Neural_Network_DNA_Demo/archive/master.zip) and extracting it somewhere.

Install Theano 

```Shell
$ conda install theano pygpu
```

If you have problems with the installation check with ...

* Theano --> check [this](http://deeplearning.net/software/theano/install.html#install) guide
* Keras --> check [this](https://keras.io/#installation) guide

or just open issue [here](https://github.com/Artjom-Metro/Neural_Network_DNA_Demo/issues).

Move with the command line to the `Neural_Network_DNA_Demo` folder:

```Shell
$ cd <LOCATION_OF_DOWNLOAD>/Neural_Network_DNA_Demo
```










