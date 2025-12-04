# 📧 Email Spam Detection (Machine Learning - Naive Bayes)

This project classifies emails as **Spam** or **Not Spam** using a **Naive Bayes machine learning model**.  
It uses text processing + vectorization to convert email content into machine-understandable form and predicts whether the message is spam.

---

## 🚀 Project Highlights

| Feature | Description |
|--------|-------------|
| 📌 Uses Naive Bayes Classifier | Best performing model for text classification |
| 📌 CountVectorizer for NLP | Converts email text into numerical vectors |
| 📌 100% Automated Pipeline | Load → Transform → Train → Predict |
| 📌 Custom Email Input Supported | Can test your own messages |
| 📌 Prints Model Accuracy | Shows prediction performance in %

---

## 🧠 How The Model Works

1. Load dataset (`emails.csv`)  
2. Convert email text into vectors using **CountVectorizer()**  
3. Train **Multinomial Naive Bayes** model  
4. Input a test email → system predicts *Spam / Ham*  
5. Displays model accuracy  

---

## 📂 Required Dataset Format

Your dataset must contain:  

| Column Name | Description |
|------------|-------------|
| **text** | Email message body/content |
| **spam** | 1 = spam, 0 = not spam |

Example:

| text | spam |
|------|------|
| Win money now! Click here | 1 |
| Meeting at 3 PM tomorrow | 0 |

---

