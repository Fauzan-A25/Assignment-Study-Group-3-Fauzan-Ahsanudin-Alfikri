## Deskripsi Proyek

Proyek ini berisi analisis data harga saham untuk perusahaan-perusahaan teknologi, termasuk AMD, NVIDIA, Intel, ASUS, dan MSI. Data yang digunakan mencakup informasi harga saham harian, termasuk harga pembukaan, harga tertinggi, harga terendah, harga penutupan, harga penutupan yang disesuaikan, dan volume perdagangan.

## Sumber Data

Data diambil dari Kaggle dan dapat diakses melalui tautan berikut: Kaggle Dataset.

## Struktur Data

Dataset ini terdiri dari 316 entri dengan kolom-kolom berikut:

- **Date**: Tanggal data.
- **Open**: Harga pembukaan saham.
- **High**: Harga tertinggi saham.
- **Low**: Harga terendah saham.
- **Close**: Harga penutupan saham.
- **Adj Close**: Harga penutupan yang disesuaikan.
- **Volume**: Jumlah saham yang diperdagangkan.

## Analisis

Analisis yang dilakukan mencakup:

- **Matriks Korelasi**: Mengidentifikasi hubungan antara variabel harga dan volume.
- **Distribusi Variabel**: Memvisualisasikan distribusi harga dan volume menggunakan histogram.
- **Boxplot**: Menganalisis outlier dalam data volume perdagangan.

## Prerequisites

Sebelum menjalankan analisis, pastikan Anda memiliki:

- Python (Disarankan Versi Terbaru)
- Pandas
- Matplotlib
- Seaborn

## Cara Menggunakan

1. Clone repositori ini ke mesin lokal Anda.
2. Install dependensi yang diperlukan.
3. Jalankan skrip analisis untuk melihat hasil analisis data.
