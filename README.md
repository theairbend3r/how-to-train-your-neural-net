[![GitHub license](https://img.shields.io/github/license/theairbend3r/how-to-train-your-neural-net)](https://github.com/theairbend3r/how-to-train-your-neural-net/blob/master/LICENSE) [![GitHub stars](https://img.shields.io/github/stars/theairbend3r/how-to-train-your-neural-net)](https://github.com/theairbend3r/how-to-train-your-neural-net/stargazers) [![GitHub forks](https://img.shields.io/github/forks/theairbend3r/how-to-train-your-neural-net)](https://github.com/theairbend3r/how-to-train-your-neural-net/network) [![GitHub issues](https://img.shields.io/github/issues/theairbend3r/how-to-train-your-neural-net)](https://github.com/theairbend3r/how-to-train-your-neural-net/issues)

![How to train your neural net poster](https://github.com/theairbend3r/how-to-train-your-neural-net/blob/master/assets/how-to-train-your-neural-net.jpg)


# How To Train Your Neural Net 


This repo contains notebooks on training deep learning models for various tasks in the domains of Natural Language Processing, Computer Vision, Time Series Forecasting using CUDA enabled PyTorch 1.0+. 


## Table of Contents: 

### PyTorch
1. Basics
    * Convolution Neural Networks. 
    * Recurrent Neural Networks.
    * Tensors and Autograd.
    * Exploring dataloaders and loss functions.
    * Sampling Samplers.


2. NLP
    * Word Vectors [GLoVe].
    * Understanding Padding and Packing for RNNs.
    * Named Entity Recognition using RNNs (Conll database).
    * Text Classification
        * Binary text classification (Yelp Reviews).
            * RNN
            * CNN
            * RNN+CNN
        * Multi-class text classification (BBC news categorization).
            * RNN
            * CNN
            * RNN+CNN

3. Computer Vision
    * Classification
        * MNIST using custom CNN.
        * Binary image classification using Hotdog-NotHotdog dataset.
    * Network Pruning
        * DNN weight pruning using Iris dataset.
        * CNN filter pruning using MNIST dataset.
    * Domain Adaptation
        * Unsupervised domain adaptation by backpropagation.




4. Tabular
    * Classification
        * Multiclass classification using feedforward neural networks.
        * Binary classification using feedforward neural networks.
    * Regression
        * Multiple Regression using feedforward neural networks.
    * Time Series
        * Univariate Forecasting - Single Step - RNN.
        * Univariate Forecasting - Multi Step - RNN.		
