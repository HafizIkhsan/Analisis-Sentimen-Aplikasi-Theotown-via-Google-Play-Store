# Analisis Sentimen Aplikasi Theotown

Proyek ini merupakan implementasi analisis sentimen teks Bahasa Indonesia untuk aplikasi TheoTown
dengan membandingkan beberapa metode ekstraksi fitur dan model klasifikasi.

## 📊 Dataset
Dataset aplikasi TheoTown berupa ulasan teks yang dikategorikan ke dalam tiga kelas:
positif, negatif, dan netral.

## ⚙️ Preprocessing
Tahapan preprocessing yang dilakukan:
- Case folding
- Cleaning text
- Tokenizing
- Stopword removal
- Stemming
- Normalisasi slang word

## 🔎 Feature Extraction
Eksperimen dilakukan menggunakan:
- Bag of Words (BoW)
- TF-IDF

## 🤖 Modeling
Model yang digunakan:
- Logistic Regression
- Random Forest
- LSTM

Evaluasi dilakukan menggunakan metrik:
accuracy, precision, recall, dan F1-score.

## 🧪 Inference
Model terbaik digunakan untuk melakukan prediksi sentimen pada teks baru.

## 📝 Medium Article

Proses dan cerita lengkap di balik proyek ini—mulai dari data collection,
preprocessing, eksperimen feature extraction (BoW & TF-IDF),
hingga perbandingan beberapa model—ditulis di Medium:

👉 [Analisis Sentimen Aplikasi TheoTown](https://medium.com/@HafizIkhsan/analisis-sentimen-aplikasi-theotown-20671143a228)

Feel free untuk membaca dan memberikan saran atau masukan 🙌
## 📎 Reference
Beberapa bagian preprocessing terinspirasi dari modul pembelajaran Dicoding.
