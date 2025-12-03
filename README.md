PROJECT MACHINE LEARNING – Support Vector Machine (SVM)
Studi Kasus: Prediksi Kelulusan Mahasiswa
1.  Judul Proyek

Prediksi Kelulusan Mahasiswa Menggunakan Support Vector Machine (SVM)
(Supervised Classification Project)

2.  Deskripsi Singkat Proyek

Proyek ini bertujuan membangun model klasifikasi menggunakan algoritma Support Vector Machine (SVM) untuk memprediksi status kelulusan mahasiswa berdasarkan berbagai fitur akademik dan non-akademik.

Mahasiswa melakukan:

Eksplorasi dataset

Preprocessing data

Training model SVM (Linear & RBF)

Evaluasi performa model

Interpretasi hasil

Membuat fungsi prediksi sederhana

Mengupload notebook dan dataset ke GitHub

3.  Dataset

Nama file: datakelulusanmahasiswa.csv
Sumber dataset: Google Spreadsheet (disediakan dosen)

Contoh fitur (menyesuaikan dataset asli):

IPK

Total SKS

Umur

Status Kehadiran

Lama Studi

Keaktifan Organisasi

Nilai Mata Kuliah tertentu

Label: Lulus / Belum Lulus

Dataset dibaca menggunakan pandas, kemudian dianalisis secara eksploratif.

4.  Instruksi Pengerjaan Proyek
Bagian A – Setup & Load Dataset (10 menit)

Import library (pandas, numpy, sklearn)

Load dataset

Tampilkan 5 baris awal

Identifikasi fitur dan label

Cek missing values

Bagian B – Exploratory Data Analysis (15 menit)

Minimal mencakup:

Statistik deskriptif

Histogram IPK

Countplot Lulus vs Tidak Lulus

Analisis pertanyaan seperti:

Apakah IPK memengaruhi kelulusan?

Fitur apa yang tampak paling berpengaruh?

Bagian C – Preprocessing Data (15 menit)

Menangani missing values

Encoding data kategorikal (OneHot / Label Encoding)

Scaling menggunakan StandardScaler

Train-test split rasio 60:40, 75:25, 80:20, 90:10

Bagian D – Training Model SVM (25 menit)

Latih dua model:

SVM Linear

SVM RBF

Hyperparameter tuning:

C: 0.1, 1, 10

Gamma: scale, 0.1, 1

Kernel: linear, rbf

Evaluasi model:

Confusion Matrix

Classification Report

Akurasi

Precision, Recall, F1-score

Pertanyaan analitis:

Model mana yang lebih baik?

Dampak nilai C terhadap decision boundary?

Apakah dataset linearly separable?

Bagian E – Model Interpretation (10 menit)

Jelaskan fitur paling berpengaruh

Apakah IPK rendah mengarah ke prediksi tidak lulus?

Kesimpulan akhir

Bagian F – Deployment Sederhana (5 menit)

Membuat fungsi:

predict_status(ipk, sks, umur, lamastudi, ...)


Fungsi harus menghasilkan prediksi Lulus atau Tidak Lulus berdasarkan model final.

Bagian G – Dokumentasi & Upload GitHub (10 menit)

Upload ke GitHub:

Notebook: SVM_kelulusan.ipynb

Folder /data berisi dataset

README.md (dokumen ini)

Screenshot hasil prediksi

Link GitHub dikumpulkan ke Edlink

5.  Rubrik Penilaian
Komponen	Bobot
Exploratory Analysis	15%
Preprocessing & Feature Scaling	20%
Pembangunan Model SVM	25%
Evaluasi & Interpretasi	20%
Dokumentasi & GitHub	20%
6.  Deliverables (Wajib)

SVM_kelulusan.ipynb

datakelulusanmahasiswa.csv

README.md

Screenshot hasil prediksi

Link repository GitHub

7.  Identitas Mahasiswa

Nama:Lailatul Rahmadani
NPM:2457201002373
Program Studi: Sistem Informasi
Universitas: UNDA
