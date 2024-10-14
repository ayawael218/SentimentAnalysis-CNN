# SentimentAnalysis-CNN
1) Description:
   This project implements a sentiment analysis model on a dataset containing 1,600,000 tweets using Convolutional Neural Networks (CNN) to classify sentiments as positive or negative.

2) Key Features:
  Data Preprocessing: Lowercased text, removed URLs and special characters, tokenized words, filtered out stopwords, and applied lemmatization.
  Embedding: Trained a Word2Vec model with 100-dimensional embeddings.
  CNN Model:
  Architecture: 3 convolutional layers with batch normalization and dropout.
  Training: 20 epochs, batch size of 128.
  Performance: Achieved 79.57% test accuracy and a validation loss of 0.4358.
  Sample Prediction: Predicted sentiment for 10 random tweets from the test set.

3) Programming Tools:
   Python, TensorFlow/Keras, NLTK, Gensim
