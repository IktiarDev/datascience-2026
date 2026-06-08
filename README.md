# Portofolio Data Science - Pertemuan 1 s/d 7

Selamat datang di repository portofolio kuliah Pengantar Data Science saya. Repository ini saya buat untuk mendokumentasikan seluruh tugas, latihan praktis, pemrosesan data, hingga pemodelan regresi yang telah saya kerjakan dari Pertemuan 1 sampai Pertemuan 7.

## Identitas Penulis
* **Nama Lengkap**: Muhammad Ikctiar Saputra
* **NIM**: 250401020169
* **Kelas**: IF401
* **Program Studi**: PJJ Informatika
* **Instansi**: Universitas Siber Asia

---

## Deskripsi Singkat Repository
Halo! Saya Muhammad Ikctiar Saputra, mahasiswa Informatika PJJ di Universitas Siber Asia. Bagi saya, mempelajari Data Science sangat penting untuk menunjang karir dan pemahaman teknologi, terutama dalam mengolah data mentah menjadi informasi atau insight yang bermanfaat untuk bisnis dan teknologi. Lewat matakuliah ini, saya belajar mulai dari dasar pemrograman Python, pembersihan data (data wrangling), visualisasi data, preprocessing, hingga dasar machine learning.

Repository ini berisi kumpulan tugas mingguan saya yang mencakup alur kerja (workflow) Data Science dasar. Di sini, Anda bisa melihat latihan saya mulai dari sintaks dasar Python, eksplorasi data tips dan penguins, integrasi REST API, pembuatan visualisasi dashboard, preprocessing data (seperti scaling & encoding), sampai pembuatan model regresi linear sederhana untuk memprediksi harga mobil. Semuanya disusun dalam file Jupyter Notebook agar mudah dibaca dan dipelajari kembali.

---

## Daftar Pertemuan & Link Notebook

Berikut adalah daftar pertemuan dan link langsung menuju Jupyter Notebook masing-masing tugas:

| Pertemuan | Topik / Deskripsi Pembahasan | Link Akses Notebook |
| :--- | :--- | :--- |
| **Pertemuan 1** | Dasar Pemrograman Python (Variabel, Loop, List, Fungsi) | [Pertemuan1_Ikctiar_250401020169.ipynb](./Pertemuan1_Ikctiar_250401020169.ipynb) |
| **Pertemuan 2** | Eksplorasi Data Analitis (EDA) pada Dataset Tips | [Pertemuan2_Ikctiar_250401020169.ipynb](./Pertemuan2_Ikctiar_250401020169.ipynb) |
| **Pertemuan 3** | Pembersihan Data (Data Wrangling) & Integrasi REST API | [Pertemuan3_Ikctiar_250401020169.ipynb](./Pertemuan3_Ikctiar_250401020169.ipynb) |
| **Pertemuan 4** | Visualisasi Data Eksploratif pada Dataset Penguins | [Pertemuan4_Ikctiar_250401020169.ipynb](./Pertemuan4_Ikctiar_250401020169.ipynb) |
| **Pertemuan 5** | Dashboard Visualisasi Statis 2x2 Multi-subplot | [Pertemuan5_Ikctiar_250401020169.ipynb](./Pertemuan5_Ikctiar_250401020169.ipynb) |
| **Pertemuan 6** | Pra-pemrosesan Data (ML Preprocessing) pada Dataset Tips | [Pertemuan6_Ikctiar_250401020169.ipynb](./Pertemuan6_Ikctiar_250401020169.ipynb) |
| **Pertemuan 7** | Pemodelan Regresi Linier Harga Mobil & Evaluasi Model | [Pertemuan7_Ikctiar_250401020169.ipynb](./Pertemuan7_Ikctiar_250401020169.ipynb) |

---

## Tools & Library Yang Digunakan

Untuk mengerjakan seluruh analisis dan visualisasi di atas, saya menggunakan Python 3 beserta library pendukung berikut:
* **Python**: Bahasa pemrograman utama.
* **Pandas**: Untuk manipulasi tabel dan pembersihan data.
* **NumPy**: Untuk komputasi numerik dan pembuatan dataset sintetis.
* **Matplotlib**: Untuk membuat visualisasi dasar dan dashboard multi-subplot.
* **Seaborn**: Untuk visualisasi statistik yang lebih rapi dan modern.
* **Scikit-Learn**: Untuk preprocessing (seperti scaling/encoding) dan pembuatan model regresi linear.
* **Requests & json_normalize**: Untuk mengambil data dari REST API eksternal dan mengubahnya menjadi format dataframe.

---

## Cara Menjalankan Notebook Secara Lokal

Jika ingin menjalankan file notebook ini di komputer Anda, silakan ikuti langkah-langkah berikut:

### 1. Persiapan
Pastikan Python (versi 3.8 ke atas) dan pip sudah terinstall. Disarankan menggunakan virtual environment agar library tidak bentrok:
```bash
# Membuat virtual environment (opsional)
python -m venv ds-env

# Mengaktifkan virtual environment (Windows)
ds-env\Scripts\activate
```

### 2. Install Library
Install library yang dibutuhkan dengan perintah:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn requests jupyter
```

### 3. Jalankan Jupyter Notebook
Jalankan perintah ini di folder project:
```bash
jupyter notebook
```
Jupyter Notebook akan otomatis terbuka di browser Anda, dan Anda tinggal memilih notebook yang ingin dijalankan.

*Tips: Anda juga bisa langsung upload file .ipynb ini ke Google Colab jika tidak ingin ribet melakukan instalasi lokal.*

---

## Kesimpulan Perjalanan Belajar (Pertemuan 1 - 7)

Selama mengikuti perkuliahan dari Pertemuan 1 sampai 7 ini, saya mendapatkan gambaran lengkap tentang bagaimana alur kerja seorang Data Scientist. Mulanya saya memantapkan dasar Python, lalu masuk ke pengolahan data riil. Saya menyadari bahwa di dunia nyata, data seringkali kotor dan tidak siap pakai. Di situlah pentingnya proses pembersihan data (data wrangling) seperti mengatasi missing value atau membuang outlier.

Selain itu, saya juga belajar menyajikan data lewat visualisasi yang menarik dan mudah dipahami, karena visualisasi adalah cara terbaik untuk menceritakan isi data ke orang lain. Terakhir, pada bagian preprocessing dan pemodelan, saya belajar menyiapkan data (mengubah kategori menjadi angka, menyamakan skala fitur) sebelum akhirnya dimasukkan ke algoritma Regresi Linear untuk membuat model prediksi. Meskipun modelnya masih sederhana, ini menjadi pondasi awal yang sangat berharga bagi saya untuk belajar machine learning yang lebih kompleks ke depannya.

