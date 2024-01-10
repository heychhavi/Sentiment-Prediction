# Sentiment-Prediction
 Architecture

<img src="https://github.com/udacity/deep-learning-v2-pytorch/blob/master/sentiment-rnn/assets/network_diagram.png?raw=true" width=40%>

This GitHub repository contains the implementation of a Recurrent Neural Network (RNN) for sentiment analysis. The model is trained to read text and predict the sentiment, whether positive or negative, based on movie reviews from IMDB.

# Description
The project utilizes an RNN due to its effectiveness in considering the sequence of words in the text, which is crucial for accurate sentiment analysis. The model is trained on a dataset containing around 130,000 movie reviews from IMDB, labeled as either "positive" or "negative".

 #Network Architecture
The RNN architecture includes:

An embedding layer for dimensionality reduction
LSTM cells for adding recurrent connections, capturing the sequence information in the movie review data
A sigmoid output layer that outputs sentiment values between 0 (negative) and 1 (positive)
# Dataset
The dataset comprises IMDB movie reviews, each labeled as positive or negative. For data preprocessing, the reviews are tokenized, with punctuation removed, and each word is encoded as an integer. The dataset is then split into training, validation, and test sets.

# Repository Contents
Python code for the RNN model
Data preprocessing scripts
Training and validation scripts
Model testing and inference scripts
# Requirements
Python 3.x
PyTorch
NumPy
# Usage
Clone the repository.
Install the required dependencies.
Run the preprocessing script to prepare the dataset.
Train the model using the training script.
Evaluate the model performance on the test set.
Use the inference script to make predictions on new data.
# Contributing
Contributions to improve the model or extend its functionality are welcome. Please feel free to fork the repository and submit a pull request with your changes.

# License
This project is licensed under the terms of the MIT license.


