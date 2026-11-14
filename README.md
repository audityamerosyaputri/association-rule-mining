# Association Rule Mining (Market Basket Analysis)

## 📌 Deskripsi Proyek

Repository ini berisi implementasi dan analisis praktikum **Data Mining** dengan topik *Association Rule Mining (Market Basket Analysis)*.

Praktikum ini bertujuan untuk menemukan pola hubungan antaritem yang sering dibeli secara bersamaan dalam suatu transaksi menggunakan algoritma Apriori dan FP-Growth.

Hasil analisis dapat dimanfaatkan untuk memberikan rekomendasi bisnis, seperti strategi cross-selling, penataan produk, bundling promo, dan rekomendasi produk.

## 🎯 Tujuan Praktikum

1. Memahami konsep dasar Association Rule Mining dan Market Basket Analysis.
2. Melakukan encoding data transaksi ke dalam format One-Hot menggunakan TransactionEncoder.
3. Menerapkan algoritma Apriori untuk menemukan frequent itemset.
4. Membentuk aturan asosiasi berdasarkan Support, Confidence, dan Lift.
5. Menganalisis pengaruh nilai minimum support dan minimum confidence.
6. Membandingkan performa algoritma Apriori dan FP-Growth.
7. Menginterpretasikan hasil aturan asosiasi menjadi rekomendasi bisnis.

## 📊 Dataset

Dataset yang digunakan merupakan data transaksi penjualan yang berisi kumpulan item dalam setiap transaksi.

Berdasarkan dataset pada modul praktikum, data terdiri dari:

- Jumlah transaksi: 60 transaksi.
- Jumlah jenis item: 12 item.
- Format data: daftar item dalam setiap transaksi.
- Sumber data: dataset sintetis transaksi toko kelontong.

Jenis item yang digunakan:
- Roti
- Mentega
- Susu
- Telur
- Kopi
- Gula
- Teh
- Keju
- Mie Instan
- Kecap
- Sabun
- Shampo

## 🛠️ Tools dan Library

Proyek ini menggunakan beberapa perangkat lunak dan library berikut:

- Python 3.10 atau lebih baru
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Mlxtend
- Matplotlib

## ⚙️ Metode yang Digunakan

### 1. Market Basket Analysis
Digunakan untuk menemukan pola pembelian item yang sering muncul secara bersamaan dalam transaksi.

### 2. Algoritma Apriori
Digunakan untuk menemukan frequent itemset berdasarkan nilai minimum support.

### 3. Association Rules
Digunakan untuk membentuk aturan hubungan antaritem dengan memperhatikan nilai support, confidence, dan lift.

### 4. FP-Growth
Digunakan sebagai algoritma alternatif Apriori untuk menemukan frequent itemset dengan pendekatan FP-Tree.

## 📐 Ukuran Evaluasi

Tiga ukuran utama yang digunakan dalam analisis:

- **Support:** Mengukur seberapa sering suatu item atau kombinasi item muncul dalam seluruh transaksi.
- **Confidence:** Mengukur tingkat kemungkinan item Y dibeli ketika item X dibeli.
- **Lift:** Mengukur kekuatan hubungan antara dua item dalam suatu aturan asosiasi.

Interpretasi Lift:
- Lift > 1: Hubungan positif antaritem.
- Lift = 1: Tidak terdapat hubungan atau independen.
- Lift < 1: Hubungan negatif antaritem.

## 📝 Tahapan Praktikum

1. Persiapan dan eksplorasi data transaksi.
2. Encoding data transaksi menggunakan TransactionEncoder.
3. Pencarian frequent itemset menggunakan algoritma Apriori.
4. Pembentukan aturan asosiasi.
5. Visualisasi hasil aturan asosiasi menggunakan scatter plot dan bar chart.
6. Interpretasi aturan asosiasi menjadi rekomendasi bisnis.
7. Eksperimen pengaruh nilai min_support dan min_confidence.
8. Perbandingan algoritma Apriori dan FP-Growth.

## 🔬 Eksperimen dan Analisis

Praktikum ini mencakup empat tugas utama:

**Tugas 1 – Eksplorasi Ambang Batas**
- Menganalisis pengaruh perubahan min_support.
- Menganalisis perubahan min_confidence.
- Membahas trade-off antara jumlah aturan dan kualitas aturan.

**Tugas 2 – Analisis Mendalam Aturan**
- Memilih aturan asosiasi yang belum dibahas.
- Menghitung leverage dan conviction.
- Memberikan interpretasi bisnis.

**Tugas 3 – Perbandingan Apriori dan FP-Growth**
- Membandingkan jumlah frequent itemset.
- Mengukur waktu eksekusi kedua algoritma.
- Menganalisis efisiensi masing-masing algoritma.

**Tugas 4 – Studi Kasus Mandiri**
- Menggunakan dataset transaksi sendiri dengan minimal 40 transaksi dan 8 jenis item.
- Menerapkan seluruh tahapan Association Rule Mining.
- Membuat visualisasi hasil.
- Memberikan minimal 3 rekomendasi bisnis berdasarkan aturan asosiasi.

## 💻 Cara Menjalankan Program

1. Clone repository ini:

   ```bash
   https://github.com/audityamerosyaputri/association-rule-mining.git
   ```

2. Install library yang dibutuhkan:

   ```bash
   pip install pandas numpy matplotlib mlxtend
   ```

3. Buka file notebook menggunakan Jupyter Notebook atau Google Colab.

4. Pastikan dataset tersedia sesuai lokasi yang digunakan dalam kode program.

5. Jalankan seluruh cell program secara berurutan untuk mendapatkan hasil analisis.

## 👥 Anggota Kelompok

| No. | Nama | NIM |
|---|---|---|---|
| 1 | AUDITYA MEROSYA PUTRI | 24343001 |
| 2 | MUHAMMAD ZAHRAN | 24343077 |
| 3 | MUHAMMAD RIYAD ANWARI | 24343044 |

## 🏫 Identitas Praktikum

- Universitas: Universitas Negeri Padang
- Fakultas: Fakultas Teknik
- Departemen: Teknik Elektronika
- Program Studi: Informatika
- Mata Kuliah: Data Mining
- Topik: Association Rule Mining (Market Basket Analysis)
- Tahun: 2026

## 📚 Referensi

Modul Praktikum Data Mining – Association Rule Mining (Market Basket Analysis), Program Studi Informatika, Universitas Negeri Padang, 2026.

