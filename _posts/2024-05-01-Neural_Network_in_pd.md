---
title: Neural Network in pd
categories: [Patch, Neural_Networks]
tags: [data-flow, pd, GEM, visual, deep-learning]     # TAG names should always be lowercase
image: 
    path: /assets/pimg/1.png
---

# A Neural Network patch to approximate the sine curve 

![patch](/assets/pimg/1.png)f

## Description

This patch implements a feedforward neural network with two hidden layers, designed to approximate the sine wave function. The input layer allows you to set weights, biases, and input values through various numerical objects. The hidden layers consist of multiple "neuron" subpatches that perform weighted sums, add biases, and apply ReLU activations. The final output is obtained by summing the outputs of the two hidden layers, displaying the neural network's prediction. Additionally, the patch includes visualization components to plot the functions, providing a representation of the neural network's performance.

[view source code](/assets/ptxt/1.txt)

[download patch](/assets/ppd/1.pd)