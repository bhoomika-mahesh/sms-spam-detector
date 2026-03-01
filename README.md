# 📩 SMS Spam Detector

This project is a **machine learning model** that detects whether an SMS message is **Spam** or **Ham (Not Spam)** using **Natural Language Processing (NLP)** and **Naive Bayes classifier**.

---

## 📌 Dataset
- Dataset: [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)  
- Contains **5574 messages** labeled as spam or ham.  

---

## ⚙️ Tech Stack
- Python  
- Pandas, NumPy  
- NLTK (text preprocessing)  
- Scikit-learn (TF-IDF, Naive Bayes, Evaluation)  

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/sms-spam-detector.git
   cd sms-spam-detector
   pip install -r requirements.txt
   jupyter notebook sms_spam_detector.ipynb

   ## 🧠 Project Overview

This project builds a Natural Language Processing (NLP) based SMS Spam Detection system.

The pipeline includes:
- Text cleaning and preprocessing using NLTK
- Tokenization and stopword removal
- TF-IDF vectorization
- Training a Multinomial Naive Bayes classifier
- Model evaluation using accuracy and confusion matrix

The system classifies SMS messages as **Spam** or **Ham (Not Spam)**.


## 🚀 Key Features

- Text preprocessing and normalization
- Feature extraction using TF-IDF
- Supervised classification using Naive Bayes
- Model evaluation and performance analysis
- Real-world NLP implementation


## 📊 Model Details

- Vectorizer: TF-IDF
- Algorithm: Multinomial Naive Bayes
- Dataset size: 5574 labeled messages
- Problem Type: Binary Text Classification
