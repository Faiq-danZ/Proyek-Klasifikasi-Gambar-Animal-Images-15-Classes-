# Proyek-Klasifikasi-Gambar-Animal-Images-15-Classes-

# 🐾 Klasifikasi 15 Jenis Hewan - Deep Learning Project

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15+-orange.svg)](https://www.tensorflow.org/)
[![Accuracy](https://img.shields.io/badge/Accuracy-91%25-brightgreen.svg)]()

Proyek ini adalah sistem klasifikasi gambar otomatis yang mampu mengenali 15 jenis hewan berbeda menggunakan teknik **Transfer Learning** dan **Fine-Tuning**. Dibuat sebagai syarat kelulusan kelas *Belajar Fundamental Deep Learning* di Dicoding Academy.

## 🚀 Fitur Utama
- **Arsitektur Sequential**: Memenuhi standar kriteria industri dengan penambahan layer kustom.
- **High Accuracy**: Mencapai akurasi **91%** pada data pengujian.
- **Multi-Format Export**: Model tersedia dalam format `.h5`, `SavedModel`, `TFLite`, dan `TFJS`.
- **Inference Ready**: Dilengkapi dengan skrip untuk memprediksi gambar baru secara instan.

## 🛠️ Teknologi & Library
- **Bahasa**: Python
- **Framework**: TensorFlow & Keras
- **Arsitektur Base**: MobileNetV2 (Pre-trained)
- **Visualisasi**: Matplotlib & Seaborn
- **Evaluasi**: Scikit-Learn (Confusion Matrix & Classification Report)

## 📊 Hasil Evaluasi Model
Model dilatih selama 12 epoch dengan strategi *Early Stopping* untuk mencegah overfitting.

| Metric | Hasil |
| :--- | :--- |
| **Akurasi Validasi** | 88.24% |
| **Akurasi Test Set** | 91% |
| **Loss Akhir** | ~0.34 |

### Classification Report Highlights:
- **Tiger & Zebra**: Prediksi Sempurna (F1-Score: 1.00)
- **Lion & Panda**: Performa Sangat Tinggi (F1-Score: 0.97)

## 📂 Struktur Proyek
```text
.
├── submission/
│   ├── saved_model/     # Model dalam format SavedModel
│   ├── tfjs_model/      # Model untuk implementasi Web (TensorFlow.js)
│   ├── tflite/          # Model ringan untuk Mobile (TFLite)
│   ├── notebook.ipynb   # File notebook utama
│   ├── README.md        # Dokumentasi proyek
│   └── requirements.txt # Daftar library yang dibutuhkan
└── ...
