# Exploring-1D-CNN-and-Transformer-Architectures-for-Multi-Class-Classification

## Introduction
This repository contains code for exploring and comparing two different architectures for multi-class classification tasks: one utilizing a traditional 1D convolutional neural network (CNN) with fully connected layers, and the other integrating a transformer encoder network with a multi-head self-attention mechanism on top of the CNN base. Both architectures are implemented using PyTorch and evaluated on a 10-class classification problem.

## Architectures
### Architecture 1:
- **Base Network:** 1D Convolutional layers for feature extraction, followed by fully connected layers for classification.

### Architecture 2:
- **Base Network:** Similar to Architecture 1, with the addition of a transformer encoder network on top, incorporating a multi-head self-attention mechanism.

## Tasks and Evaluation
1. **Training and Evaluation:** Train both architectures for 100 epochs and plot accuracy and loss per epoch using Weight and Biases (WandB) platform.
2. **K-fold Cross Validation:** Perform k-fold validation with k=4 for robust evaluation.
3. **Performance Metrics:** Compute Accuracy, Confusion Matrix, F1-scores, and AUC-ROC curve for the test set for all combinations of networks.
4. **Parameter Analysis:** Report total trainable and non-trainable parameters for both architectures.
5. **Hyper-parameter Tuning:** Conduct hyper-parameter tuning and report the best hyper-parameter set for improved performance.

## Conclusion
Through rigorous experimentation and analysis, this project aims to determine which architecture performs better for the given multi-class classification task. The findings will provide insights into the effectiveness of transformer-based architectures compared to traditional CNNs in handling sequential data for classification purposes.

## How to Use
1. Clone this repository.
2. And run the code in IPYNB file by adjusting the path to data accordingly.


