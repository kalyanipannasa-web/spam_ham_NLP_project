# SMS Spam Detection using Machine Learning

## Overview

This project is a Machine Learning-based SMS Spam Detection system that classifies text messages as either **Spam** or **Ham (Not Spam)**. The model is trained using the SMS Spam Collection dataset and uses Natural Language Processing (NLP) techniques to convert text into numerical features before classification.

## Features

* Text preprocessing and cleaning
* NLP-based feature extraction using CountVectorizer
* Spam/Ham classification using Multinomial Naive Bayes
* Model evaluation with accuracy and classification metrics
* Easy-to-use and lightweight implementation

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* NLTK
* CountVectorizer
* Multinomial Naive Bayes

## Workflow

1. Load and preprocess SMS data.
2. Clean and tokenize text messages.
3. Convert text into numerical vectors using CountVectorizer.
4. Split the dataset into training and testing sets.
5. Train a Multinomial Naive Bayes classifier.
6. Evaluate model performance using accuracy score and classification report.
7. Predict whether a new SMS message is spam or ham.

## Results

The model achieves high accuracy in detecting spam messages and demonstrates the effectiveness of Naive Bayes for text classification tasks.

## Future Improvements

* Deploy as a web application using Streamlit or Flask.
* Experiment with TF-IDF Vectorization.
* Compare performance with Logistic Regression, SVM, and Random Forest.
* Add real-time message prediction functionality.
