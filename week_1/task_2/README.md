# Klasifikasi Penyakit Jantung

## Ringkasan Proyek
Proyek ini berfokus pada analisis klasifikasi penyakit jantung menggunakan model machine learning. Dua pendekatan dilakukan, yaitu klasifikasi biner dan klasifikasi multikelas, dengan tujuan memprediksi kondisi kesehatan berdasarkan fitur pasien. Analisis dilakukan menggunakan Jupyter Notebook (`classification_heartdisease.ipynb` dan `classification_heartdisease_multiclass.ipynb`), dengan dataset `HeartDisease.csv`.

## Deskripsi Berkas
- **classification_heartdisease.ipynb**: Notebook yang berisi implementasi klasifikasi biner untuk mendeteksi keberadaan penyakit jantung.
- **classification_heartdisease_multiclass.ipynb**: Notebook yang berisi implementasi klasifikasi multikelas untuk mengklasifikasikan tingkat keparahan penyakit jantung.
- **HeartDisease.csv**: Dataset yang digunakan dalam proyek ini, berisi berbagai atribut pasien yang berhubungan dengan penyakit jantung.

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
   - Normalisasi dan encoding fitur
   - Pembagian dataset menjadi data latih dan data uji
2. **Analisis Eksploratori Data (EDA)**:
   - Memvisualisasikan distribusi data
   - Menganalisis korelasi antar fitur
3. **Implementasi Model Klasifikasi**:
   - Model yang digunakan: Logistic Regression, Decision Tree, Random Forest, SVM, dll.
   - Evaluasi kinerja model menggunakan metrik seperti akurasi, precision, recall, dan F1-score.

## Cara Menggunakan
1. Buka `classification_heartdisease.ipynb` atau `classification_heartdisease_multiclass.ipynb` di Jupyter Notebook.
2. Jalankan sel secara berurutan untuk melakukan preprocessing, eksplorasi data, dan pemodelan.
3. Tinjau hasil evaluasi dan analisis model.

## Hasil & Wawasan
- Proyek ini bertujuan untuk mengembangkan model machine learning yang dapat membantu mendeteksi penyakit jantung dengan akurasi tinggi.
- Model terbaik dipilih berdasarkan evaluasi metrik performa.

## Penulis
Muhammad Fitran Ramadhan - Mahasiswa Teknik Komputer, Telkom University

## Lisensi
Proyek ini dibuat untuk tujuan edukasi dan tidak memiliki lisensi khusus.

