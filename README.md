# Klasifikasi Bunga dengan CNN

Proyek ini merupakan implementasi **Convolutional Neural Network (CNN)** untuk mengklasifikasikan jenis bunga berdasarkan citra gambar. Proyek dibuat dengan mengikuti tutorial YouTube “[Flower Classification Project in Python Deep Learning Neural Network](https://www.youtube.com/watch?v=h6TJiGrYINk)”.

## 📋 Latar Belakang

Klasifikasi bunga adalah salah satu studi kasus populer dalam bidang *computer vision* dan *deep learning*. Dengan memanfaatkan CNN, komputer dapat mengenali pola visual pada gambar bunga sehingga mampu membedakan jenis bunga tertentu secara otomatis.

## 🧠 Tujuan Proyek

* Membangun model CNN yang mampu mengenali beberapa jenis bunga.
* Menerapkan teknik *data preprocessing* dan *data augmentation*.
* Melatih serta mengevaluasi performa model menggunakan dataset citra bunga.
* Menyediakan modul prediksi untuk gambar baru.

## 🛠 Teknologi yang Digunakan

* **Python** (3.10 atau lebih baru)
* **TensorFlow / Keras**
* **NumPy, Pandas, Matplotlib**
* **Streamlit
* **PIL / OpenCV** untuk manipulasi gambar
* **Scikit-learn** (opsional, untuk evaluasi)
* **Jupyter Notebook*

## 📌 Langkah Implementasi

1. **Persiapan Dataset**

   * Unduh dataset bunga (https://drive.google.com/file/d/1WUX0JJ9bTPgcPXlP_iDYqLhy8m2j7buk/view?usp=sharing).
   * Atur folder menjadi 5 kelas.
   * Terapkan augmentasi (rotasi, zoom, flipping, dsb).

2. **Membangun Model CNN**

   * Susun layer Conv2D, MaxPooling, Flatten, dan Dense.
   * Gunakan aktivasi ReLU dan softmax pada output.
   * Tambahkan Dropout untuk mengurangi overfitting.

3. **Melatih Model**

   * Kompilasi dengan optimizer Adam, loss categorical_crossentropy.
   * Latih model selama beberapa epoch dengan batch size tertentu.
   * Pantau akurasi dan loss di data training dan validasi.

4. **Evaluasi & Visualisasi**

   * Uji model pada data test.
   * Tampilkan confusion matrix dan grafik akurasi/loss.

5. **Prediksi Gambar Baru**

   * Lakukan preprocessing (resize, normalisasi).
   * Prediksi jenis bunga dengan model terlatih.
   * Tampilkan hasil prediksi (label dan probabilitas).

## 🎯 Hasil yang Diharapkan

* Model mampu mencapai akurasi tinggi pada data validasi/test.
* Kode dapat diperluas untuk eksperimen lebih lanjut (misalnya *transfer learning* atau integrasi ke aplikasi web/mobile).

## 🚀 Cara Menjalankan Proyek

1. Clone repo:

   ```bash
   git clone [https://github.com/username/flower-classification-cn](https://github.com/nelasamosir/flower-image-classfication-app.git
   cd flower-image-classfication-app
   ```

2. Siapkan dataset. Link Dataset : https://drive.google.com/file/d/1WUX0JJ9bTPgcPXlP_iDYqLhy8m2j7buk/view?usp=sharing

4. Jalankan pelatihan model file .ipynb dan simpan model.

5. Jalankan file app.py.

## 📚 Referensi

* Tutorial: [Flower Classification Project in Python Deep Learning Neural Network](https://www.youtube.com/watch?v=h6TJiGrYINk)
* Dokumentasi TensorFlow / Keras
* Artikel mengenai CNN & image classification

---

✍️ Dibuat sebagai proyek pembelajaran *Deep Learning* dan *Computer Vision*.
