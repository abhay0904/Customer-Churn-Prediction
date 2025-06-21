# ANN Churn Classification

This repository contains an Artificial Neural Network (ANN) model for customer churn classification. The model is trained to predict whether a customer will churn based on various input features.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Customer churn prediction is a critical task for businesses aiming to retain customers. This project leverages an ANN to classify customers as likely to churn or remain.

## Dataset
The dataset used for training includes various features such as customer demographics, account information, and transaction history. It is preprocessed before being fed into the ANN model.

## Installation
To set up the project, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/Durvankur-Rasal/ANN-churn-classification.git
   cd ANN-churn-classification
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
Run the training script:
```sh
python train.py
```
To make predictions on new data:
```sh
python predict.py --input data/sample_input.csv
```

## Model Architecture
The ANN model consists of the following layers:
- Input layer with necessary features
- Fully connected hidden layers with activation functions (ReLU)
- Output layer with softmax activation for classification

## Evaluation
The model is evaluated using metrics such as:
- Accuracy
- Precision
- Recall
- F1-score

