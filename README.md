# SentimentScope: Sentiment Analysis with Transformers

Project from **AWS AI & ML Scholars Certificate** - Transformers-based sentiment analysis on the IMDB movie reviews dataset.

## Date
Completed: 2023

## Overview
Train a transformer model from scratch for binary sentiment classification (positive/negative) on the IMDB dataset. Uses PyTorch and Hugging Face 	ransformers library.

## Dataset
IMDB Large Movie Review Dataset (aclIMDB v1):
- 25,000 training reviews (pos/neg)
- 25,000 test reviews (pos/neg)
- Download: [IMDB Dataset](https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz)
- Or use Hugging Face datasets library: load_dataset('imdb') (recommended)

## Files
- SentimentScope_starter.ipynb - Main notebook (exercise version)

## Requirements
`ash
pip install torch transformers datasets accelerate evaluate
` 

## How to Run
1. Open SentimentScope_starter.ipynb in Jupyter
2. The notebook downloads the IMDB dataset automatically via datasets.load_dataset('imdb')`r
3. Run all cells to train and evaluate the transformer model

