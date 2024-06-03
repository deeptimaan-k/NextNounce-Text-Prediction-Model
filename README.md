# NextNounce-Text-Prediction-Model

## Introduction
NextNounce-Text-Prediction-Model is a text prediction model built using TensorFlow and Keras. This model leverages an LSTM (Long Short-Term Memory) network to predict the next word in a given sequence of text. The model is trained on a text corpus to learn the patterns and structure of the language, enabling it to make accurate predictions.

## Features
- Tokenizes the input text and creates n-gram sequences.
- Pads sequences to ensure uniform length.
- Uses an Embedding layer followed by an LSTM layer for prediction.
- Predicts the next word in a sequence.

## Requirements
- Python 3.6+
- TensorFlow 2.x
- NumPy
- Keras (included with TensorFlow 2.x)
- Jupyter Notebook (optional, for running the code in a notebook environment)

## Installation
To install the required packages, use pip:
```bash
pip install tensorflow numpy
