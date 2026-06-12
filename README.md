# Eksperimen Operasi Dasar pada Sinyal dan Citra

Repository ini dibuat untuk memenuhi Tugas Individu mata kuliah **Pengolahan Sinyal Digital**. Proyek ini berfokus pada implementasi praktis dan analisis teoritis mengenai operasi dasar matematika yang diterapkan pada domain sinyal 1D (audio/gelombang) dan citra 2D (gambar).

## Cakupan Praktikum
Proyek ini dibagi menjadi beberapa bagian utama:
* **Bagian A: Operasi Sinyal 1D** – Penjumlahan sinyal, amplifikasi (perkalian skalar), dan penggeseran waktu (*time shifting* / *delay*).
* **Bagian B: Operasi Citra 2D** – Penjumlahan dua gambar (*image blending*), translasi objek, dan manipulasi tingkat kecerahan (*brightness/contrast*) lewat histogram.
* **Bagian C: Uji Sistem Linier** – Pembuktian matematis dan komputasi terhadap sifat homogenitas serta additivitas menggunakan model sistem $T(x) = 2x$ dan $T(x) = x^2$.
* **Bagian D: Analisis & Studi Kasus** – Pembahasan mendalam mengenai *image blending*, risiko *audio clipping*, serta augmentasi data untuk AI.

## Teknologi & Library yang Digunakan
* **Bahasa Pemrograman:** Python 3
* **Lingkungan Kerja:** Google Colab / Jupyter Notebook
* **Library Utama:**
  * `NumPy` – Untuk manipulasi array tingkat tinggi dan komputasi matriks.
  * `Matplotlib` – Untuk visualisasi grafik sinyal 1D dan plot histogram citra.
  * `OpenCV` (cv2) – Untuk pemrosesan gambar dan transformasi spasial citra 2D.

## Struktur File
* `OPERASI_DASAR_SISTEM_SINYAL_DAN_CITRA.pdf` - Dokumen laporan lengkap hasil analisis teori dan kesimpulan.
* `Operasi_sinyal_dan_citra.ipynb` - *Source code* Google Colab yang berisi seluruh program praktikum.

---
*Dibuat oleh Zharifah Zahra Salsabila - NIM 452024618106*


