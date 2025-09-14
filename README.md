# Fake-news-detection

# 📰 Fake News Detection Project

## 📄 Project Overview
This project detects whether a news article or headline is *Real* or *Fake* using Machine Learning.  
It demonstrates the complete workflow of *data preprocessing, vectorization, model training, and prediction*.  

- *Dataset:* Combines Fake.csv (fake news) and True.csv (real news) into news.csv.  
- *Model Used:* Logistic Regression with TF-IDF features.  
- *Language/Tools:* Python, Pandas, NLTK, Scikit-learn, Jupyter/Google Colab.  

---

## 🛠 Features
1. Loads and merges fake and real news datasets.  
2. Cleans and preprocesses text (lowercase, remove punctuation, stopwords, lemmatization).  
3. Converts text into numerical features using *TF-IDF vectorization*.  
4. Trains a *Logistic Regression* model to classify news.  
5. Predicts whether any new headline/text is *Real or Fake*.  

---

## ⚠ Limitations
- The dataset primarily contains *political news*, so general news may sometimes be misclassified.  
- The model predicts based on *patterns learned from the dataset*, not factual verification.  
- Accuracy may vary for news topics outside the dataset distribution.  

🔮 *Future Work*  
- Use larger and more diverse datasets.  
- Experiment with advanced models (Random Forest, XGBoost, LSTM, BERT).  
- Deploy as a *Streamlit/Flask web app*.  


## 📂 File Structure

Fake-news-project/
 Fake.csv 
 
 True.csv 
 
 news.csv
 
 Fake_news_detection.ipynb
 
 requirements.txt 
 
 README.md                 
