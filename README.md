📌 Project Description

SentimentPulse is a sentiment analysis project that analyzes social media posts (tweets) to classify sentiment as positive or negative.

The project supports emoji handling, allowing realistic sentiment analysis for posts containing emojis.

It implements the following models:

Machine Learning: Logistic Regression, LinearSVC

Deep Learning: LSTM

The project includes preprocessing, feature extraction (TF-IDF, embeddings), model training, evaluation, and real-time sentiment prediction.

📂 Dataset

Sentiment140 dataset (1.6 million tweets)

Source: Kaggle / Sentiment140

Columns: sentiment, id, date, query, user, text

Sentiment mapping:

0 → negative

4 → positive

Emoji handling is done using emoji.demojize() so the model can understand emojis.

⚙️ Features

Cleans tweets (removes URLs, mentions, special characters)

Converts emojis to text descriptions

TF-IDF vectorization for ML models

Train LinearSVC and Logistic Regression efficiently

Train LSTM for deep learning sentiment classification

Real-time sentiment prediction for new posts
