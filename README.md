# Kolmogorov-Arnold Neural Networks (KAN)

This repository contains an implementation of Kolmogorov-Arnold Neural Networks (KAN) using PyTorch. The project demonstrates the application of KAN in classifying handwritten digits from the MNIST dataset.

## Table of Contents
- [Kolmogorov-Arnold Neural Networks (KAN)](#kolmogorov-arnold-neural-networks-kan)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Model Architecture](#model-architecture)
  - [Training and Evaluation](#training-and-evaluation)
  - [Results](#results)

## Introduction
Kolmogorov-Arnold Neural Networks (KAN) provide an alternative approach to traditional multi-layer perceptrons (MLPs) by leveraging the Kolmogorov-Arnold representation theorem. This project implements KAN and evaluates its performance on the MNIST dataset.

## Installation
To get started, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/kan.git
cd kan
pip install -r requirements.txt
```
## Usage

You can run the provided Jupyter notebook to train and evaluate the Kolmogorov-Arnold Neural Network on the MNIST dataset.

1. Open the notebook `kan.ipynb` in Jupyter.
2. Execute the cells sequentially to train the model and evaluate its performance.

## Model Architecture

The Kolmogorov-Arnold Neural Network (KAN) consists of multiple layers, each transforming input dimensions using linear layers and activation functions. The architecture is defined in the `KolmogorovArnoldNN` class in the notebook.

## Training and Evaluation

The notebook covers the following steps:

1. **Data Preparation:** Loading and normalizing the MNIST dataset.
2. **Model Definition:** Creating an instance of the `KolmogorovArnoldNN` class.
3. **Training:** Training the model using the Adam optimizer and cross-entropy loss.
4. **Evaluation:** Calculating accuracy and visualizing results with a confusion matrix.

## Results

The trained model's performance is evaluated on the test dataset, with results visualized using a confusion matrix. The confusion matrix provides insights into the model's accuracy across different classes.
