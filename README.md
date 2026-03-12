# CS4375 Sentiment Analysis

FFNN and RNN models for 5-class sentiment analysis on Yelp reviews.

## Requirements
pip install torch tqdm numpy

## Usage

**FFNN:**
python ffnn.py --hidden_dim 50 --epochs 5 --train_data training.json --val_data validation.json

**RNN:**
python rnn.py --hidden_dim 64 --epochs 10 --train_data training.json --val_data validation.json

## Files
- ffnn.py: Feedforward Neural Network
- rnn.py: Recurrent Neural Network
