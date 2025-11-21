# Google Play Review Sentiment Analysis (End-to-End Project)

Proyek ini merupakan implementasi lengkap *end-to-end* untuk melakukan **sentiment analysis** pada ulasan pengguna Google Play.  
Data dikumpulkan melalui proses *scraping*, kemudian diproses dan digunakan untuk membangun model machine learning untuk klasifikasi sentimen positif atau negatif.

---

## 📌 Project Overview

Sentiment analysis digunakan untuk memahami opini dan persepsi pengguna terhadap suatu aplikasi.  
Project ini mencakup:

1. **Scraping Data**  
   - Mengambil semua ulasan aplikasi dari Google Play menggunakan `google-play-scraper`
   - Menyimpan ulasan dalam format CSV untuk diproses lebih lanjut

2. **Data Preprocessing**  
   - Case folding  
   - Cleaning (menghapus simbol, angka, noise)  
   - Stopword removal
   - Stemming  
   - Tokenization  
   - Label encoding  

3. **Exploratory Data Analysis (EDA)**  
   - Distribusi sentimen  

4. **Modeling**  
   - TF-IDF Vectorization  
   - Model klasifikasi (contoh: Random Forest / Logistic Regression / SVM)  
   - Evaluasi model menggunakan accuracy

---

## 🛠️ Tech & Tools

- Python  
- pandas  
- scikit-learn  
- google-play-scraper  
- matplotlib & seaborn  
- Jupyter Notebook  

---

## 🚀 How to Run

1. Clone repository:
   ```bash
   git clone https://github.com/username/repo-name.git
2. Install dependencies:
    pip install -r requirements.txt
3. Buka notebook dan jalankan sel secara berurutan.
