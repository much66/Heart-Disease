# Heart Disease Classification

**Dataset** : [source](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset) <br>
**Notebook** : [view](https://github.com/much66/Heart-Disease/blob/main/Heart_Disease_Classification.ipynb)<br>
**Deck** : [view](https://public.tableau.com/views/HeartDisease_17192394275550/HeartDisease?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)<br>

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
    <kbd> <img width="1000" alt="workflow" src="Workflow HDC.png"> </kbd> <br>
    Gambar 1 — Workflow Pembuatan Model
</p>
<br>

## 📂 Insight
- Akurasi Prediksi yang Tinggi
- Identifikasi Faktor Risiko Utama
- Peningkatan Efisiensi Klinis
- Metrik Evaluasi yang Komprehensif
<br>

## 📂 Modeling and Evaluation
- Pembagian Dataset
    - Dataset dibagi dengan rasio 80% untuk data latih (Train) dan 20% untuk data uji (Test).
- Percobaan dengan Beberapa Metode
    - Dilakukan percobaan menggunakan beberapa metode seperti Support Vector Machine, Random Forest, Naive Bayes, Extreme Gradient Boosting, K-Nearest Neighbour.
    - Evaluasi dilakukan menggunakan Accuracy dan Roc Auc Score.
- Hasil Percobaan
  
Model|Accuracy|ROC and AUC Score
---|---|---
Naive Bayes|87.93%|87.74%            
Random Forest|87.93%|87.86%            
Extreme Gradient Boost|87.93%|87.74%           
K-Nearest Neighbour|89.66%|89.52%            
Support Vector Machine|89.66%| 89.64%            


<br>
<p align="center">
    <kbd> <img width="1000" alt="feats" src="Komparasi Model.png"> </kbd> <br>
    Gambar 2 — Perbandingan model
</p>
<br>


## 📂 Recommendations
- Penggunaan Metode Prophet dan Simulasi Monte Carlo: Gunakan Prophet untuk prediksi harga saham dan Simulasi Monte Carlo untuk memperkirakan skenario pergerakan harga di masa depan, memahami risiko dan return dengan lebih baik.
- Portofolio Jangka Pendek: Fokuskan investasi pada jangka pendek (1-3 bulan) untuk responsif terhadap perubahan pasar, monitor kinerja secara berkala, dan sesuaikan portofolio dengan analisis risiko terkini.
- Diversifikasi Saham dengan Volatilitas dan VaR Terendah: Diversifikasikan portofolio dengan saham berisiko rendah, prioritaskan kestabilan harga dan minimalkan potensi kerugian, sehingga portofolio tetap terlindungi dari fluktuasi ekstrem dan memberikan return yang stabil.


<p align="center">
    <kbd> <a href="https://public.tableau.com/views/HeartDisease_17192394275550/HeartDisease?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link" target="_blank"><img width="1000" alt="Dashboard" src="Dashboard Heart.jpg"></a></kbd> <br>
    Gambar 3 — Dashboard Heart Disease
</p>
