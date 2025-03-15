# Analisis Regresi pada Data Automobile

## Ringkasan Proyek
Proyek ini berfokus pada analisis regresi terhadap data otomotif untuk memprediksi atribut yang relevan berdasarkan fitur yang diberikan. Analisis dilakukan menggunakan Jupyter Notebook (`regresion_automobile.ipynb`), dengan dataset `Automobile.csv`.

## Deskripsi Berkas
- **regresion_automobile.ipynb**: Jupyter Notebook yang berisi preprocessing data, analisis eksploratori data (EDA), seleksi fitur, pelatihan model, dan evaluasi model regresi.
- **Automobile.csv**: Dataset yang digunakan untuk analisis regresi, berisi berbagai atribut terkait kendaraan.

## Persyaratan
Untuk menjalankan proyek ini, pastikan Anda memiliki dependensi berikut:
- Python (>=3.7)
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

Anda dapat menginstal pustaka yang diperlukan dengan perintah:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Struktur Proyek
1. **Preprocessing Data**:
   - Menangani nilai yang hilang
   - Pembersihan dan transformasi data
   - Encoding fitur
2. **Analisis Eksploratori Data (EDA)**:
   - Memvisualisasikan hubungan antar fitur
   - Mengidentifikasi korelasi
3. **Implementasi Model Regresi**:
   - Membagi data menjadi set pelatihan dan pengujian
   - Menerapkan model regresi (misalnya, Regresi Linear, Decision Tree, Random Forest, dll.)
   - Mengevaluasi kinerja model menggunakan metrik seperti RMSE, MAE, dan R²

## Cara Menggunakan
1. Buka `regresion_automobile.ipynb` di Jupyter Notebook.
2. Jalankan sel secara berurutan untuk menjalankan preprocessing data, analisis, dan pemodelan.
3. Tinjau output dan evaluasi kinerja model.

## Hasil & Wawasan
- Proyek ini bertujuan untuk menemukan model regresi terbaik dalam memprediksi atribut kendaraan.
- Metrik evaluasi kinerja digunakan untuk membandingkan berbagai model dan memilih yang paling akurat.

## Penulis
Muhammad Fitran Ramadhan - Mahasiswa Teknik Komputer, Telkom University

## Lisensi
Proyek ini dibuat untuk tujuan edukasi dan tidak memiliki lisensi khusus.
