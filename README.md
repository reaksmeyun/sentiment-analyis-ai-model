# HappySad AI 🟢

## 📌 Project Description
**HappySad AI** is a sentiment analysis project that analyzes social media posts (tweets) to classify sentiment as **positive** or **negative**.  

The project supports **emoji handling**, allowing realistic sentiment analysis for posts containing emojis.  

It implements the following models:  
- **Machine Learning:** Logistic Regression, LinearSVC  
- **Deep Learning:** LSTM  

The project has two main parts: **AI models** and **Web interface**.

---

## 📂 Dataset
- **Dataset:** Sentiment140 dataset (~1.6 million tweets)  
- **Source:** [Kaggle / Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140)
- Rename file of dataset that downloaded to "semtiment140_analysis_dataset.csv"
- **Columns:** sentiment, id, date, query, user, text  

**Sentiment mapping:**  
- `0` → negative  
- `4` → positive  

Emoji handling is done using `emoji.demojize()` so the model can understand emojis.  

---

## ⚙️ Features

### 🤖 AI / Model Features
- Cleans tweets (removes URLs, mentions, and special characters)  
- Converts emojis to text descriptions  
- TF-IDF vectorization for ML models  
- Train **LinearSVC** and **Logistic Regression** efficiently  
- Train **LSTM** for deep learning sentiment classification  

### 🌐 Web / Django Features
- User-friendly input form for tweets or text  
- Upload CSV files for batch sentiment analysis  
- Display sentiment predictions for uploaded data  
- **Word cloud visualization** for frequent words in the dataset  
- **Sentiment trend over time** graph  
- Supports emojis in input  
- Integration with pre-trained AI models  
- Real-time results for non-technical users  

---

## 💾 Saved Models
You can download the pre-trained models here:  
[Google Drive - Saved Models](https://drive.google.com/drive/folders/1lIGeVWsw2qdwA3TkzXVzdtwbwcJa2k-H?usp=sharing)  

---

## 🌐 Website
Access the web app here:  
[Your Website Link Here](https://example.com)  

---

## 🛠️ Django Web App Setup

1. **Clone the repository**  
```bash
git clone https://github.com/reaksmeyun/sentiment_project.git
cd sentiment_project
