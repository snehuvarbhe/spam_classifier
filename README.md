# 📧 Spam Classifier using Naive Bayes

## 📌 Overview
This project is an **SMS spam classifier** leveraging **Natural Language Processing (NLP)** and **Naive Bayes**. It processes text messages and predicts whether they are **spam or ham (not spam)** based on learned patterns.

---

## 🚀 Features
- **Text Preprocessing**: Tokenization, stopword removal, stemming
- **Feature Extraction**: Uses **CountVectorizer** for bag-of-words representation
- **Model Training**: Implements **Multinomial Naive Bayes**
- **Class Balancing**: Uses **SMOTE** for handling imbalance
- **Performance Evaluation**: Computes **Accuracy, Precision, Recall, and Confusion Matrix**

---

## 📂 Dataset
- **Name**: SMS Spam Collection Dataset
- **Size**: 5,574 messages
- **Columns**:
  - `label`: ('spam' or 'ham')
  - `text`: The SMS message content

---

## ⚙️ Project Structure
```
📂 Spam-Classifier
│-- 📄 README.md               # Documentation
│-- 📄 spam_classifier.ipynb   # Main Python Script
│-- 📄 SMSSpamCollection       # Dataset File
```

---

## 🔬 Machine Learning Pipeline
1️⃣ **Data Preprocessing**  
   - Converts text to lowercase
   - Removes non-alphabetic characters
   - Tokenizes and removes stopwords
   - Applies stemming for feature consistency

2️⃣ **Feature Extraction**  
   - **CountVectorizer** (bag-of-words)
   - Uses **top 3000 words** for efficiency

3️⃣ **Handling Class Imbalance**  
   - Uses **SMOTE** (Synthetic Minority Over-sampling Technique)

4️⃣ **Model Training**  
   - Uses **Multinomial Naive Bayes (alpha=0.1)** for text classification
   - Alternative: **Logistic Regression** for improved precision

5️⃣ **Evaluation Metrics**  
   - **Accuracy**: Overall performance measure
   - **Precision**: Spam classification accuracy
   - **Recall**: Measures spam detection capability
   - **Confusion Matrix**: Analyzes misclassification errors

---

## 📊 Model Performance (Current Results)
| Metric    | Score |
|-----------|-------|
| Accuracy  | 97.2% |
| Precision | 88.3% |
| Recall    | 91.2% |

---

## 🛠️ Future Enhancements
- Implement **Deep Learning models (LSTMs, Transformers)**
- Develop a **user-friendly web interface**
- Deploy as a **Flask API** for real-time SMS filtering

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 🤝 Contributing
Pull requests are welcome! For significant changes, please open an issue first.

📧 **Contact:** snehuvarbhe26@example.com  

---

## 🎯 Summary
This project delivers a **high-accuracy spam detection system** using **Naive Bayes & NLP**. It integrates **feature engineering, class balancing, and model tuning** for improved performance. Future goals include **deep learning-based models and API deployment**. 🚀

