# Headline Sarcasm Detection Model
## Overview
This project implements a Sarcasm Detection Model using a neural network with TensorFlow and Keras. The model is trained on headlines and classifies whether a given headline is sarcastic or not. The model achieves a validation accuracy of around 85-86% after fine-tuning.

The goal of this project is to explore natural language processing (NLP) techniques for sarcasm detection, which is a challenging and fun problem in text classification.

## Dataset
The dataset used is a collection of headlines labeled as sarcastic or not sarcastic. The data consists of:
- Headlines from news articles
- Labels indicating whether the headline is sarcastic (1) or not sarcastic (0)

[Download the dataset on Kaggle](https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection)

## Model Architecture
The model is built using TensorFlow/Keras and consist of:
- <b>Embedding layer</b>: Converts input text into word embeddings.
- <b>Global Average Pooling</b>: Reduces the dimensionality of the embedding vectors.
- <b>Dense layer</b>: Fully connected layer with 16 units and ReLU activation.
- <b>Dropout layer</b>: To prevent overfitting by randomly dropping neurons.
- <b>Output layer</b>: A single neuron with a sigmoid activation for binary classification.

## Evaluation
The model is evaluated on a test set, achieving around 85-86% validation accuracy. Metrics tracked during training include:
- Training Loss
- Validation Loss
- Training Accuracy
- Validation Accuracy
