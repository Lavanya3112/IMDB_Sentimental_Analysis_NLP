# 🎬 IMDb Sentiment Analysis using NLP & Machine Learning

## 📌 Overview

This project implements an end-to-end Sentiment Analysis system using Natural Language Processing (NLP) techniques and Machine Learning models.
The goal is to classify movie reviews from the IMDb dataset as **positive** or **negative**.

---

## 🔍 Features

* Text preprocessing:

  * Lowercasing
  * Removing punctuation & stopwords
  * Tokenization
* Feature engineering:

  * Bag of Words (BoW)
  * TF-IDF
* Machine Learning models:

  * Logistic Regression
  * Naive Bayes
  * Decision Tree
* Model evaluation using:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
* Model comparison with visualization

---

## 📂 Dataset

The dataset used is the IMDb movie reviews dataset from Kaggle:

👉 https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

⚠️ Note: Dataset is not included in this repository due to size limitations. Please download it from the link above and place it in the project directory.

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* NLTK
* Scikit-learn
* Matplotlib

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/imdb-sentiment-analysis-nlp.git
```

2. Install dependencies:

```bash
pip install pandas numpy nltk scikit-learn matplotlib
```

3. Download dataset from Kaggle and place it in the project folder

4. Run the notebook:

```bash
jupyter notebook
```

---

## 📊 Results

| Model               | Vectorizer | Accuracy |
| ------------------- | ---------- | -------- |
| Logistic Regression | TF-IDF     | ~90%     |
| Logistic Regression | BoW        | ~89%     |
| Naive Bayes         | TF-IDF     | ~87%     |
| Decision Tree       | TF-IDF     | ~72%     |

---

## 🧠 Key Insights

* TF-IDF outperformed Bag of Words due to better feature weighting
* Logistic Regression achieved the best performance (~90%)
* Naive Bayes worked well as a baseline model
* Decision Tree performed poorly on high-dimensional text data
* Proper preprocessing significantly improved results

---

## 📎 Author

**Lavanya Dive**
BSc Data Science Student

---

## ⭐ Acknowledgment

This project was completed as part of the **Innomatics Research Labs Internship (Feb 2026)**.
