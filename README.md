# Tangma

https://arxiv.org/abs/2507.10560

## Overview

This project implements Tangma --- an activation function combining tunable nonlinearity and residual linearity through the use of learnable parameters for deep learning models. Tested in custom CNNs with MNIST and CIFAR-10 datasets, it shows promising results in training performance by preventing issues like vanishing gradients, while softening high intensity activations. 

## Project Structure

```plaintext
Tangma/
├── cifar10_cnn.ipynb                   # Full implmentation (defining activation functions + custom CIFAR10 CNN)
├── mnist_cnn.ipynb                     # Same as above but for MNIST dataset
├── Tangma_ShreelGolwala.pdf            # A pdf copy of the paper
├── tangma_paper                        # Folder with all figures and main .tex file.  


