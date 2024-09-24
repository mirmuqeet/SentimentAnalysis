# SentimentAnalysis


## Overview
This project implements a sentiment analysis model that classifies product reviews into positive and negative sentiments using Natural Language Processing (NLP) techniques. The model utilizes various preprocessing steps, sentiment analysis methods, and a machine learning model for predictions. Visualizations are included to display sentiment distributions and word clouds.

## Features
- **Text Preprocessing**: Tokenization, stop word removal, and lemmatization of text data.
- **Sentiment Analysis**: Application of NLTK's Sentiment Intensity Analyzer to assign sentiment scores to reviews.
- **Model Training**: Logistic Regression model trained to classify reviews as positive or negative.
- **Model Evaluation**: Comprehensive evaluation metrics including precision, recall, F1-score, and confusion matrix.
- **Visualizations**: Sentiment distribution pie chart and word cloud of reviews.

## Dataset
The dataset used for this project is `amazon.csv`, which contains:
- `Text`: The product review text.
- `label`: Sentiment label (0 for Negative, 1 for Positive).

## Technologies Used
- **Python**: Main programming language.
- **Pandas**: Data manipulation and analysis.
- **NLTK**: Natural Language Toolkit for text processing and sentiment analysis.
- **Scikit-learn**: Machine learning library for model training and evaluation.
- **Matplotlib**: Plotting library for visualizations.
- **Seaborn**: Statistical data visualization library.
- **WordCloud**: Library for generating word clouds.

