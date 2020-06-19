[![GitHub license](https://img.shields.io/github/license/theairbend3r/how-to-train-your-neural-net)](https://github.com/theairbend3r/how-to-train-your-neural-net/blob/master/LICENSE) [![GitHub stars](https://img.shields.io/github/stars/theairbend3r/how-to-train-your-neural-net)](https://github.com/theairbend3r/how-to-train-your-neural-net/stargazers) [![GitHub forks](https://img.shields.io/github/forks/theairbend3r/how-to-train-your-neural-net)](https://github.com/theairbend3r/how-to-train-your-neural-net/network) [![GitHub issues](https://img.shields.io/github/issues/theairbend3r/how-to-train-your-neural-net)](https://github.com/theairbend3r/how-to-train-your-neural-net/issues)

![How to train your neural net poster](https://github.com/theairbend3r/how-to-train-your-neural-net/blob/master/assets/how-to-train-your-neural-net.jpg)

# How To Train Your Neural Net

This repo contains notebooks on training deep learning models for various tasks in the domains of `Computer Vision`, `Natural Language Processing`, and `Time Series Forecasting` using CUDA enabled `PyTorch 1.0+`.

## Table of Contents

### PyTorch

- #### Basics

  - Self-Attention in Computer Vision.
  - Convolutional Neural Networks.
  - Data Loaders and Loss Functions.
  - Recurrent Neural Networks.
  - PyTorch Samplers.
  - Tensors and Autograd.

* #### Computer Vision
  - Classification
    - MNIST using custom CNN.
    - Binary image classification using Hotdog-NotHotdog dataset.
  - Network Pruning
    - CNN filter pruning using MNIST dataset. [NIPS 2015]
  - Domain Adaptation
    - Unsupervised domain adaptation by backpropagation. [ICML 2015]
  - Attention
    - Non-local Neural Networks. [CVPR 2018]

- #### Natural Language Processing

  - Word Vectors [GLoVe].
  - Understanding Padding and Packing for RNNs.
  - Named Entity Recognition using RNNs (Conll database).
  - Text Classification
    - Binary text classification (Yelp Reviews).
      - RNN
      - CNN
      - RNN+CNN
    - Multi-class text classification (BBC news categorization).
      - RNN
      - CNN
      - RNN+CNN

- #### Tabular
  - Classification
    - Multiclass classification using DNN.
    - Binary classification using DNN.
  - Regression
    - Multiple Regression using DNN.
  - Time Series
    - Univariate Forecasting - Single Step - RNN.
    - Univariate Forecasting - Multi Step - RNN.

## Blog Post

You can find the related blog-posts [here](https://medium.com/tag/akshaj-wields-pytorch).
