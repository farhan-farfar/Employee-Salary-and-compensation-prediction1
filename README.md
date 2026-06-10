# Employee-Salary-and-compensation-prediction

# Employee Salary Prediction and Compensation Analysis

## 📌 Deskripsi Proyek

Employee Salary Prediction and Compensation Analysis merupakan aplikasi berbasis **Data Mining** yang dikembangkan untuk menganalisis faktor-faktor yang memengaruhi gaji karyawan serta melakukan prediksi salary menggunakan teknik Machine Learning.

Proyek ini dikembangkan sebagai tugas **Ujian Akhir Semester (UAS) Data Mining** dengan menerapkan framework **CRISP-DM (Cross Industry Standard Process for Data Mining)**.

Selain melakukan prediksi gaji menggunakan metode **Linear Regression**, proyek ini juga menerapkan **K-Means Clustering** untuk melakukan segmentasi karyawan berdasarkan karakteristik kompensasi dan pengalaman kerja.

---

## 🎯 Tujuan Proyek

Tujuan dari proyek ini adalah:

* Menganalisis hubungan antara karakteristik karyawan dan besaran gaji.
* Memprediksi gaji karyawan berdasarkan atribut tertentu.
* Melakukan segmentasi karyawan menggunakan metode clustering.
* Mengimplementasikan model Machine Learning ke dalam aplikasi web berbasis Streamlit.
* Menyediakan dashboard analitik yang mudah digunakan dan interaktif.

---

## 📊 Dataset

Dataset yang digunakan:

**Employee Compensation and Salary Prediction Dataset**

Sumber Dataset:

https://www.kaggle.com/datasets/alitaqishah/employee-compensation-and-salary-prediction-dataset

Dataset berisi informasi terkait:

* Age
* Gender
* Education Level
* Job Title
* Years of Experience
* Annual Salary

---

## 🧠 Metode Data Mining

### 1. Linear Regression

Linear Regression digunakan untuk memprediksi nilai salary berdasarkan karakteristik karyawan.

Input yang digunakan:

* Age
* Gender
* Education Level
* Job Title
* Years of Experience

Output:

* Annual Salary Prediction

### 2. K-Means Clustering

K-Means digunakan untuk mengelompokkan karyawan berdasarkan karakteristik tertentu sehingga dapat diperoleh segmentasi karyawan.

Contoh segmentasi:

* Junior Employee
* Mid-Level Employee
* Senior Employee

---

## 🔄 Framework Penelitian

Penelitian ini menggunakan framework:

### CRISP-DM

Tahapan yang dilakukan:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment

---

## 🌐 Fitur Aplikasi

### 🏠 Home

Menampilkan:

* Informasi proyek
* Dataset
* Metode yang digunakan
* Anggota kelompok
* Link repository

### 📈 Dataset Overview

Menampilkan:

* Jumlah data
* Jumlah atribut
* Missing value
* Statistik salary
* Distribusi data
* Heatmap korelasi
* Visualisasi interaktif

### 💰 Salary Prediction

Menampilkan:

* Form input pengguna
* Prediksi salary menggunakan Linear Regression
* Kategori salary

Kategori salary:

* Entry Level
* Mid Level
* Senior Level

### 👥 Employee Segmentation

Menampilkan:

* Hasil clustering menggunakan K-Means
* Visualisasi cluster
* Karakteristik setiap cluster

---

## 🛠️ Teknologi yang Digunakan

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Plotly
* Joblib

---

## 📂 Struktur Folder

```text
Employee-Salary-and-compensation-prediction1
│
├── app.py
├── home.py
├── dataset_overview.py
├── salary_prediction.py
├── employee_segmentation.py
│
├── model
│   ├── linear_regression_model.pkl
│   ├── kmeans_model.pkl
│   └── encoder.pkl
│
├── assets
│   ├── anggota1.jpg
│   ├── anggota2.jpg
│   └── logo.png
│
├── salary.csv
├── requirements.txt
└── README.md
```

---

## 🚀 Cara Menjalankan Proyek

### 1. Clone Repository

```bash
git clone https://github.com/farhan-farfar/Employee-Salary-and-compensation-prediction1.git
```

### 2. Masuk ke Folder Project

```bash
cd Employee-Salary-and-compensation-prediction1
```

### 3. Install Dependency

```bash
pip install -r requirements.txt
```

### 4. Jalankan Streamlit

```bash
streamlit run app.py
```

---

## ☁️ Deployment

Aplikasi dapat dijalankan secara online menggunakan:

* Streamlit Community Cloud

Link deployment:

Tambahkan URL deployment setelah aplikasi berhasil di-deploy.

---

## 📈 Evaluasi Model

### Linear Regression

Metode evaluasi:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

### K-Means Clustering

Metode evaluasi:

* Silhouette Score

---

## 👨‍💻 Tim Pengembang

### Anggota 1

Nama:
Farhan Putra Pratama

Universitas:
Universitas Negeri Surabaya

Program Studi:
Sistem Informasi

### Anggota 2

Nama:
Muhammad Ali Mukahfi

Universitas:
Universitas Negeri Surabaya

Program Studi:
Sistem Informasi

---

## 📚 Referensi

* Han, J., Kamber, M., & Pei, J. (2022). Data Mining: Concepts and Techniques.
* Witten, I. H., Frank, E., Hall, M. A., & Pal, C. J. (2023). Data Mining: Practical Machine Learning Tools and Techniques.
* Scikit-Learn Documentation.
* Streamlit Documentation.
* Kaggle Dataset Repository.

---

## 📄 Lisensi

Proyek ini dibuat untuk keperluan akademik dan pembelajaran pada mata kuliah Data Mining.
