# Next Word Prediction using LSTM

## Overview
This project implements a next-word prediction model using a Long Short-Term Memory (LSTM) neural network. The model is trained on text data to predict the next word in a given sequence, enhancing applications like autocomplete and text generation.

## Features
- Uses LSTM-based deep learning model for next-word prediction
- Trained on a text dataset for language modeling
- Implements data preprocessing including tokenization and padding
- Supports real-time text input for prediction

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/hassan1324sa/Next-word-prediction-using-LSTM.git
   cd Next-word-prediction-using-LSTM
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Prepare your dataset (if using a custom one) and preprocess it.
2. Train the model:
   ```bash
   python train.py
   ```
3. Run the prediction script:
   ```bash
   python predict.py "your input text here"
   ```

## Dataset
The model is trained on a text dataset. You can replace it with your own dataset in the preprocessing pipeline.

## Model Architecture
- Embedding Layer
- LSTM Layers
- Dense Layer with Softmax Activation


