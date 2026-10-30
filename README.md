# FashionMNIST Neural Network Analysis

## Overview

This project explores the behavior and performance of fully connected neural networks on the FashionMNIST dataset using PyTorch. The notebook focuses not only on classification accuracy but also on understanding how different activation functions influence weight distributions, gradient flow, and neuron activations throughout the network.

The project includes:

- FashionMNIST data preprocessing
- Neural network construction using PyTorch
- Multiple activation function experiments
- Weight distribution analysis
- Gradient distribution visualization
- Activation distribution inspection
- Model architecture experimentation
- Reproducibility through fixed random seeds

The primary objective is to investigate how activation functions impact neural network training dynamics and internal representations.

---

## Dataset

### FashionMNIST

FashionMNIST is a computer vision dataset consisting of grayscale clothing images.

Dataset characteristics:

| Property | Value |
|-----------|---------|
| Classes | 10 |
| Image Size | 28 × 28 |
| Channels | 1 |
| Training Images | 60,000 |
| Test Images | 10,000 |

### Classes

- T-shirt/Top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle Boot

---

## Project Structure

```text
.
├── fashionmnist_network_analysis.ipynb
├── pretrained_files/
│   ├── FashionMNIST_50.config
│   ├── FashionMNIST_50_results.json
│   ├── FashionMNIST_50.tar
│   ├── FashionMNIST_Adam.config
│   ├── FashionMNIST_Adam_results.json
│   └── FashionMNIST_Adam.tar
├── visualizations/
│   ├── weight_distribution.png
│   ├── gradient_distribution.png
│   ├── activation_distribution.png
│   └── training_metrics.png
└── README.md
