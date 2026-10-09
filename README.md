#Data Acquisition and Management
# Data Acquisition and Management

## Informasi Proyek

* **Mata Kuliah:** Akuisisi dan Manajemen Data
* **Kode Mata Kuliah:** BIFP-243
* **Topik:** Data Acquisition Lifecycle
* **Bahasa Pemrograman:** Python

## Deskripsi

Proyek ini mendokumentasikan tahapan siklus hidup data, mulai dari akuisisi, penyimpanan, pembersihan, transformasi, analisis, hingga penyampaian hasil. Dokumentasi mencakup tools yang dapat digunakan dan risiko yang perlu diperhatikan pada setiap tahap.

## Struktur Folder

```text
proyek_data_akuisisi/
├── data/
│   ├── raw/          # Data asli, tidak diubah
│   ├── interim/      # Data sementara
│   └── processed/    # Data yang sudah diproses
├── notebooks/        # Notebook analisis
├── src/              # Source code
├── docs/             # Dokumentasi
├── reports/          # Laporan dan hasil analisis
└── README.md
```

## Tools

* Python
* pandas
* NumPy
* Requests
* Beautiful Soup
* Git dan GitHub
* Google Colab

## Reproducibility

Proyek ini disusun agar tahapan pengelolaan data dapat ditelusuri dan diulang. Data mentah disimpan terpisah dari data sementara dan data hasil pemrosesan. Kode, dokumentasi, serta notebook ditempatkan pada direktori masing-masing agar struktur proyek konsisten. Versi Python dan pustaka yang digunakan perlu dicatat untuk membantu proses reproduksi. Sebelum menjalankan notebook, pastikan dependensi yang dibutuhkan telah tersedia dan sumber data yang digunakan dapat diakses. Setiap perubahan kode dan dokumentasi dicatat menggunakan Git agar riwayat pekerjaan dapat diperiksa kembali.

## Catatan

Folder `data/raw/` digunakan untuk menyimpan data asli dan sebaiknya tidak diubah secara langsung.
