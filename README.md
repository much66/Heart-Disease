# Heart-Disease-Classification

**Dataset** : [source](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset) <br>
**Notebook** : [view](https://github.com/much66/Optimalisasi-Portofolio-Saham/blob/main/Banking_Stock_Forecasting.ipynb)<br>
**Deck** : [view](https://github.com/much66/Optimalisasi-Portofolio-Saham/blob/main/Deck%20Presentasi.pdf)<br>

<br>

**Table of Contents**
- [Business Understanding]()
- [Workflow]()
- [Insight]()
- [Modeling and Evaluation]()
<br>


## 📂 Business Understanding
### Problem Statement
Lembaga kesehatan menghadapi tantangan dalam mendeteksi dan mengklasifikasikan penyakit jantung secara dini untuk mengurangi tingkat kematian dan meningkatkan kualitas hidup pasien. Deteksi dini penyakit jantung memungkinkan penanganan dan pengobatan yang lebih cepat dan efektif, yang dapat mengurangi risiko komplikasi serius. Oleh karena itu, diperlukan solusi yang akurat dan efisien untuk mengklasifikasikan penyakit jantung menggunakan data pasien sebagai alat bantu yang mendukung keputusan klinis.

### Goals
- Meningkatkan Akurasi Diagnosis: Mengembangkan model klasifikasi yang dapat mendeteksi penyakit jantung dengan tingkat akurasi yang tinggi.
- Mengidentifikasi Faktor Risiko: Menentukan feature importance untuk mengidentifikasi faktor-faktor risiko utama yang berkontribusi terhadap penyakit jantung.
Objectives.

### Objectives
- Membuat Model Klasifikasi: Mengembangkan model klasifikasi menggunakan algoritma machine learning untuk memprediksi apakah seorang pasien menderita penyakit jantung.
- Evaluasi Kinerja Model: Mengukur kinerja model dengan metrik evaluasi seperti akurasi, presisi, recall, dan F1-score untuk memastikan keandalan model dalam deteksi penyakit jantung.
- Analisis Feature Importance: Menganalisis feature importance untuk mengidentifikasi variabel-variabel yang paling berpengaruh terhadap prediksi penyakit jantung, membantu dalam pengambilan keputusan klinis dan penentuan intervensi medis yang tepat, dengan catatan bahwa hasil model ini digunakan sebagai alat bantu diagnosa.

<br>


## 📂 Workflow
<p align="center">
    <kbd> <img width="1000" alt="workflow" src="Workflow Forecasting.png"> </kbd> <br>
    Gambar 1 — Workflow Pembuatan Model
</p>
<br>

## 📂 Insight
- Prediksi harga setiap saham 7 periode mendatang
- Maksimal kerugian setiap saham
- Kestabilan harga setiap saham
- Rekomendasi saham berdasarkan Volatility dan VaR Terkecil
<br>

## 📂 Modeling and Evaluation
- Pembagian Dataset
    - Dataset dibagi dengan rasio 80% untuk data latih (Train) dan 20% untuk data uji (Test).
- Percobaan dengan Beberapa Metode
    - Dilakukan percobaan menggunakan beberapa metode seperti Prophet, ARIMA, Neural Prophet, dan Exponential Smoothing.
    - Evaluasi dilakukan menggunakan Mean Absolute Percentage Error (MAPE) untuk mengukur akurasi prediksi.
- Hasil Percobaan
    - ARIMA: MAPE 0.3009
    - Exponential Smoothing: MAPE 0.0720
    - Neural Prophet: MAPE 0.1730
    - Prophet: MAPE 0.036 (Akurasi tertinggi)

<br>
<p align="center">
    <kbd> <img width="1000" alt="feats" src="Komparasi.png"> </kbd> <br>
    Gambar 2 — Perbandingan model
</p>
<br>


## 📂 Recommendations
- Penggunaan Metode Prophet dan Simulasi Monte Carlo: Gunakan Prophet untuk prediksi harga saham dan Simulasi Monte Carlo untuk memperkirakan skenario pergerakan harga di masa depan, memahami risiko dan return dengan lebih baik.
- Portofolio Jangka Pendek: Fokuskan investasi pada jangka pendek (1-3 bulan) untuk responsif terhadap perubahan pasar, monitor kinerja secara berkala, dan sesuaikan portofolio dengan analisis risiko terkini.
- Diversifikasi Saham dengan Volatilitas dan VaR Terendah: Diversifikasikan portofolio dengan saham berisiko rendah, prioritaskan kestabilan harga dan minimalkan potensi kerugian, sehingga portofolio tetap terlindungi dari fluktuasi ekstrem dan memberikan return yang stabil.


<p align="center">
    <kbd> <img width="800" alt="feats" src="Dashboard Portofolio.jpg"> </kbd> <br>
    Gambar 3 — <a href="https://lookerstudio.google.com/reporting/feda5c98-ea8e-46a9-aa6a-cadb7e207c58">Dashboard Saham Optimal</a>
</p>
