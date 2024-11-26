# Twitter-Sentiment-Analysis

## Project Overview

This project performs **Sentiment Analysis** on Twitter data to classify tweets into different categories: **Positive**, **Negative**, **Neutral**, and **Irrelevant**. The goal is to analyze the sentiments expressed in tweets and determine their respective categories, which can be useful for various applications such as opinion mining, market sentiment analysis, and social media monitoring.

## Features

- **Data Preprocessing**: Includes functions to clean and preprocess the tweet data by removing punctuation, stop words, emojis, and URLs.
- **TF-IDF Vectorization**: Text data is vectorized using the TF-IDF method to convert textual data into numerical features for machine learning.
- **Sentiment Classification with Random Forest**: A **Random Forest** classifier is used to train a model on the preprocessed tweet data and predict sentiment categories (Positive, Negative, Neutral, Irrelevant).
- **Visualization**: Provides insightful visualizations such as:
  - Word cloud to visualize the most frequent words in the dataset.
  - Distribution of tweet lengths across different sentiment categories.

## Dataset

This project works with a dataset of tweets labeled with sentiment categories:
- **Positive**: Tweets that express positive sentiments.
- **Negative**: Tweets that express negative sentiments.
- **Neutral**: Tweets that are neutral or not expressing a clear sentiment.
- **Irrelevant**: Tweets that are not relevant to the analysis (e.g., ads, spam).

## Requirements

To run this project, you'll need to install the following Python packages:

- `nltk` for text processing and natural language tasks
- `seaborn` and `matplotlib` for data visualization
- `pandas` for data handling and manipulation
- `wordcloud` for generating word clouds
- `scikit-learn` for machine learning models, including Random Forest and TF-IDF vectorization

You can install these dependencies using pip:

```bash
pip install nltk seaborn matplotlib pandas wordcloud scikit-learn
