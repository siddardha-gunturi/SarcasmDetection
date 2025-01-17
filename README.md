# Sarcasm Detection Using Random Forest Classifier

This repository contains a machine learning project aimed at detecting sarcasm in text using the **Random Forest classifier**. The model is trained on a dataset of sarcastic and non-sarcastic sentences and classifies text into these two categories: sarcastic or non-sarcastic.

## Overview

Sarcasm detection is an important subfield of Natural Language Processing (NLP) due to its reliance on context and tone, which can be challenging to capture in text alone. This project uses **Random Forest**, a powerful ensemble learning method, to classify sarcastic vs. non-sarcastic text based on linguistic features like n-grams, word frequencies, and other textual representations.

## Getting Started

Follow these steps to set up and run the project locally.

### Clone the repository
```bash
git clone https://github.com/siddardha-gunturi/SarcasmDetection.git

Update path in Sarcasm_detector.ipynb file.
```

## Requirements
The project requires the following libraries:

  1. Python 3.x
  2. scikit-learn
 3. pandas
 4. numpy
 5. nltk

## Model Training

1. Data Preprocessing:
The raw text data is preprocessed by:
  Tokenization,
  Lowercasing,
  Removing stop words,
  Lemmatization
2. Model:
A Random Forest classifier is used to train the model. Random Forest is an ensemble method that builds multiple decision trees and aggregates their predictions to improve classification accuracy.
## Evaluation:
The model is evaluated using accuracy, precision, recall, and F1-score on a separate test dataset.
Accuracy: 65%
