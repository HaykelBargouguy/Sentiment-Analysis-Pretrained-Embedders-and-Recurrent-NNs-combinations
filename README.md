# Sentiment Analysis on IMDB Movie Reviews

## Project Overview
This repository contains our work on sentiment analysis of movie reviews from the IMDB dataset. We focused on evaluating the performance of three different recurrent neural network architectures: LSTM (Long Short-Term Memory), GRU (Gated Recurrent Units), and CRNN (Convolutional Recurrent Neural Network). Each architecture was tested with three popular embedding techniques: GloVe, Word2Vec, and FastText.

## Objective
The main objective of this project was to determine the most effective combination of RNN architecture and word embeddings for classifying sentiments expressed in movie reviews as either positive or negative.

## Dataset
The dataset used is the IMDB dataset, which contains movie reviews labeled for sentiment (positive/negative).

## Models and Technologies
- **Recurrent Neural Networks (RNNs)**: LSTM, GRU, CRNN
- **Embeddings**: GloVe, Word2Vec, FastText
- **Framework**: TensorFlow

## Results
![RNN](https://github.com/HaykelBargouguy/Sentiment-Analysis-Pretrained-Embedders-and-Recurrent-NNs-combinations/assets/98351985/691ea48e-b811-4cb4-90d2-8a67cd0a7cb2)
Our experiments led to the best performance with the combination of LSTM and FastText embeddings, achieving an accuracy of 0.87.
