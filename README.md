# Twitter-Sentiment-Analysis

This repository contains code for performing sentiment analysis on Twitter data. The code is implemented in a Jupyter Notebook and uses various libraries and techniques to analyze sentiment in tweets.

## Prerequisites

Before running the code, you need to install the following Python packages:

- gensim
- keras
- pandas

You can install these packages using pip:

```bash
pip install gensim
pip install keras
pip install pandas

```

Code Overview
Here's an overview of the code and its functionality:

Data Preparation:
The code starts by importing the necessary libraries and setting up the environment.
It defines the dataset columns and encoding, as well as the size of the training data.
Text cleaning is performed using regular expressions to remove special characters, links, and user mentions from the tweets.

Word2Vec Model:
It uses the Word2Vec model from the gensim library to create word embeddings for the text data.
The model is trained on the preprocessed text.

Tokenization:
The code tokenizes the text data and prepares it for model training.

Data Splitting:
The dataset is split into training and testing sets.

Model Creation:
A neural network model is defined using Keras, which includes an embedding layer and LSTM layer for sentiment analysis.

Model Training:
The model is trained on the training data and its performance is evaluated.

Visualization:
Training and validation accuracy and loss are visualized using matplotlib.

Sentiment Prediction:
The code provides a function for predicting sentiment on new text data.

Model Export:
The trained model, Word2Vec model, tokenizer, and encoder are saved to files.

Usage
You can run the code in a Jupyter Notebook environment. To use the sentiment analysis model for predictions, you can load the exported model files and use the provided predict function. 











