---
layout: post
title: Building my first neural network from scratch
description: Building my first neural network from scratch
summary: Building my first neural network from scratch
tags: [python, machine learning]
---

In traditional programming, the computer is given an input and a model, and returns an output. Here's a simple example:

```python
#Input
x = 1

#Model
def add_five(x):
    return x + 5
```

In machine learning, however, the program is given an input and an expected output, and returns a model relating the two. This is accomplished through what is known as a neural network.

### What is a Neural Network?

A neural network is comprised of:
- An input layer, **x**
- An arbitrary amount of hidden layers
- An output layer, **ŷ**
- A set of weights, **W**, and biases, **B**, between each layer
- Activation functions for each node in the hidden layers

<figure>
	<img src="/assets/img/neural1.png" width="250">
	<figcaption>Neural Network.</figcaption>
</figure>

The goal of a neural network is to find the best possible set of weights and biases to minimize the cost function.

### Forward Propogation

### Backward Propogation