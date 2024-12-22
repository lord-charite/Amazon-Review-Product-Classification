# Overview

This project aims to classify Amazon product reviews as high-star reviews (rating = 1) or low-star reviews (rating = 0). It is divided into two parts:
  1) Binary Classification with Machine Learning Models
  2) Classification with Large Language Models (LLMs)
     
# Part 1: Binary Classification with ML Models

Objective:  Train and evaluate machine learning models to classify reviews as high-star(1) or low-star (0).

# Key Steps

- Data Preprocessing:
    - Extract features using reviewText and optionally other columns.
    - Preprocess text (e.g., stop-word removal, tokenization).
  
- Feature Engineering: Use TF-IDF or other feature representations.
  
- Model Training:
    - Train at least three ML classifiers (e.g., Logistic Regression, Random Forest, SVM).
    - Perform hyperparameter tuning using 5-fold cross-validation.

- Evaluation:
    - Compare models using precision, recall, and macro F1-score.
    - Select the best model and generate predictions for the test set.


# Part 2: Classification with LLMs

# Objective
Evaluate an open-source large language model (LLM) for the classification task using prompting techniques.

# Key Steps

- Model Setup: Use mistralai/Mistral-7B-Instruct-v0.3 from Huggingface.
  
- Prompting Techniques: Experiment with zero-shot, one-shot, and few-shot prompting using examples from the training set.

- Evaluation: Report precision, recall, and macro F1-score for each prompting strategy.

- Perform error analysis on:
    - Prompt instructions.
    - Class definitions.
  
