# Machine Learning Nanodegree
# Capstone Project
## Project: Cervantes 2.0

In this project we will focus on Text Generation. Text Generation is part of [Natural Language Processing](https://en.wikipedia.org/wiki/Natural_language_processing) and can be used to [transcribe speech to text](http://www.jmlr.org/proceedings/papers/v32/graves14.pdf), perform [machine translation](http://arxiv.org/abs/1409.3215), generate handwritten text, image captioning, generate new blog posts or news headlines. 

RNNs are [very effective](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) when understanding sequence of elements and have been used in the past to generate text. I will use a Recurrent Neural Network to generate text inspired on the works of Cervantes.

![Basic RNN -> Unrolled RNN](images/basic_unrolled_RNN.png)

In order to generate text, we will look at a class of Neural Network where connections between units form a directed cycle, called Recurrent Neural Network (RNNs). RNNs use an internal memory to process sequences of elements and is able to learn from the syntactic structure of text. Our model will be able to generate text based on the text we train it with.

### Install

Highly recommend installing [Anaconda](https://www.continuum.io/downloads). Anaconda conveniently installs Python, the Jupyter Notebook, and other commonly used packages for scientific computing and data science.

This project has the following dependencies:
- Python 3.6
- Jupyter Notebook
- Numpy
- Tensorflow 1.0

### Run 

Execute the [Jupyter](http://jupyter.org/install.html) notebook - mlnd-cervantes.ipynb