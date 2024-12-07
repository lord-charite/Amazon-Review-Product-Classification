# Amazon Review Binary Classification Task

This repository contains the implementation of a binary classification task on Amazon product reviews. The task involves identifying whether a review is a high-star review (rating > 3) or a low-star review (rating ≤ 3). The project is divided into two parts:

# Part 1: Binary Classification with ML Models

# Objective

Train and evaluate machine learning models to classify reviews as high-star or low-star.

# Key Steps

# Data Preprocessing:

Extract features using reviewText and optionally other columns.
Preprocess text (e.g., stop-word removal, tokenization).

# Feature Engineering:

Use TF-IDF or other feature representations.

# Model Training:

Train at least three ML classifiers (e.g., Logistic Regression, Random Forest, SVM).
Perform hyperparameter tuning using 5-fold cross-validation.

# Evaluation:

Compare models using precision, recall, and macro F1-score.
Select the best model and generate predictions for the test set.

# Deliverables

Write-up: Describes feature engineering, model training, and evaluation.
Prediction File: .csv file with test set predictions


# Part 2: Classification with LLMs

# Objective

Evaluate an open-source large language model (LLM) for the classification task using prompting techniques.

# Key Steps

- Model Setup:

Use mistralai/Mistral-7B-Instruct-v0.3 from Huggingface.

- Prompting Techniques:

Experiment with zero-shot, one-shot, and few-shot prompting using examples from the training set.

# Evaluation:

Report precision, recall, and macro F1-score for each prompting strategy.
Perform error analysis on:
Prompt instructions.
Class definitions.
In-context example selection and order.

# Output Parsing:

Handle extra information in LLM outputs with regex or custom parsers.

#Deliverables

Write-up: Describes LLM performance, prompting strategies, and error analysis.

# License

This project is for educational purposes only.






