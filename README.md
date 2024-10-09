# NCIFAR10

A PyTorch implementation of the Natural CIFAR-10 (NCIFAR10) dataset and a collection of deep learning models and utilities for image classification tasks. This repository provides an easy-to-use framework for training and evaluating models on the CIFAR-10 dataset with added augmentations or modifications specific to NCIFAR10.

## Introduction

NCIFAR10 is an extension or customized version of the well-known [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html), featuring 60,000 32x32 color images in 10 different classes. This project introduces:

- Additional data preprocessing steps such as augmentations (if applicable).
- Pre-trained models.
- Benchmarking on popular deep learning architectures.
- Support for custom training loops and evaluation metrics.

## Features

- **Customizable dataset augmentations**: Easily apply standard or custom transformations.
- **Pre-built models**: Use state-of-the-art architectures such as ResNet, VGG, and more.
- **Efficient training**: Support for multi-GPU training and mixed precision.
- **Comprehensive logging**: Use TensorBoard and other utilities for tracking experiments.
- **Easy extensibility**: Easily add new datasets, models, or loss functions.
  
## Installation

To install the dependencies and clone this repository, follow these steps:

```bash
# Clone the repository
git clone https://github.com/elhariri78/ncifar10.git
cd ncifar10

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows, use venv\​⬤
