# SMART EXPENSIVE MEMBER
A machine learning project that automatically classifies financial transaction descriptions into categories like Food & Dining, Travel, and Shopping. This repository uses a Multinomial Naive Bayes classifier for text classification.

## Overview
This project is a smart helper that does the boring job of sorting your expenses for you. You give it a short note about what you bought, like "movie tickets", and it instantly knows to put it in the Entertainment group.

It learned how to do this by studying hundreds of examples, figuring out which words (like "movie," "uber," or "pizza") belong to which spending category. The result is a simple tool that makes tracking your money easy.
## Core Features
Automatic Categorization: Classifies expenses into 9 distinct categories.

Efficient Model: Utilizes a fast and lightweight Naive Bayes classifier, perfect for text data.

Custom Dataset: Custom built dataset over 300 transaction examples

Ready to Use: Includes scripts to both train the model and make new predictions.

## Tech Stack
Python: The programming language.

Pandas: For loading and manipulating the dataset.

Scikit-learn: For TF-IDF, Label Encoding, the Naive Bayes model, and evaluation metrics.

Joblib: For saving and loading the trained model artifacts.

## Project Structure
EXPENSE-CATEGORIZER/
├── data/
│   └── dataset.csv
├── models/
│   ├── expense_model.joblib
│   ├── label_encoder.joblib
│   └── tfidf_vectorizer.joblib
├── main.ipynb
└── README.md          
