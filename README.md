# 🐾 Proyek Klasifikasi Wajah Hewan (Animal Faces)

Proyek ini bertujuan untuk melakukan klasifikasi gambar wajah hewan menggunakan teknik Deep Learning. Dataset yang digunakan difokuskan pada tiga kategori utama: Kucing, Anjing, dan Satwa Liar.

## 📊 Sumber Dataset

Dataset yang digunakan dalam proyek ini berasal dari **Kaggle** yang disusun oleh Andrew MVD.

* **Nama Dataset:** Animal Faces
* **Penyusun:** Andrew MVD
* **Link Sumber:** [https://www.kaggle.com/datasets/andrewmvd/animal-faces](https://www.kaggle.com/datasets/andrewmvd/animal-faces)

### Informasi Dataset:
Dataset ini terdiri dari gambar berkualitas tinggi (512x512 piksel) yang dikategorikan ke dalam 3 kelas:
1.  **Cat** (Kucing)
2.  **Dog** (Anjing)
3.  **Wildlife** (Satwa Liar)

Total terdapat kurang lebih 16.130 gambar yang telah dipisahkan ke dalam folder `train` dan `val` untuk mempermudah proses pelatihan model.

## 🛠️ Metodologi
Proyek ini menggunakan library **Keras/TensorFlow** dengan beberapa teknik optimasi seperti:
* `ReduceLROnPlateau` untuk penyesuaian learning rate otomatis.
* `EarlyStopping` untuk mencegah overfitting.
* `Class Weights` untuk menangani ketidakseimbangan data jika ada.

## 📜 Lisensi & Atribusi
Dataset ini disediakan di bawah lisensi publik yang tercantum pada halaman Kaggle penyedia. Harap merujuk pada link sumber di atas jika ingin menggunakan dataset ini untuk keperluan riset atau publikasi lainnya.

