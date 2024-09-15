# Sentiment Analysis Report 
## Overview 
This project evaluates three sentiment analysis models: Twitter RoBERTa Base, DistilBERT-base-uncased emotion, and BERT-base-multilingual-uncased-sentiment. The goal is to compare their performance on English and French datasets from social media posts, product reviews, and movie reviews.

## Models
- Twitter RoBERTa Base: Optimized for social media text.
- DistilBERT-base-uncased emotion: Efficient model fine-tuned for emotion classification.
- BERT-base-multilingual-uncased-sentiment: Multilingual model for sentiment analysis across multiple languages.

## Methodology
- Datasets: 1600 sentences per sentiment label (positive, neutral, negative), shuffled to prevent bias. For each experiment, 100 random samples were used.
- Languages: English and French datasets were used. Twitter RoBERTa and DistilBERT were tested on English, while BERT Multilingual was tested on both English and French.
  
## Experimentation
Models were tested on diverse datasets without retraining, evaluating their performance and suitability for various tasks.
Five experiments were conducted on each model:

- English Datasets: Three experiments
- French Datasets: Two experiments

## Results
- Accuracy: Plotted as bar graphs representing overall accuracy for each model.
- Confusion Matrices: Generated for each model, displaying true positives, false positives, true negatives, false negatives, true neutrals, and false neutrals.

## Hardware & Software
- Hardware: Google Colab (Intel Xeon CPUs, NVIDIA Tesla K80 GPU, 12.72 GB RAM)
- Software: Python 3.8.5, Google Colab, Libraries: PyTorch, Transformers, NumPy


