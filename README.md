# Machine-Learning

# 📊 Tugas 1 – Data Preprocessing Machine Learning

Repository ini berisi implementasi tahapan **data preprocessing** menggunakan Python pada dataset mahasiswa. Proses ini merupakan langkah awal yang sangat penting sebelum membangun model machine learning.

---

## 🎯 Tujuan

Melakukan pembersihan dan persiapan data agar siap digunakan dalam proses machine learning, meliputi:

* menangani missing value
* normalisasi format data
* encoding data kategorikal
* pembagian data (training & testing)
* visualisasi data

---

## ⚙️ Tools & Library

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Google Colab

---

## 🔍 Tahapan Pengerjaan

### 1. Load Dataset

Membaca dataset dari file Excel ke dalam DataFrame menggunakan pandas.

---

### 2. Exploratory Data Analysis (EDA)

* Melihat struktur data (`info()`)
* Mengecek missing value
* Menampilkan statistik deskriptif

---

### 3. Menangani Missing Values

* `Nilai_Akhir` → diisi menggunakan **modus (mode)**
* `Umur` → diisi menggunakan **mean**

---

### 4. Normalisasi Format Tanggal

Kolom `Tanggal_Ujian` dikonversi menjadi format `datetime`.

---

### 5. Label Encoding

Mengubah data kategorikal menjadi numerik.

Contoh mapping:

```
Jenis_Kelamin:
0 = Laki-laki
1 = Perempuan
```

---

### 6. Split Data

Dataset dibagi menjadi:

* 80% data training
* 20% data testing

---

### 7. Visualisasi

* Histogram untuk distribusi umur
* Grafik batang untuk jumlah mahasiswa per program studi

---

## 📈 Insight Singkat

* Distribusi umur mahasiswa berada pada rentang sekitar 18–30 tahun
* Terdapat variasi jumlah mahasiswa pada setiap program studi
* Data berhasil dibersihkan dan siap digunakan untuk model machine learning

---

## 🚀 Cara Menjalankan

1. Clone repository:

```
git clone https://github.com/username/tugas-preprocessing-ml.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Jalankan notebook:

```
jupyter notebook
```

---

## 🧠 Catatan

* Proses preprocessing sangat penting untuk meningkatkan kualitas model machine learning
* Encoding dilakukan sesuai instruksi tugas meskipun dalam praktik nyata biasanya dilakukan setelah EDA

---

## 👤 Author

Nama: Muhammad Zidan,
Program Studi: (Data Science)

---

## ⭐ Penutup

Repository ini dibuat sebagai bagian dari pembelajaran **Machine Learning**, khususnya dalam memahami pentingnya preprocessing data sebelum tahap modeling.

---
