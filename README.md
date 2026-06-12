# Praktikum Manipulasi Citra Digital menggunakan OpenCV

* **Nama:** Zharifah Zahra Salsabila
* **NIM:** 452024618196


## Deskripsi Singkat Project
Project ini merupakan implementasi prapemrosesan dan manipulasi piksel dasar pada citra digital menggunakan pustaka OpenCV dan Python. Eksperimen ini mencakup perbaikan representasi warna (BGR ke RGB), penyelarasan dimensi gambar melalui teknik interpolasi geometri, operasi aritmatika linear berbobot, hingga transformasi non-linear (logaritmik dan gamma) untuk koreksi pencahayaan (exposure).

## Citra yang Digunakan
Project ini menggunakan dua buah citra bertipe data `uint8` berformat `.jpg` sebagai input utama:
1. **`images/img1.jpg`**: Citra utama berukuran $(490 \times 735 \times 3)$ piksel yang digunakan sebagai objek dasar visualisasi dan transformasi non-linear.
2. **`images/img2.webp`**: Citra kedua yang digunakan sebagai pasangan dalam eksperimen penggabungan gambar (*image blending*).

## Library yang Digunakan
Eksperimen ini bergantung pada beberapa pustaka (*libraries*) Python berikut:
* **`opencv-python` (OpenCV)**: Untuk operasi membaca, mengonversi ruang warna, meresize, dan manipulasi matriks citra.
* **`numpy`**: Untuk komputasi array numerik tingkat tinggi (seperti konversi tipe data ke `float64` dan pencegahan *integer overflow*).
* **`matplotlib`**: Untuk visualisasi plot citra, perbandingan multi-jendela, dan analisis grafik histogram.
* **`python-docx`**: Untuk pembuatan dokumen laporan otomatis langsung dari lingkungan pemrograman.

## Cara Menjalankan Notebook
**Persiapan Folder:** Pastikan semua file tugas (`.ipynb`, file gambar, dan `requirements.txt`) berada dalam satu folder yang sama.
**Eksekusi Kode:** Buka file 

