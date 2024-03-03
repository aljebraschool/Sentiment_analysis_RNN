# Sentiment Analysis with an RNN

This repository contains the implementation of a recurrent neural network (RNN) for sentiment analysis. The RNN is designed to process sequences of words, making it well-suited for understanding the context in which each word appears.

## Objective

The primary goal of this project is to accurately determine whether a given text is expressing a positive or negative sentiment. By training the RNN on a dataset of movie reviews and their corresponding sentiment labels, we aim to develop a model that can make informed predictions on the sentiment of unseen reviews.

## Project Structure

1. **Data Preprocessing**: The dataset of movie reviews is preprocessed to remove any unnecessary information and convert the text into a suitable format for the RNN.
2. **Embedding Layer**: An embedding layer is used to efficiently represent words as vectors, which can then be passed into the RNN.
3. **LSTM Layer**: Long Short-Term Memory (LSTM) cells are employed to provide the RNN with the ability to understand and remember sequential information.
4. **Output Layer**: The LSTM outputs are mapped to a sigmoid output layer, which predicts sentiment values between 0 (negative) and 1 (positive).

## Dataset

The movie reviews dataset used in this project consists of a collection of movie reviews along with their corresponding sentiment labels. Each review is labeled as either 'positive' or 'negative', and the goal is to train the RNN to accurately predict these labels.

## Setup Instructions

To run this code locally, you will need:

- Python (>=3.6)
- PyTorch (>=1.7.0)
- Jupyter Notebook

After installing the required libraries, simply clone this repository and execute the `Sentiment Analysis with an RNN.ipynb` notebook.

```shell
git clone https://github.com/yourusername/sentiment-analysis-rnn.git
cd sentiment-analysis-rnn
jupyter notebook Sentiment\ Analysis\ with\ an\ RNN.ipynb
