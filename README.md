
# Phishing Email Detection Model

A machine learning-based cybersecurity project that detects whether an email is **Phishing** or **Safe** using Python and Scikit-learn.

---

## 📌 Project Overview

Phishing emails are fraudulent messages designed to trick users into clicking malicious links, opening dangerous attachments, or providing sensitive information such as usernames, passwords, and financial details.

This project uses **Machine Learning and Natural Language Processing (NLP)** techniques to classify email messages into two categories:

- 🔴 **Phishing**
- 🟢 **Safe**

The model analyzes email text and learns patterns from labeled training data.

---

## 🎯 Project Objective

The main objectives of this project are:

- Detect phishing emails automatically.
- Train a machine learning model using labeled email data.
- Convert email text into numerical features.
- Classify emails as Phishing or Safe.
- Evaluate model performance.
- Generate accuracy and classification reports.
- Build a foundation for future SOC-based phishing analysis.

---

## 🚀 Key Features

- Phishing email classification
- Safe email classification
- Text-based feature extraction
- TF-IDF / text vectorization
- Machine learning classification
- Accuracy calculation
- Precision, Recall and F1-score
- Confusion Matrix support
- URL analysis extension
- Suspicious keyword detection
- Future IOC extraction support
- SOC investigation integration

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Dataset Processing |
| NumPy | Numerical Operations |
| Scikit-learn | Machine Learning |
| TF-IDF | Text Feature Extraction |
| Multinomial Naive Bayes | Classification |
| Matplotlib | Visualization |
| Seaborn | Confusion Matrix |
| Joblib | Model Saving |
| Streamlit | Web Interface |
| Kali Linux | Development Environment |
| VS Code | Code Editor |
| Git & GitHub | Version Control |

---

# 🔄 Project Workflow

```text
                  Email Dataset
                       |
                       v
                Data Preparation
                       |
                       v
                 Train / Test Split
                       |
                       v
                Text Vectorization
                       |
                       v
             Machine Learning Model
                       |
                       v
                   Prediction
                       |
             +---------+---------+
             |                   |
             v                   v
        🔴 Phishing          🟢 Safe
             |
             v
       Model Evaluation
             |
             v
   Accuracy / Precision /
   Recall / F1-Score
