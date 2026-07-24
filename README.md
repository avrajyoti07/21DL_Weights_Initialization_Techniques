# Weight Initialization Techniques Neural Networks Demo

A beginner-friendly deep learning project demonstrating the critical role of weight initialization in training neural networks. This repository serves as a starter-phase template for understanding what happens to a model's learning capabilities when weights are initialized incorrectly.

## Overview
This repository explores binary classification on a 2D dataset[cite: 2, 3]. It practically highlights the "symmetry breaking" problem and how improper weight initialization can prevent a model from effectively separating classes[cite: 2, 3].

## Features
* **Model Architecture**: Utilizes Keras `Sequential` models built with `Dense` layers[cite: 2, 3].
* **Activation Functions**: Includes experiments using both `relu`[cite: 2] and `sigmoid`[cite: 3] activation functions.
* **Initialization Experiments**:
    * Demonstrates a training scenario where model weights are intentionally initialized to a constant value of 0.5[cite: 2].
    * Shows the effects of zero initialization by setting all network weights to 0.0 before compiling the model[cite: 3].
* **Visualization**: Plots training loss and accuracy against validation metrics, and generates contour plots to visualize the model's resulting decision boundaries[cite: 2, 3].

## Dataset
The model is trained on a 2D U-shaped dataset containing `X` and `Y` coordinates alongside a binary `class` label[cite: 2, 3]. To replicate the experiments or test the data loading, you can reference the dataset using the file named ushape.xls.

## Prerequisites
Ensure you have the following libraries installed:
* `numpy`[cite: 2, 3]
* `pandas`[cite: 2, 3]
* `matplotlib`[cite: 2, 3]
* `tensorflow` / `keras`[cite: 2, 3]

## Author
**Avrajyoti Kundu**
