# 📰 Fake News Detection using NLP & Machine Learning

Fake news spreads rapidly on digital platforms and social media, making it difficult to trust online information.  
This project focuses on building a **machine learning-based NLP system** to classify news articles as **Fake or Real** using textual data.

---

## 🚀 Project Overview

This project uses **Natural Language Processing (NLP)** techniques and **Machine Learning models** to detect fake news articles.  
The core idea is to clean and preprocess textual data, extract meaningful features using **TF-IDF**, and train classification models such as **Naive Bayes** and **Random Forest**.

---

## 🎯 Objectives

- Detect whether a given news article is **Fake or Real**
- Apply NLP preprocessing techniques
- Convert text into numerical features using **TF-IDF**
- Train and evaluate ML classification models
- Perform error analysis and extract meaningful insights.

---

## 📂 Dataset Description

The dataset consists of two CSV files:

- **True.csv** → Real news articles  
- **Fake.csv** → Fake news articles  

Each file contains:
- `title` – News headline  
- `text` – Full news article  
- `subject` – Category of news  
- `date` – Publication date  

---

## 🛠️ Technologies Used

- **Python**
- **Pandas, NumPy**
- **NLTK**
- **Scikit-learn**
- **Matplotlib, Seaborn**
- **Jupyter Notebook**

---

## 🔍 Project Workflow

1. **Data Loading & Labeling**
   - Merged fake and real news datasets
   - Assigned labels (0 = Fake, 1 = Real)

2. **Data Cleaning & Preprocessing**
   - Lowercasing text
   - Removing punctuation, numbers, and HTML tags
   - Stopword removal
   - Lemmatization

3. **Exploratory Data Analysis (EDA)**
   - Label distribution
   - Word count analysis
   - Frequent word comparison

4. **Feature Extraction**
   - TF-IDF Vectorization
   - Unigrams and bigrams

5. **Model Building**
   - Multinomial Naive Bayes
   - Random Forest Classifier (comparison)

6. **Model Evaluation**
   - Accuracy Score
   - Classification Report
   - Confusion Matrix
   - ROC Curve & AUC Score

7. **Error Analysis**
   - Analysis of misclassified articles
   - Understanding false positives and false negatives

---

## 📊 Model Performance

| Model | Accuracy |
|------|---------|
| Naive Bayes | ⭐ High |
| Random Forest | Moderate |

> Naive Bayes performed better due to its suitability for high-dimensional sparse text data.

---

## 📌 Key Insights

- Fake news articles often use **sensational and emotional language**
- Real news articles tend to be **formal and factual**
- TF-IDF significantly improves text representation
- Naive Bayes is highly effective for NLP classification tasks

---
