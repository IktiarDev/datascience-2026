# Portofolio Data Science - Pertemuan 1 s/d 7

Selamat datang di repository portofolio perkuliahan Pengantar Data Science saya. Repository ini dibuat untuk mendokumentasikan seluruh materi pembelajaran, latihan pemrograman, analisis data, visualisasi, preprocessing, hingga pemodelan regresi yang telah saya selesaikan sepanjang Pertemuan 1 sampai Pertemuan 7.

## Identitas Penulis
* **Nama Lengkap**: Muhammad Ikctiar Saputra
* **NIM**: 250401020169
* **Kelas**: IF401
* **Program Studi**: PJJ Informatika
* **Instansi**: Universitas Siber Asia

---

## Deskripsi Singkat Repository
Halo! Saya Muhammad Ikctiar Saputra, seorang mahasiswa Informatika PJJ di Universitas Siber Asia. Belajar Data Science merupakan bagian penting dari perjalanan akademik dan karir saya, dengan tujuan utama untuk memahami bagaimana data dapat diolah menjadi wawasan (*insights*) yang berharga untuk memecahkan masalah nyata di industri teknologi dan otomatisasi bisnis. Melalui perkuliahan ini, saya berkomitmen untuk menguasai dasar-dasar pemrograman data, pembersihan data, visualisasi yang informatif, serta konsep pemrosesan awal data sebelum masuk ke pemodelan statistik dan machine learning.

Repository ini berisi portofolio lengkap tugas dan latihan praktis mingguan yang mencakup seluruh alur kerja Data Science (*Data Science Workflow*). Di dalamnya, Anda akan menemukan eksplorasi sintaks Python dasar, analisis statistik deskriptif menggunakan dataset nyata, proses pembersihan data kotor (*data wrangling*), integrasi dengan REST API publik, visualisasi interaktif dan pembuatan dashboard visualisasi statis, rekayasa fitur (*feature engineering*) seperti *one-hot encoding* dan scaling, hingga implementasi model regresi linier untuk memprediksi harga mobil berdasarkan data sintetis. Setiap topik dikemas secara terpisah dalam file Jupyter Notebook yang rapi dan terstruktur.

---

## Daftar Pertemuan & Link Notebook

Berikut adalah tabel daftar pertemuan perkuliahan beserta topik bahasan dan akses langsung ke masing-masing notebook:

| Pertemuan | Topik / Deskripsi Pembahasan | Link Akses Notebook |
| :--- | :--- | :--- |
| **Pertemuan 1** | Dasar Pemrograman Python (Variabel, Loop, List, Fungsi) | [Pertemuan1_Ikctiar_250401020169.ipynb](file:///c:/Users/ahmad/OneDrive/Documents/Kuliah/data-science/Pertemuan1_Ikctiar_250401020169.ipynb) |
| **Pertemuan 2** | Eksplorasi Data Analitis (EDA) pada Dataset Tips | [Pertemuan2_Ikctiar_250401020169.ipynb](file:///c:/Users/ahmad/OneDrive/Documents/Kuliah/data-science/Pertemuan2_Ikctiar_250401020169.ipynb) |
| **Pertemuan 3** | Pembersihan Data (Data Wrangling) & Integrasi REST API | [Pertemuan3_Ikctiar_250401020169.ipynb](file:///c:/Users/ahmad/OneDrive/Documents/Kuliah/data-science/Pertemuan3_Ikctiar_250401020169.ipynb) |
| **Pertemuan 4** | Visualisasi Data Eksploratif pada Dataset Penguins | [Pertemuan4_Ikctiar_250401020169.ipynb](file:///c:/Users/ahmad/OneDrive/Documents/Kuliah/data-science/Pertemuan4_Ikctiar_250401020169.ipynb) |
| **Pertemuan 5** | Dashboard Visualisasi Statis 2x2 Multi-subplot | [Pertemuan5_Ikctiar_250401020169.ipynb](file:///c:/Users/ahmad/OneDrive/Documents/Kuliah/data-science/Pertemuan5_Ikctiar_250401020169.ipynb) |
| **Pertemuan 6** | Pra-pemrosesan Data (ML Preprocessing) pada Dataset Tips | [Pertemuan6_Ikctiar_250401020169.ipynb](file:///c:/Users/ahmad/OneDrive/Documents/Kuliah/data-science/Pertemuan6_Ikctiar_250401020169.ipynb) |
| **Pertemuan 7** | Pemodelan Regresi Linier Harga Mobil & Evaluasi Model | [Pertemuan7_Ikctiar_250401020169.ipynb](file:///c:/Users/ahmad/OneDrive/Documents/Kuliah/data-science/Pertemuan7_Ikctiar_250401020169.ipynb) |


---

## Tools & Library Yang Digunakan

Seluruh analisis dan implementasi dalam portofolio ini dibangun menggunakan ekosistem Python 3 dan pustaka pendukung berikut:
* **Python**: Bahasa pemrograman utama untuk seluruh logika data.
* **Pandas**: Digunakan untuk manipulasi tabel data, pembersihan data (*data wrangling*), dan membaca format CSV.
* **NumPy**: Digunakan untuk komputasi numerik, pembuatan dataset sintetis, dan operasi matriks.
* **Matplotlib**: Pustaka visualisasi dasar untuk menggambar chart, grafik kustom, dan mengatur tata letak dashboard multi-subplot.
* **Seaborn**: Pustaka visualisasi berbasis Matplotlib dengan estetika modern untuk histogram, boxplot, dan heatmap korelasi.
* **Scikit-Learn**: Pustaka machine learning untuk pembagian data (*train-test split*), standarisasi skala fitur (*StandardScaler*), serta pelatihan model regresi linier (*LinearRegression*).
* **Requests & json_normalize**: Library untuk mengambil data dari server REST API publik secara dinamis dan menyusunnya ke dalam Pandas DataFrame.

---

## Cara Menjalankan Notebook Secara Lokal

Untuk menjalankan file Jupyter Notebook di komputer Anda, ikuti langkah-langkah di bawah ini:

### 1. Prasyarat (Prerequisites)
Pastikan Anda sudah menginstal **Python (versi 3.8 ke atas)** dan package manager **pip**. Anda disarankan untuk menggunakan Anaconda atau membuat virtual environment terlebih dahulu:
```bash
# Membuat virtual environment (opsional)
python -m venv ds-env

# Mengaktifkan virtual environment (Windows)
ds-env\Scripts\activate
```

### 2. Instalasi Dependensi
Instal pustaka-pustaka yang diperlukan dengan menjalankan perintah berikut:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn requests jupyter
```

### 3. Menjalankan Jupyter Notebook
Buka aplikasi Jupyter di workspace project ini dengan perintah:
```bash
jupyter notebook
```
Setelah browser terbuka, Anda dapat memilih dan menjalankan file notebook (.ipynb) dari daftar yang tersedia dari atas ke bawah.

*Catatan: Anda juga dapat langsung mengunggah file-file notebook ini ke **Google Colab** untuk menjalankannya secara online tanpa perlu instalasi lokal.*

---

## Kesimpulan Umum Perjalanan Belajar (Pertemuan 1 - 7)

Perjalanan belajar Data Science dari Pertemuan 1 hingga Pertemuan 7 ini memberikan pemahaman yang menyeluruh dan logis tentang bagaimana sebuah alur kerja sains data bekerja dari awal hingga akhir. Pembelajaran dimulai dari penguasaan fondasi pemrograman dasar menggunakan Python di Pertemuan 1, yang menjadi bekal krusial sebelum mulai memanipulasi data tabular. 

Selanjutnya pada Pertemuan 2 dan 3, saya memahami bahwa data di dunia nyata jarang sekali bersih. Kemampuan melakukan eksplorasi data analitis dasar serta membersihkan data (*data wrangling*) seperti menangani duplikat, imputasi nilai kosong, normalisasi teks, dan membuang outlier dengan batas statistik (IQR) sangatlah krusial karena model machine learning yang baik hanya bisa dibangun dari data yang berkualitas tinggi (*garbage in, garbage out*).

Pada Pertemuan 4 dan 5, fokus bergeser pada penyajian data secara visual. Visualisasi data bukan hanya untuk menghasilkan grafik yang indah, melainkan alat komunikasi yang sangat kuat untuk menemukan pola tersembunyi, korelasi antar variabel, dan menyajikan temuan kompleks kepada pemangku kepentingan dalam bentuk dashboard yang ringkas dan mudah dipahami. 

Akhirnya, pada Pertemuan 6 dan 7, saya diperkenalkan dengan jembatan menuju Machine Learning. Sebelum data digunakan untuk melatih model regresi, data tersebut harus melalui preprocessing (scaling dan encoding) agar algoritma dapat memprosesnya dengan optimal. Melalui pemodelan Regresi Linier sederhana di pertemuan terakhir, saya dapat menguji kemampuan prediksi model dan melakukan evaluasi performa menggunakan metrik kesalahan (seperti MAE dan RMSE) untuk memahami seberapa akurat model dalam memprediksi data baru. Pembelajaran ini memberikan pondasi kokoh bagi saya untuk mendalami pemodelan prediksi yang lebih kompleks di masa mendatang.
