# 📧 Fake News Detection

🚫✉️ Say goodbye to spam! This project helps identify fake news using Natural Language Processing (NLP) and Machine Learning. It leverages classic classification models combined with powerful vectorization techniques to accurately classify emails as real or fake.

---

## 🔍 Project Overview

Fake or spam news are a widespread issue in digital communication. This project builds an intelligent classifier that analyzes news content and predicts whether it's legitimate or fake — with **up to 98.7% accuracy**!

---

## 🧠 Models Used

We evaluated two well-established machine learning models:

- ✅ **Logistic Regression**
  - 🔹 **TF-IDF** vectorizer: **~98.7% accuracy**
  - 🔹 **Word2Vec** vectorizer: **~96% accuracy**

- ✅ **Naive Bayes (MultinomialNB)**
  - 🔹 **TF-IDF** vectorizer: **~93% accuracy**
  - 🔹 **Word2Vec** vectorizer: **~87.8% accuracy**

---

## 🧰 Text Vectorization Techniques

### 🔤 TF-IDF (Term Frequency-Inverse Document Frequency)
- Highlights important words based on frequency and uniqueness.
- Achieved top accuracy when paired with Logistic Regression.

### 🧠 Word2Vec (Gensim-based)
- Captures the **semantic meaning** of words by representing them as dense vectors.
- We compute the **average Word2Vec embedding per email**.

---

## 🗂️ Dataset & Preprocessing

The dataset includes labeled email texts — either **real** or **fake**.  
We apply the following preprocessing steps:

- 🔸 Lowercasing
- 🔸 Sentence tokenization
- 🔸 Word tokenization
- 🔸 Removing punctuation & stopwords (optional)

---

## 🚀 How to Run

1. ✅ **Install dependencies**
   ```bash
   pip install -r requirements.txt

## 👨‍💻 Author

Your Name
- 📧 Email: sangamsrivastav2002@gmail.com
- 🔗 GitHub: SangamSrivastav
- 🐍 Passionate about Python, NLP, and making the web a safer place one email at a time!
