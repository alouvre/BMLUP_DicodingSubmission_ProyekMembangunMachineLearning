## Deskripsi Proyek

Proyek ini merupakan tugas akhir dari kelas Belajar Machine Learning Untuk Pemula di Dicoding. Dalam proyek ini, saya melakukan analisis data dengan metode *clustering* serta membangun model *classification* berdasarkan hasil klasterisasi yang telah dilakukan. Dataset yang digunakan adalah dataset mengenai pola penjualan dalam industri minuman yang didapat dari Kaggle : https://www.kaggle.com/datasets/sebastianwillmann/beverage-sales/data

Proyek ini sedang dalam tahap penilaian.

## Struktur Repository

- `[Clustering] Submission Akhir BMLP_Alifia Mustika.ipynb` : Notebook yang berisi proses *clustering* pada dataset.
- `[Klasifikasi] Submission Akhir BMLP_Alifia Mustika.ipynb` : Notebook yang berisi proses *classification* menggunakan 3 Algoritma berdasarkan hasil klasterisasi.

## Hasil dan Evaluasi

![image](https://github.com/user-attachments/assets/09a354ea-dade-4561-b127-42a2689a9291)


### Model Clustering
Model akhir didapat menggunakan metode KMeans dengan **silhouette score** = 0.9935.

## Penilaian

Submission Anda akan dinilai oleh reviewer dengan skala 1–5 berdasarkan dari parameter yang ada. Anda dapat menerapkan beberapa saran untuk mendapatkan nilai tinggi. Berikut sarannya.

1. Menggunakan dataset dengan **minimal 2500 baris**.
2. Menggunakan **minimal 5 fitur** untuk proses clustering dengan **campuran numerikal dan kategorikal**.
3. **Menerapkan feature selection** pada tahap clustering untuk memilih fitur terbaik dan membandingkan silhoutte score dengan sebelum menggunakan feature selection.
4. Evaluasi akhir pada clustering harus mencapai **nilai silhouette score minimal 0.70**.
5. Mengimplementasikan **2 algoritma klasifikasi** yang berbeda untuk membandingkan performa model.
6. Meningkatkan **akurasi dan F1-Score** pada **training serta testing** set **minimal 92%**.

Berikut adalah detail penilaian submission:

&starf;&star;&star;&star;&star; : Semua kriteria utama terpenuhi, tetapi penulisan kode masih perlu banyak diperbaiki atau terindikasi melakukan plagiat.

&starf;&starf;&star;&star;&star; : Semua kriteria utama terpenuhi, tetapi penulisan kode masih perlu diperbaiki.

&starf;&starf;&starf;&star;&star; : Semua kriteria utama terpenuhi, tetapi tidak terdapat saran yang terpenuhi.

&starf;&starf;&starf;&starf;&star; : Semua kriteria utama terpenuhi dan menerapkan minimal 3 dari seluruh saran yang ada di atas.

&starf;&starf;&starf;&starf;&starf; : Semua kriteria utama terpenuhi dan menerapkan semua saran yang ada di atas.

## Submission yang Tidak Sesuai Kriteria

- **Tidak melampirkan file** yang diminta pada ketentuan berkas submission.
- **Tidak menggunakan template** yang disediakan.
- **Memasukan kolom ID** untuk dimasukan ke dalam data training.
- Tidak menampilkan/memiliki nilai **silhouette score**.
- **Tidak memberikan penjelasan** mengenai hasil clustering.
- Tidak menggunakan **dataset dan label dari hasil clustering**.
- Model klasifikasi **tidak menampilkan akurasi dan F1-Score pada training set serta testing set**.
- Tidak diperbolehkan menggunakan platform atau metode **AutoML**, seperti berikut.
    - PyCaret
    - Auto-sklearn
    - Google Cloud AutoML 
    - H2O Driverless AI (dari H2O.ai)
    - Microsoft Azure Automated Machine Learning
    - TPOT (Tree-based Pipeline Optimization Tool)
    - DataRobot
    - RapidMiner Auto Model
    - Amazon SageMaker Autopilot
    - IBM Watson AutoAI
