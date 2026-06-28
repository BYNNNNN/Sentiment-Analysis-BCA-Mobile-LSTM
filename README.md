# 📊 Sentiment Analysis of BCA Mobile Reviews using LSTM

## 📖 Overview

This project implements a sentiment analysis model to classify user reviews of the **BCA Mobile** application into Positive, Neutral, and Negative sentiments using the **Long Short-Term Memory (LSTM)** algorithm.

The project covers the complete machine learning workflow, including data scraping, text preprocessing, feature extraction using Word2Vec, model training, and performance evaluation.

---

## 🎯 Objectives

- Analyze user sentiment toward the BCA Mobile application.
- Build a deep learning model using LSTM.
- Evaluate model performance using standard classification metrics.

---

## 📂 Project Structure

```text
Sentiment-Analysis-BCA-Mobile-LSTM
│
├── notebook
├── dataset
├── resources
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ⚙️ Technologies

- Python
- Pandas
- NumPy
- TensorFlow
- Keras
- Gensim
- Scikit-learn
- Matplotlib
- Google Colab

---

## 🔄 Workflow

1. Data Scraping
2. Text Preprocessing
3. Sentiment Labeling
4. Word2Vec Embedding
5. Padding Sequence
6. LSTM Model Training
7. Model Evaluation

---

## 📊 Dataset

- Source: Google Play Store
- Total collected reviews: **10,000**
- Final dataset after preprocessing: **6,859**

---

## 🚀 Future Improvements

- Expand slang word dictionary
  Enrich the slang_words.csv normalization dictionary to better handle evolving informal Indonesian language in app reviews.
- Improve class balance handling
  Address potential class imbalance between Positive, Neutral, and Negative to reduce misclassification, as reflected in the confusion matrix results.
- Hyperparameter tuning
  Experiment with different LSTM configurations (units, dropout rate, learning rate) to further improve beyond the current 91.84% accuracy

---

## 👤 Author

**Suryo Bintoro**

Machine Learning & Data Analytics Enthusiast
