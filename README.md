# Skip-gram Word Embeddings in PyTorch

## Overview

This project implements the Skip-gram word embedding model using PyTorch. The Skip-gram model is used to represent words in a vector form, making them suitable for natural language processing tasks. This README provides an overview of the project, its components, and how to use it.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Preprocessing](#preprocessing)
- [Training](#training)
- [Visualizing Word Embeddings](#visualizing-word-embeddings)


## Installation

To use this project, you need to have Python and PyTorch installed on your system. You can install PyTorch by following the instructions on the [official PyTorch website](https://pytorch.org/).

Clone this repository to your local machine:

``` bash
   git clone https://github.com/yourusername/skip-gram-pytorch.git
```

## Usage

## Preprocessing

Before training the Skip-gram model, you'll need to preprocess your text data. The preprocessing steps include tokenization, stop-word removal, and word stemming. Modify the preprocess function in the code to preprocess your corpus of text.

## Training
Set the hyperparameters such as num_epochs and learning_rate before training the Skip-gram model. You can also adjust the embed_dims to control the dimensionality of word embeddings.

## Visualizing Word Embeddings
After training, you can visualize word embeddings using techniques like Singular Value Decomposition (SVD) and cosine similarity. Use the get_embeddings function to obtain word embeddings and calculate cosine similarity between words.
