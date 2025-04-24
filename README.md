# 🧠 Image Classification: Plastic, Paper, and Garbage Bags

Proyek ini menggunakan Deep Learning (CNN) untuk mengklasifikasikan gambar kantong ke dalam tiga kategori:
- 🛍️ Kantong Plastik (Plastic Bag)
- 📄 Kantong Kertas (Paper Bag)
- 🗑️ Kantong Sampah (Garbage Bag)

Dataset diambil dari Kaggle dan diolah menggunakan Google Colab. Model akhir disimpan ke Google Drive.

---

## 📦 Dataset

Dataset yang digunakan:  
[Plastic Paper Garbage Bag Synthetic Images (Kaggle)](https://www.kaggle.com/datasets/vencerlanz09/plastic-paper-garbage-bag-synthetic-images)

## 🔧 Fitur Proyek

- 🔽 Download otomatis dari Kaggle
- 🗂️ Ekstraksi dan pemisahan dataset (train, val, test)
- 🖼️ Visualisasi sample gambar
- 🧠 CNN dengan augmentasi gambar
- ⏹️ EarlyStopping dan ReduceLROnPlateau untuk training
- 📉 Penyesuaian class weight untuk dataset imbalance
- 📊 Evaluasi model dan confusion matrix
- 💾 Export model ke Google Drive (`.h5` dan SavedModel)

---

## 🛠️ Teknologi

- Python (Google Colab)
- TensorFlow / Keras
- Matplotlib, Seaborn
- scikit-learn
- PIL (Python Imaging Library)

---

## 🚀 Cara Menjalankan

1. **Upload `kaggle.json`** ke Google Colab
2. Jalankan semua sel di file notebook
3. File ZIP akan diunduh & diekstrak otomatis
4. Dataset dibagi menjadi train/val/test
5. Model dilatih, dievaluasi, dan disimpan ke Google Drive

---

## 🐍 Instalasi Requirements

Jika kamu ingin menjalankan proyek ini secara lokal:

```bash
pip install -r requirements.txt
