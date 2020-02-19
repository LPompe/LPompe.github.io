---
title: 'GridTorch released'
date: 2020-02-11
permalink: /posts/gridtorch/
tags:
  - code
  - grid-cells
  - machine-learning
---

# GridTorch [code here](https://github.com/LPompe/gridtorch)
## Pytorch neural network model with grid-like activations is now open source
Back in 2018, Banino <em>et al</em> released their paper <em>vector-based navigation using grid-like representations in artificial agents</em> in Nature. This is one of the first instances of artificial neural networks reproducing single neuron-like statistics through training by SGD only (see also: Cueva & Wei, 2018). The authors released the code of this paper in Tensorflow [here](https://github.com/deepmind/grid-cells). 

With the growing popularity of PyTorch, and the time crunch of my Msc., I decided to reimplement the model in PyTorch. This makes is extremely easy to instantiate different versions of the model for rapid experimentation. For even more ease-of-use I have included the weights of the trained (in Tensorflow) model, so no need to spend hours training anymore. The code of the model, training routine and evaluation can be found [here](https://github.com/LPompe/gridtorch). 

Feel free to open a PR, or DM me (@LucasPompe) with your project (idea)
-L
