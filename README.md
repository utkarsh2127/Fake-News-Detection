# Fake News Detection System

## Overview
The Fake News Detection System is a machine learning project that classifies news articles as real or fake based on their content. It utilizes natural language processing (NLP) techniques and logistic regression for predictive modeling.

## Features
- **Data Preprocessing:** Cleans and prepares the news dataset by handling missing values and merging relevant text features.
- **Text Normalization:** Applies stemming to reduce words to their root form, improving text data uniformity.
- **TF-IDF Vectorization:** Converts textual data into numerical vectors using TF-IDF (Term Frequency-Inverse Document Frequency), capturing word importance in documents.
- **Logistic Regression Model:** Trains a logistic regression classifier to predict whether a news article is real or fake.
- **Model Evaluation:** Computes accuracy scores, confusion matrices, and classification reports to assess model performance.
- **Hyperparameter Tuning:** Utilizes grid search to find optimal regularization parameters for the logistic regression model.
- **Comparison:** Compares model performances between logistic regression and random forest classifiers.

## Technology Stack
- **Python:** Core programming language for implementation.
- **Pandas:** Data manipulation and analysis.
- **NLTK:** Text preprocessing including stemming and stopwords removal.
- **Scikit-learn:** Machine learning library for model building and evaluation.
- **Matplotlib and Seaborn:** Visualization of data and model performance metrics.

## How It Works
1. **Data Preparation:** Loads and cleans the news dataset, handling missing values.
2. **Text Processing:** Merges author names and news titles, applies stemming to content text.
3. **Vectorization:** Transforms text data into TF-IDF numerical representations.
4. **Model Training:** Splits data into training and test sets, trains a logistic regression model.
5. **Model Evaluation:** Assesses model accuracy, generates confusion matrix, and classification report.
6. **Hyperparameter Optimization:** Uses grid search to find optimal parameters for logistic regression.
7. **Comparison:** Compares logistic regression and random forest classifier accuracies.

## Usage
1. **Setup:** Ensure Python and required libraries are installed.
2. **Execution:** Run the script to preprocess data, train the model, and evaluate its performance.
3. **Interpretation:** Review accuracy scores and classification metrics to understand model effectiveness.

## Example
- **Logistic Regression Model:** Achieved an accuracy of 97.9%.
- **Random Forest Classifier:** Achieved an accuracy of 99.3%.

## Contributing
Contributions are welcome! Please submit Pull Requests for feature enhancements or bug fixes.
