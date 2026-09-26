# ANN-Date-Fruit-Classification

An Artificial Neural Network (ANN) based classification project for classifying different varieties of Date Fruits using PyTorch.

## Project Overview

This project uses a neural network to classify Date Fruits into 7 different classes based on their numerical features.

The project covers the complete machine learning workflow:

- Data loading and preprocessing
- Train-test split
- Feature scaling
- Label encoding
- PyTorch tensor conversion
- DataLoader creation
- ANN model building
- Model training
- Model evaluation
- Accuracy calculation

## Dataset

The dataset contains 898 samples and 34 numerical features.

The target variable is `Class`, which contains 7 Date Fruit varieties:

- BERHI
- DEGLET
- DOKOL
- IRAQI
- ROTANA
- SAFAVI
- SOGAY

## Model Architecture

The ANN consists of the following layers:

```text
Input Features (34)
        ↓
Linear Layer (34 → 64)
        ↓
ReLU
        ↓
Linear Layer (64 → 64)
        ↓
ReLU
        ↓
Linear Layer (64 → 7)
        ↓
Output Classes
