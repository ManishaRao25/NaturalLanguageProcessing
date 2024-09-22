# NLP Project: Sentiment Analysis on Restaurant Reviews
## Overview
This repository contains code for a Sentiment Analysis project that leverages Natural Language Processing (NLP) techniques. The model is built using Python, Hugging Face's Transformers, and pandas, aiming to classify customer reviews as positive or negative.

This project demonstrates the full pipeline of an NLP workflow, from data cleaning and preprocessing to model inference and visualization of results. The dataset used here is a collection of restaurant reviews, and the primary goal is to determine the sentiment of each review.

### Key Features
**Data Preprocessing** : Cleaning and tokenizing raw text, removing stopwords, punctuation, and more.
**Sentiment Analysis**: Utilizing a pre-trained NLP model from Hugging Face’s Transformers for sentiment classification.
**Visualization**: Displaying the distribution of positive vs. negative sentiments through visual plots.
**Highly Modular**: Code is structured to allow easy extension or modification for other NLP tasks or datasets.

## Project Structure:
-- nlp-sentiment-analysis/
│
├── data/                   # Folder containing the dataset
│   └── Restaurant_Reviews.tsv
├── models/                 # Folder for saved models (if required)
├── preprocess.py           # Preprocessing functions for text data
├── sentiment_analysis.py   # Main script to run sentiment analysis
├── utils.py                # Utility functions (e.g., for loading data)
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation

**Dataset**
The provided dataset consists of restaurant reviews, formatted in a TSV file with two columns:

- Review: The customer review (text).
- Liked: A binary column indicating whether the customer liked the restaurant or not.
You can replace the dataset with any text data by ensuring it follows the same format, or modify the code to handle different formats.

**Results**
After running the pipeline, you will get a classification of each review as positive or negative.
A bar chart is plotted to show the distribution of sentiments, helping visualize the overall feedback trend of the reviews.
Example Output:

**Review	Sentiment**
"The food was amazing!"	Positive
"Service was terrible and slow."	Negative
"I love the ambiance and the staff."	Positive

**License**
This project is licensed under the MIT License - see the LICENSE file for details.
