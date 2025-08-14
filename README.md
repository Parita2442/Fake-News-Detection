# 📰 Fake News Detection using NLP and Machine Learning

This project explores the development of a robust fake news detection system using Natural Language Processing (NLP) and machine learning techniques. The model classifies news articles as **real** or **fake** by analyzing the content and structure of the text, providing insights into patterns of misinformation.

## 📌 Problem Statement
With the increasing proliferation of misinformation across digital platforms, particularly around politics and public health, the need for automated and reliable fake news detection has become critical. This project aims to build a system that can differentiate between real and fake news articles to support the fight against disinformation and preserve media integrity.

## 🧠 Methods & Approach

- **Data Source:** Kaggle's [Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- **Preprocessing:** 
  - Text cleaning (removing noise, stopwords, and sources)
  - Handling imbalanced data
  - Sentiment analysis
- **Text Representation:** 
  - Sentence embeddings using `SentenceTransformer('all-MiniLM-L6-v2')`
  - Title and text embeddings computed separately
- **Classification Models:** 
  - Support Vector Machine (SVM)
  - Random Forest
  - XGBoost
  - Decision Tree
- **Additional Analysis:**
  - Cosine similarity between article titles and body texts
  - Sentiment comparison across fake and real news
- **Performance Metrics:** Accuracy, Precision, Recall, F1-Score, Confusion Matrix

## ✅ Results
- **SVM** outperformed other models with **96.87% accuracy** on text data and **94.53% on title data**.
- Fake news articles showed more negative sentiment compared to real news.
- Cosine similarity analysis indicated titles were not significantly misleading.

## 🔭 Future Enhancements
- Apply **topic modeling (LDA)** for deeper content categorization
- Expand dataset across regions and languages
- Conduct temporal analysis to study trends over time
- Test deployment in real-time environments


## 📊 Business Relevance
This model can be used by social media platforms and news aggregators to flag misleading content, contributing to the ethical use of AI in media and helping users make more informed decisions.




