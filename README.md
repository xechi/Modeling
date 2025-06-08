# HIVE-ML

**HIVE** adalah aplikasi berbasis machine learning yang dirancang untuk mengidentifikasi penyakit dan hama pada daun padi. Aplikasi ini bertujuan untuk membantu petani menghemat waktu dan biaya diagnosis penyakit tanaman dengan solusi otomatis berbasis AI.

---

## 📦 Dataset

- Sumber Dataset:
[Hive Paddy Disease & Pest Dataset](https://www.kaggle.com/datasets/muhsyuaib/hive-dataset)


- Daftar Kelas:

#### 🦠 Penyakit (Disease)

| Indeks | Nama Kelas                  |
|--------|-----------------------------|
| 1      | bacterial_leaf_blight       |
| 2      | bacterial_leaf_streak       |
| 3      | bacterial_panicle_blight    |
| 4      | blast                       |
| 5      | brown_spot                  |
| 6      | downy_mildew                |
| 7      | tungro                      |
| 8      | normal (daun sehat)         |

#### 🐛 Hama (Pest)

| Indeks | Nama Kelas                  |
|--------|-----------------------------|
| 9      | asiatic_rice_borer          |
| 10     | brown_plant_hopper          |
| 11     | dead_heart                  |
| 12     | hispa                       |
| 13     | paddy_stem_maggot           |
| 14     | rice_gall_midge             |
| 15     | rice_leaf_caterpillar       |
| 16     | rice_leaf_hopper            |
| 17     | rice_leaf_roller            |
| 18     | rice_shell_pest             |
| 19     | rice_stem_fly               |
| 20     | rice_water_weevil           |
| 21     | thrips                      |
| 22     | yellow_rice_borer           |
  

---

## 🎯 Machine Learning Deliverables

- Mengembangkan model klasifikasi daun padi dengan machine learning / deep learning.
- Menggabungkan data hama dan penyakit untuk menambah variasi dataset.
- Meningkatkan efisiensi diagnosis dan mendukung pertanian berbasis teknologi (smart farming).

---

## 📊 Hasil Pelatihan Model

- Model menunjukkan performa pelatihan yang sangat baik dengan tren akurasi meningkat dan loss menurun stabil.

![Cuplikan layar 2025-06-08 073144](https://github.com/user-attachments/assets/7d87b352-c987-4568-8e24-9f7d0bc600d4)

## 📷 Hasil Inference

- Model mampu mengidentifikasi jenis hama/penyakit dengan tingkat kepercayaan sangat tinggi:

![Cuplikan layar 2025-06-08 073105](https://github.com/user-attachments/assets/7d7eb93e-8698-48e0-b36a-324156c18abb)

![Cuplikan layar 2025-06-08 073119](https://github.com/user-attachments/assets/b231242e-1f06-4848-8442-a40f7f3681df)

---

## 🧪 Fitur Notebook

- Visualisasi dan eksplorasi dataset
- Preprocessing gambar dan augmentasi
- Pelatihan dan evaluasi model CNN
- Visualisasi performa model
- Prediksi gambar uji dan penyimpanan model
- Inference Model

---

## 🔧 Cara Menggunakan

1. Clone repositori atau unduh `.zip` lalu ekstrak.
2. Buka file `.ipynb` di Google Colab.
3. Jalankan semua sel secara berurutan.
4. Unduh dataset dan jalankan proses pelatihan model.
5. Simpan model akhir dalam format `.h5`.

---

## 📚 Citation

> “Paddy Doctor, Pandarasamy Arjunan (Samy), and Petchiammal. Paddy Doctor: Paddy Disease Classification. https://kaggle.com/competitions/paddy-disease-classification, 2022. Kaggle.”

