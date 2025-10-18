

## 📌 Project Title

**Analisis Sentimen Game Brawl Stars Menggunakan Streamlit dan Machine Learning**

---

## 📖 Description

Proyek ini menganalisis ulasan pengguna (*user reviews*) dari game **Brawl Stars** untuk mengetahui persepsi pemain terhadap game tersebut.
Aplikasi ini dibangun dengan **Streamlit** dan model **Machine Learning** yang mampu mengklasifikasikan ulasan menjadi sentimen **positif** atau **negatif**.

Tujuan utama proyek ini adalah membantu pengembang dan pemain memahami opini komunitas tentang gameplay, update, dan performa aplikasi.

---

## ⚙️ Technologies Used

* 🐍 **Python 3.x**
* 🌐 **Streamlit** — antarmuka web interaktif
* 🧠 **Scikit-learn** — pelatihan model Machine Learning
* 💾 **Joblib** — penyimpanan model terlatih
* 🧹 **Pandas & NumPy** — pengolahan data
* 🔤 **Sastrawi** — stemming Bahasa Indonesia
* 🗂️ **Google Play Scraper** — pengambilan data ulasan Brawl Stars

---

## 🌟 Features

* Analisis sentimen otomatis terhadap ulasan pemain
* Visualisasi perbandingan ulasan positif dan negatif
* Antarmuka interaktif berbasis web
* Model dapat dikembangkan ulang dengan dataset baru
* Prediksi cepat dan real-time

---

## 🧩 Setup Instructions

1. **Clone repository**

   ```bash
   git clone https://github.com/username/brawlstars-sentiment.git
   cd brawlstars-sentiment
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Jalankan aplikasi**

   ```bash
   streamlit run app.py
   ```

4. **Buka di browser**

   ```
   http://localhost:8501
   ```

---

## 🤖 AI Support Explanation

Aplikasi ini menggunakan model Machine Learning yang dilatih pada dataset ulasan pemain Brawl Stars.
Langkah-langkahnya:

1. **Data Collection:** Mengambil data ulasan dari Google Play Store dengan library `google-play-scraper`.
2. **Preprocessing:** Membersihkan teks, menghapus tanda baca, dan stemming dengan Sastrawi.
3. **Feature Extraction:** Mengubah teks menjadi vektor menggunakan *TF-IDF Vectorizer*.
4. **Model Training:** Melatih model *Logistic Regression* untuk klasifikasi sentimen.
5. **Deployment:** Menyimpan model ke file `model1.pkl` dan menjalankannya di Streamlit.

---

## Integrasi IBM Granite AI
<img width="1920" height="1080" alt="Pengunaan IBM Granite" src="https://github.com/user-attachments/assets/7a89072b-12b5-4e32-93e7-6653cedc7141" />
untuk mengetahui alur dari analisis sentimen itu sendiri

---

## 🧠 Author

**Nama:** Jujun Munawar
**Institusi:** Institut Teknologi Garut
**Deskripsi:** Aplikasi ini dibuat untuk mengamati persepsi pengguna terhadap game Brawl Stars dengan pendekatan *Machine Learning* dan *Natural Language Processing (NLP)*.


