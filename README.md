# Shopee Sentiment Analysis 🛍️

Capstone project for **AI Hacktiv8** — analyzing sentiment from Shopee product reviews using various NLP techniques and classification models.

---

## 📌 Project Objective
To classify Shopee product review texts into **positive** and **negative** sentiment classes. The goal is to help sellers and analysts gain insights from customer feedback more efficiently.

---

## 🧰 Tools and Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Sastrawi (for Indonesian text preprocessing)
- Jupyter Notebook

---

## 🔎 Workflow Overview
1. **Data Cleaning**  
   - Remove HTML tags, special characters, etc.
2. **Preprocessing**  
   - Tokenizing, lowercasing, stopword removal, stemming (Indonesian)
3. **Feature Extraction**  
   - TF-IDF Vectorization
4. **Modeling**  
   - Trained Logistic Regression, Naive Bayes, and SVM models
5. **Evaluation**  
   - Accuracy, Precision, Recall, F1-Score

---
## 🚀 How to Run

1. **Clone Repository**
   ```bash
   git clone https://github.com/hellaww/Shopee_Sentiment_Analysis.git
   cd Shopee_Sentiment_Analysis

## 📊 Model Performance (Best)
| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | **88%**  |

---

## 📂 File Structure
Shopee_Sentiment_Analysis/
│
├── data/
│   └── shopee_reviews.csv
│
├── models/
│   └── logistic_model.pkl
│
├── images/
│   └── confusion_matrix.png
│
├── sentiment_analysis.py
├── preprocessing.py
├── README.md
└── requirements.txt

