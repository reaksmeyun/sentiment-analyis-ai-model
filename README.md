# HappySad AI 🟢

## 📌 Project Description
**HappySad AI** is a sentiment analysis project that analyzes social media posts (tweets) to classify sentiment as **positive** or **negative**.  

The project supports **emoji handling**, allowing realistic sentiment analysis for posts containing emojis.  

It implements the following models:  
- **Machine Learning:** Logistic Regression, LinearSVC  
- **Deep Learning:** LSTM  

The project includes:  
- Preprocessing  
- Feature extraction (TF-IDF, embeddings)  
- Model training and evaluation  
- Real-time sentiment prediction  

---

## 📂 Dataset
- **Dataset:** Sentiment140 dataset (~1.6 million tweets)  
- **Source:** [Kaggle / Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140)  
- **Columns:** sentiment, id, date, query, user, text  

**Sentiment mapping:**  
- `0` → negative  
- `4` → positive  

Emoji handling is done using `emoji.demojize()` so the model can understand emojis.  

---

## ⚙️ Features
- Cleans tweets (removes URLs, mentions, and special characters)  
- Converts emojis to text descriptions  
- TF-IDF vectorization for ML models  
- Train **LinearSVC** and **Logistic Regression** efficiently  
- Train **LSTM** for deep learning sentiment classification  
- Real-time sentiment prediction for new posts  

---

## 📈 Usage
1. Preprocess your dataset  
2. Train the ML or DL models  
3. Evaluate model performance  
4. Predict sentiment for new tweets in real-time  

---

## 🔧 Technologies
- Python  
- scikit-learn  
- TensorFlow / Keras  
- Pandas, Numpy  
- emoji library  

---

## 🚀 Goal
To provide a **fast, accurate, and emoji-aware sentiment analysis tool** for social media posts.
