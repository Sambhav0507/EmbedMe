# Skip-gram Word Embeddings in PyTorch

## Overview

This project implements the Skip-gram word embedding model using PyTorch. The Skip-gram model is used to represent words in a vector form, making them suitable for natural language processing tasks. This README provides an overview of the project, its components, and how to use it.

## Table of Contents

- [Installation](#installation)
- [Skip Gram model](##Skipgrammodel)
- [Word Context](#preprocessing)
- [Word Vector Initialization](#word)
- [Training](#training)
- [Word Embeddings](#visualizing-word-embeddings)
- [Single Value Decomposition](#svd)


## Installation

To use this project, you need to have Python and PyTorch installed on your system. You can install PyTorch by following the instructions on the [official PyTorch website](https://pytorch.org/).

## Skip gram model

The skip-gram model is a popular neural network-based technique used in natural language processing (NLP) and word embedding tasks. It is a part of the word2vec family of algorithms developed by Tomas Mikolov and his team at Google. The skip-gram model is specifically designed to learn word embeddings, which are vector representations of words that capture semantic and syntactic relationships between words in a text corpus


## Word Context
The central idea of the skip-gram model is to predict the context words (words that appear nearby) for a given target word within a specific window of text. The model takes a large corpus of text as input.

## Word Vector Initialization
Each word in the vocabulary is initialized with a unique vector representation. These vectors are typically initialized randomly or with small random values. I have used one-hot encoding vectors for initialization

## Training
The skip-gram model is trained using a neural network. Given a target word, the model tries to maximize the probability of the surrounding context words appearing within a certain window. This is done using techniques like stochastic gradient descent.

## Single Value Decomposition
Single Value Decomposition (SVD) is a fundamental mathematical technique used in linear algebra and data analysis. It is a way to factorize a matrix into three other matrices, providing insights into the structure and properties of the original matrix. SVD has applications in various fields, including data compression, dimensionality reduction, recommendation systems, and image processing.
