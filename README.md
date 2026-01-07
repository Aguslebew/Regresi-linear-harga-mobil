# Regresi-linear-harga-mobil

Proyek ini bertujuan untuk memprediksi **harga mobil** berdasarkan beberapa fitur numerik menggunakan algoritma **Regresi Linear** dengan bantuan library **scikit-learn**.

---

##  Struktur Proyek

```
├── CarPrice_Assignment.csv          # Dataset harga mobil
├── regresi_linear_harga_mobil.ipynb # File Jupyter Notebook
└── README.md                        # Dokumentasi proyek
```

---

##  Dataset

- Nama dataset: `CarPrice_Assignment.csv`
- Target/label: `price`
- Jenis permasalahan: **Regresi**

Dataset berisi berbagai spesifikasi mobil dan harga jualnya.

---

##  Fitur yang Digunakan

Model menggunakan fitur numerik berikut:

- `wheelbase`
- `carlength`
- `carwidth`
- `carheight`
- `curbweight`
- `enginesize`
- `boreratio`
- `stroke`
- `compressionratio`
- `horsepower`
- `peakrpm`
- `citympg`
- `highwaympg`

Fitur-fitur tersebut dipilih karena memiliki pengaruh terhadap harga mobil.

---

##  Library yang Digunakan

Pastikan library berikut sudah terinstal:

```bash
pip install pandas scikit-learn
```

Library utama:
- `pandas`
- `scikit-learn`

---

##  Alur Pengerjaan

1. Membaca dataset menggunakan pandas
2. Memilih fitur numerik dan target harga
3. Membagi data menjadi data latih dan data uji (80:20)
4. Melatih model Regresi Linear
5. Melakukan prediksi pada data uji
6. Mengevaluasi model menggunakan MSE dan R²
7. Melakukan prediksi harga mobil baru

---

##  Evaluasi Model

Model dievaluasi menggunakan:

- **Mean Squared Error (MSE)** untuk mengukur kesalahan prediksi
- **R² Score** untuk mengetahui seberapa baik model menjelaskan variasi data

Nilai R² yang mendekati 1 menunjukkan performa model yang baik.

---

##  Contoh Prediksi

Model dapat digunakan untuk memprediksi harga sebuah mobil baru berdasarkan spesifikasi tertentu yang dimasukkan ke dalam model.

Output berupa estimasi **harga mobil**.

---

##  Kesimpulan

- Regresi Linear dapat digunakan untuk memprediksi harga mobil
- Pemilihan fitur numerik sangat memengaruhi hasil prediksi
- Model cukup baik untuk data dengan hubungan linier

---

## 👤 Penulis

Proyek ini dibuat sebagai latihan **Machine Learning – Regresi Linear** menggunakan Python dan scikit-learn.

✨ Semoga bermanfaat!

