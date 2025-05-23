# final-project-machine-learning-for-gdgoc-member-2025

## 🌿 Final Project Machine Learning GDGoC Unesa - Plant Disease Image Classification

Proyek ini bertujuan untuk mengasah pemahaman kalian dalam membangun model klasifikasi citra menggunakan model deep learning, serta memahami alur kerja Machine Learning dari preprocessing hingga evaluasi model.

---

## 📌 Deskripsi Proyek

Kamu diminta untuk membangun sebuah **model klasifikasi gambar daun sehat dan sakit** menggunakan dataset *PlantVillage*, kemudian pilih salah satu jenis tanaman. Model ini akan mampu mengidentifikasi jenis penyakit pada daun dari gambar yang diberikan.

---

## 🎯 Tujuan Pembelajaran

- Memahami alur kerja proyek machine learning end-to-end
- Menggunakan **Deep Learning** untuk klasifikasi gambar
- Mengimplementasikan augmentasi data dan evaluasi model
- Membuat prediksi gambar baru menggunakan model yang dilatih
- Men-deploy model sederhana (opsional)

---

## 🗂️ Langkah-langkah Minimum yang Harus Dilakukan

1. **Persiapan Dataset**
   - Download dataset dari Kaggle
   - Pilih subset tanaman tertentu (misalnya: `Tomato`)
   - Lakukan eksplorasi data

2. **Preprocessing & Augmentasi**
   - Resize gambar ke ukuran seragam (misal: 224x224)
   - Lakukan augmentasi (flip, rotation, zoom, dsb.)

3. **Modeling**
   - Gunakan model Deep Learning dengan library seperti `Tensorflow`, `Keras`, `PyTourch`
   - Diperbolehkan menggunakan model pre-trained seperti `MobileNetV2`, `ResNet50`, atau `EfficientNet`  tetapi harus di training ulang
   - evaluasi dengan metrik akurasi dan confusion matrix

4. **Prediksi**
   - Uji model dengan gambar baru
   - Buat fungsi `predict_image()` untuk klasifikasi manual

5. **(Opsional) Visualisasi / Deployment**
   - Streamlit/Gradio interface untuk demo model

---

## 🧰 Teknologi yang Digunakan

- Python (Jupyter Notebook / Google Colab)
- TensorFlow, Keras, atau PyTorch
- Scikit-Learn & Matplotlib
- Kaggle Dataset: [PlantVillage](https://www.kaggle.com/datasets/emmarex/plantdisease)
- (Opsional) Streamlit atau Gradio untuk demo

---

## 🔗 Referensi & Resources

- [Kaggle PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)
- [TensorFlow Transfer Learning Guide](https://www.tensorflow.org/tutorials/images/transfer_learning)
- [Image Classification with TensorFlow](https://www.tensorflow.org/tutorials/images/classification)
- [Streamlit Docs](https://docs.streamlit.io/)
- [Gradio Docs](https://www.gradio.app/guides)

---

## 📁 Struktur Folder yang diwajibkan
```
├── dataset/
│ └── Tomato/...
├── notebooks/
│ └── EDA.ipynb
│ └── training.ipynb
├── model/
│ └── final_model.keras/.h5
├── app (optional)/
│ └── streamlit_app.py (opsional)
├── README.md
```
---

## ✅ Kriteria Penilaian

| Kriteria                        | Bobot | Keterangan |
|--------------------------------|--------|------------|
| Preprocessing & EDA            | 20%    | Pemahaman terhadap struktur dan kualitas data |
| Implementasi Deep Learning     | 25%    | Penggunaan model pre-trained secara tepat |
| Evaluasi & Interpretasi Model  | 25%    | Akurasi, confusion matrix, klasifikasi yang benar |
| Visualisasi / Deployment       | 20%    | Interface demo sederhana (Streamlit/Gradio) |
| Struktur kode & dokumentasi    | 10%    | Rapi, jelas, dan dapat dijalankan ulang |

**Total Nilai: 100%**

---

## 🌱 Selamat Mengerjakan!

Gunakan waktu kalian sebaik mungkin, kerjakan secara bertahap, dan pastikan setiap bagian bisa dijelaskan secara logis dan runtut.  
Proyek ini bisa kamu gunakan sebagai portofolio untuk karier atau showcase ML pertamamu!
