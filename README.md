# Klasifikasi Citra Nyamuk

Proyek ini adalah implementasi klasifikasi citra nyamuk dengan metode deep learning. Menggunakan 2 pemodelan yaitu ensemble learning dan single model.
Tujuan dari proyek ini adalah untuk mengklasifikasikan spesies nyamuk berdasarkan citra dan membandingkan performa klasifikasi.

---

## Tujuan
- Mengklasifikasikan spesies nyamuk berdasarkan citra
- Menerapkan dan membandingkan dua pendekatan pemodelan deep learning
- Mengevaluasi performa model berdasarkan metrik evaluasi

---

## Dataset
- Sumber dataset: Dataset pribadi 
- Jenis data: Citra nyamuk (format JPG)
- Jumlah kelas: 3 kelas
  - Aedes aegypti
  - Aedes albopictus
  - Culex quinquefasciatus

Pembagian data:
- Training set: 999 gambar (64%)
- Validation set: 249 gambar (16%)
- Test set: 312 gambar (20%)

---

## Metodologi
Proyek ini menggunakan dua pendekatan pemodelan untuk melakukan klasifikasi citra nyamuk :
1. Ensemble learning
Menggabungkan EfficientNetB0 dan DenseNet121
2. Single model
Menggunakan EfficientNetB2

---

## Struktur Repository
.
|-- klasifikasi_ensemble_learning.ipynb
`-- klasifikasi_nyamuk.ipynb


## Cara Menjalankan Proyek

1. Clone repository ini:
git clone https://github.com/elisabetsmjtk/Klasifikasi-Nyamuk.git
2. Buka notebook menggunakan Jupyter Notebook/Google Colab
3. Pastikan struktur dataset sudah sesuai (Menggunakan gdrive)
4. Jalankan notebook:
ensemble_model.ipynb untuk ensemble learning
efficientnet_b2.ipynb untuk single model
