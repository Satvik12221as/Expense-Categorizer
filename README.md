# SMART EXPENSIVE MEMBER
A machine learning project that automatically classifies financial transaction descriptions into categories like Food & Dining, Travel, and Shopping. This repository uses a Multinomial Naive Bayes classifier, a fast and effective algorithm for text classification.

## Overview
This project solves the common problem of manually tracking expenses. It implements a classic Natural Language Processing (NLP) pipeline:

Text Cleaning: Raw transaction texts are cleaned and preprocessed.

Feature Extraction: The cleaned texts are converted into numerical features using TF-IDF.

Model Training: A Multinomial Naive Bayes model is trained on the features to learn the patterns for each expense category.

The result is a simple yet powerful command-line tool that can predict the category for any new transaction.

## Core Features
Automatic Categorization: Classifies expenses into 9 distinct categories.

Efficient Model: Utilizes a fast and lightweight Naive Bayes classifier, perfect for text data.

Custom Dataset: Trained on a diverse, custom-built dataset of over 300 transaction examples.

Ready to Use: Includes scripts to both train the model and make new predictions.

Visual Evaluation: Automatically generates a confusion matrix to visualize model performance.

## Tech Stack
Python: The core programming language.

Pandas: For loading and manipulating the dataset.

Scikit-learn: For TF-IDF, Label Encoding, the Naive Bayes model, and evaluation metrics.

Joblib: For saving and loading the trained model artifacts.

## Project Structure
expense-categorizer/
├── models/
├── plots/               
├── .gitignore
├── README.md
├── requirements.txt
├── dataset.csv          
├── main.py            
└── predict.py           
