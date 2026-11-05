
# UTS Data Mining – Klasifikasi Wine Quality

## 1. Deskripsi Proyek

Proyek ini merupakan tugas Ujian Tengah Semester (UTS) mata kuliah Data Mining. Penelitian ini bertujuan untuk melakukan klasifikasi kualitas anggur (*Wine Quality*) menggunakan metode *Machine Learning* berdasarkan beberapa atribut atau karakteristik anggur.

Model klasifikasi dilatih menggunakan data training, kemudian digunakan untuk memprediksi kualitas anggur pada data testing.

## 2. Dataset

Dataset yang digunakan terdiri dari tiga file utama:

- `data_training.csv`: Data yang digunakan untuk melatih model.
- `data_testing.csv`: Data yang digunakan untuk melakukan prediksi.
- `hasilprediksi_3digitNIMterakhir.csv`: Template hasil prediksi.

Jumlah data:
- Data training: 857 baris.
- Data testing: 286 baris.

## 3. Metode yang Digunakan

Beberapa algoritma Machine Learning yang digunakan dalam proses klasifikasi adalah:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Random Forest
4. Gradient Boosting

## 4. Tahapan Pengerjaan

Tahapan pengerjaan proyek meliputi:

1. Import library yang dibutuhkan.
2. Membaca dataset training dan testing.
3. Melakukan pemeriksaan dan pemahaman data.
4. Melakukan Exploratory Data Analysis (EDA).
5. Melakukan preprocessing data.
6. Membagi data training menjadi data latih dan validasi.
7. Melatih beberapa model klasifikasi.
8. Melakukan evaluasi model menggunakan Accuracy dan Macro F1-Score.
9. Memilih model terbaik.
10. Melakukan prediksi terhadap data testing.
11. Menyimpan hasil prediksi dalam format CSV.

## 5. Hasil Prediksi

Hasil prediksi disimpan dalam format CSV dengan dua kolom saja, yaitu:

- `Id`: ID untuk mengidentifikasi setiap data sesuai dengan data testing.
- `Quality`: Hasil prediksi kualitas anggur.

## 6. Tools dan Library

Tools dan library yang digunakan:

- Python
- Google Colab
- GitHub
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## 7. File Repository

Repository ini berisi dataset, notebook pengerjaan, dan file hasil prediksi untuk tugas UTS Data Mining.
