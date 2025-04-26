# Baseline Time Series Regression Project

Proyek ini merupakan implementasi prediksi regresi pada data time series untuk memodelkan nilai **% Baseline** berdasarkan beberapa fitur cuaca dan solar irradiance. Proyek ini mencakup preprocessing data, imputasi missing value, scaling, model regresi, dan pembuatan file submission.

## Struktur Direktori

```
.
├── data/                 # Folder berisi data (train, test, weather, solar, dll)
├── notebooks/            # Jupyter notebooks untuk eksplorasi dan modeling
├── outputs/              # Folder hasil submission dan visualisasi
├── requirements.txt      # Daftar dependensi proyek
├── README.md             # File ini
└── main.py               # (Jika ada) script utama untuk menjalankan pipeline
```

## Fitur Utama

- Preprocessing data time series
- Imputasi nilai hilang menggunakan `SimpleImputer` dan `KNNImputer`
- One-Hot Encoding kolom kategorikal
- Standarisasi data
- Pelatihan model regresi (Linear Regression, Random Forest, dll.)
- Evaluasi model dan visualisasi performa
- Pembuatan file submission sesuai format

## Cara Menjalankan

1. **Clone repository ini**

```bash
git clone <URL_REPO_KAMU>
cd nama-folder-repo
```

2. **Install dependensi**

```bash
pip install -r requirements.txt
```

3. **Jalankan script atau notebook**

Gunakan Jupyter Notebook atau jalankan script `main.py` jika disediakan.

## Dependencies

Lihat `requirements.txt` untuk daftar lengkap pustaka yang digunakan.

## Catatan

- Pastikan semua kolom waktu telah dikonversi ke format datetime sebelum merge antar dataset.
- Data memiliki format time series dari jam 6 pagi sampai 6 sore.
- Model disusun untuk menyimpan hasil prediksi per model dalam format submission (berisi `Timestamp` dan `Baseline`).

## Lisensi

Proyek ini bebas digunakan untuk keperluan edukasi dan non-komersial.