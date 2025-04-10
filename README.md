## 📊 Sentiment Analysis using Machine Learning

Proyek ini merupakan studi kasus analisis sentimen dari ulasan aplikasi Android (Google Play Store) menggunakan pendekatan _Machine Learning_. Data dikumpulkan menggunakan `google-play-scraper`, diproses dengan Natural Language Processing (NLP) tools, lalu diklasifikasikan menggunakan beberapa algoritma seperti:

- Naive Bayes
- Logistic Regression
- Random Forest
- Decision Tree

Tujuannya adalah untuk mengklasifikasikan sentimen pengguna terhadap aplikasi apakah **positif**, **negatif**, atau **netral** berdasarkan teks ulasan mereka.

---

## 🚀 Fitur

- Web scraping ulasan dari Google Play Store
- Pembersihan data teks (cleaning, tokenizing, stemming, stopword removal)
- Visualisasi WordCloud
- Implementasi dan evaluasi model klasifikasi
- Model evaluasi menggunakan Confusion Matrix dan akurasi

---

## 🧰 Instalasi

### 1. Clone repositori (jika tersedia di GitHub)

```bash
git clone https://github.com/username/repo-sentiment-analysis.git
cd repo-sentiment-analysis
```

### 2. Buat dan aktifkan Virtual Environment

#### 💻 Windows:

```bash
python -m venv env
env\Scripts\activate
```

#### 🍎 Linux/macOS:

```bash
python3 -m venv env
source env/bin/activate
```

### 3. Install semua dependensi dari `requirements.txt`

```bash
pip install -r requirements.txt
```

> Jika `nltk` digunakan, pastikan download resource-nya:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

---

## 🧪 Jalankan Notebook

Buka Jupyter Notebook atau VS Code, lalu jalankan file:

```bash
Sentiment_Analysis_using_Machine_Learning.ipynb
```

---

## 📝 Catatan

- Proses scraping bisa memakan waktu tergantung jumlah review dan koneksi internet.
- Disarankan menggunakan `reviews()` (bukan `reviews_all()`) untuk membatasi jumlah data agar tidak terlalu besar.
- Pastikan koneksi internet aktif saat proses scraping.
