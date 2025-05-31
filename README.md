# 📦 Sentiment Analysis of Shopee Product Reviews

## 📌 Project Overview
Proyek ini bertujuan untuk menganalisis sentimen dari ulasan produk yang ada di platform Shopee menggunakan teknik *Natural Language Processing* (NLP) dan *Machine Learning*. Dengan memanfaatkan data ulasan yang tersedia secara publik, proyek ini menggali insight yang bisa berguna untuk meningkatkan pelayanan, produk, dan pengalaman pengguna.

## 📂 Raw Dataset Link
Dataset yang digunakan berasal dari data publik ulasan Shopee. Data tersebut telah dibersihkan dan diproses untuk keperluan analisis.  
📎 [Shopee Customer Review Sentiment Analysis - Kaggle Notebook](https://www.kaggle.com/code/davydev/shopee-customer-review-sentiment-analysis/data)

## 🔍 Insight & Findings
- Mayoritas ulasan pelanggan bersentimen **positif**, mencerminkan kepuasan terhadap produk dan layanan.
- Kata-kata yang sering muncul pada review positif: *“bagus”, “murah”, “cepat”*.
- Kata-kata pada review negatif biasanya mengandung: *“lama”, “rusak”, “tidak sesuai”*.
- Hasil klasifikasi sentimen menunjukkan distribusi:  
  - Positif: 70%  
  - Negatif: 20%  
  - Netral: 10%

## 🤖 AI Support Explanation
Analisis dilakukan dengan pendekatan NLP dan klasifikasi teks. Tahapan utama:
- **Preprocessing:** case folding, stopwords removal, stemming, tokenizing.
- **Vectorization:** menggunakan TF-IDF untuk mengubah teks menjadi fitur numerik.
- **Modeling:** digunakan algoritma Machine Learning seperti **Naive Bayes** untuk klasifikasi sentimen.
- Evaluasi model dilakukan dengan metrik akurasi dan confusion matrix.

## 📓 Notebook Analisis Lengkap
Notebook analisis lengkap dapat dilihat di:  
📓 [Shopee Sentiment Analysis - Colab](https://colab.research.google.com/drive/1eQ9NPrYywwZRcycs-lQ9AQIsEMQHDBZU?usp=sharing)

---

