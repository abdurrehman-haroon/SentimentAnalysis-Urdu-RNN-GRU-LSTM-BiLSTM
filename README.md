# Urdu Sentiment Analysis with Deep Learning Models

This repository contains implementations of various sequence-based deep learning models for sentiment analysis in Urdu language. The dataset used for this task is the Urdu Sentiment Corpus, which consists of labeled data with class labels P (Positive) and N (Negative).

## Dataset
The dataset can be accessed from the following link:
[Urdu Sentiment Corpus](https://github.com/MuhammadYaseenKhan/Urdu-Sentiment-Corpus/blob/master/urdu-sentiment-corpus-v1.tsv)

## Models Implemented
The following sequence-based deep learning models have been implemented for sentiment analysis:
1. Recurrent Neural Network (RNN)
2. Gated Recurrent Unit (GRU)
3. Long Short-Term Memory (LSTM)
4. Bidirectional LSTM (BiLSTM)

## Implementation Details
- **Splitting Data**: The data is split into train and test sets with a ratio of 75% for training and 25% for testing.
- **Hyperparameters**: The following hyperparameters are experimented with for each model:
  - Number of layers: 2 or 3
  - Dropout rate: 0.3 or 0.7

## Results
For each model, the accuracy, precision, recall, and F-score are calculated for all combinations of hyperparameters. The best results along with the corresponding parameter values are reported in a table.

