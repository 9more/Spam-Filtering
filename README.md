# Spam Filtering
## Spam Message Classification

Links to other projects: https://github.com/9more/Sentiment-Analysis-Amazon-Review-Data-/tree/main
https://github.com/9more/Diabetes-Detection-


## Overview

This project develops a machine learning pipeline to classify text messages as **Spam** or **Not Spam**. The solution uses natural language processing (NLP) techniques to clean and transform text data before training and evaluating multiple classification models.

## Libraries and Tools

* **Python**
* **pandas** – data loading and preprocessing
* **NumPy** – numerical operations
* **spaCy** – text cleaning, tokenisation, stop-word removal, and lemmatisation
* **scikit-learn** – machine learning pipeline, model training, hyperparameter tuning, and evaluation
* **TfidfVectorizer** – text feature extraction
* **LogisticRegression**, **LinearSVC**, **MultinomialNB** – classification algorithms
* **GridSearchCV** – hyperparameter optimisation
* **pickle** – model serialisation and deployment

## Project Workflow

1. Load and explore the dataset.
2. Clean and preprocess text using spaCy.
3. Split the data into training and testing sets.
4. Convert text into numerical features using TF-IDF.
5. Build a machine learning pipeline combining feature extraction and classification.
6. Optimise model performance using GridSearchCV with cross-validation.
7. Evaluate models using F1-score, precision, recall, and confusion matrix.
8. Save the best-performing model using pickle for future predictions.

## Outcome

The final solution provides an automated and scalable approach for detecting spam messages from raw text input using a production-ready machine learning pipeline.
