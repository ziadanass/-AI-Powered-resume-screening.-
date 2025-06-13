# 🤖 AI-Powered Resume Screening System

An AI-powered system that automates resume screening using NLP and machine learning, helping recruiters efficiently identify qualified candidates and reduce manual effort and bias in the hiring process.

---

## 📌 Project Overview

This project presents an intelligent solution to streamline the candidate selection process.  
By leveraging Natural Language Processing (NLP) techniques and machine learning models, the system automatically analyzes and classifies resumes based on their content.

---

## ❗ Problem Statement

Traditional resume screening is:
- Time-consuming
- Prone to human error and bias
- Inefficient when handling large volumes

This system aims to *automate* the screening process, ensuring *faster, fairer, and more accurate* candidate evaluation.

---

## 🧰 Tools & Technologies Used

- Python 3
- pandas, NumPy
- NLTK (Natural Language Toolkit)
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Random Forest Classifier

---

## 🗃 Dataset

- 📁 File used: Extended_Filtered_Data_3000.csv
- Contains pre-processed resume texts and classification labels
- Data cleaning steps included:
  - Null value removal
  - Punctuation and unnecessary character removal

---

## 🔄 Data Preprocessing Steps

1. Lowercasing all text
2. Stopword removal using *NLTK*
3. Lemmatization via WordNetLemmatizer
4. TF-IDF feature extraction
5. Label encoding of target classes

---

## 🤖 Model Training

Implemented and compared two machine learning models:
1. *Logistic Regression* – simple and interpretable baseline
2. *Random Forest Classifier* – robust and performs better with complex data

✅ *Hyperparameter tuning* was performed using GridSearchCV.

---

## 📊 Evaluation Metrics

Models were evaluated using:
- *Accuracy Score*
- *Classification Report*
  - Precision
  - Recall
  - F1-score

> Example: Random Forest achieved ~X% accuracy (adjust based on your results)

---


## 🧠 Conclusion

This project proves the effectiveness of AI in automating resume screening.  
It helps HR teams:
- Save time
- Reduce bias
- Make informed hiring decisions faster

---

## 🚀 Future Enhancements

- Integration with a web-based HR dashboard
- Support for resumes in multiple languages
- Using deep learning models like *BERT* for contextual understanding

---

## 👤 Author

*Ziad Anas*  
AI & Data Science Enthusiast  


---

## 💼 Project Status

✅ Completed initial implementation  
🧪 Ready for integration & real-world testing  
📈 Open to contributions and improvements
---
