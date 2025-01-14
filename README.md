# Supermarket Customer Analysis

## Deskripsi
Project ini bertujuan untuk menganalisis data pelanggan supermarket guna memahami pola consumer behavior, seperti hubungan antara pendapatan, status pernikahan, jumlah anak, dan pengeluaran untuk kategori produk tertentu (wine dan produk daging). Insight yang dihasilkan digunakan untuk mendukung pengambilan keputusan strategis, seperti segmentasi pelanggan dan pengembangan strategi pemasaran.

## Tujuan
1. Menganalisis hubungan antara pendapatan, jumlah anak, status pernikahan, dan pengeluaran.
2. Melakukan segmentasi pelanggan berdasarkan variabel-variabel penting.
3. Memberikan insight bisnis yang relevan untuk meningkatkan efisiensi strategi pemasaran.
4. Mengidentifikasi perbedaan pola konsumsi berdasarkan karakteristik pelanggan untuk mendukung personalisasi penawaran.


## Dataset
Dataset yang digunakan berisi informasi mengenai:
- **Pendapatan (Income):** Pendapatan tahunan pelanggan.
- **Status Pernikahan (Marital_Status):** Status pernikahan pelanggan (Single, Married, Single Parent.).
- **Jumlah Anak di Rumah (Kidhome, Teenhome)
- **Pengeluaran Pelanggan untuk Produk:**
  - **Wine (MntWines):** Pengeluaran untuk wine.
  - **Produk Daging (MntMeatProducts):** Pengeluaran untuk daging.
  - **Buah (MntFruits):** Pengeluaran untuk buah.
  - **Produk Ikan (MntFishProducts):** Pengeluaran untuk produk ikan.

### Langkah Pembersihan Data
1. **Penanganan Missing Values:** Menghapus nilai kosong pada kolom kritis seperti pendapatan, status pernikahan, dan jumlah anak.
2. **Transformasi Kategori:** Menggabungkan kategori status pernikahan serupa menjadi grup yang lebih relevan:
     - `Single` dan `Alone` digabung menjadi `Single`.
     - `Widow` dan `Divorced` digabung menjadi `Single Parent`.
3. **Penghapusan Outlier:** Menghapus outlier pada kolom pendapatan menggunakan metode Interquartile Range (IQR).
4. **Pembuatan Variabel Baru:**
   - `Kids_Status`: Kategori anak di rumah (`Kids`/`No Kids`).
   - Total pengeluaran pelanggan untuk semua kategori produk.
  
## Analisis yang Dilakukan
1. Eksplorasi Data**
2. Segmentasi Pelanggan**
3. Visualisasi Data**

## Hasil dan Insight
### Hubungan Pendapatan dan Pengeluaran:
- Terdapat korelasi positif yang kuat (**0.82**) antara pendapatan dan pengeluaran total.
- Pelanggan dengan pendapatan tinggi memiliki pengeluaran yang jauh lebih tinggi untuk produk premium (wine dan daging).

### Pengaruh Jumlah Anak:
- Semakin banyak anak di rumah, semakin rendah pengeluaran untuk produk premium seperti wine dan daging (korelasi **-0.53**).
- Pelanggan tanpa anak memiliki pengeluaran lebih tinggi untuk semua kategori produk.

### Status Pernikahan dan Pola Pengeluaran:
- Pelanggan **Single** memiliki pengeluaran tertinggi untuk wine.
- Pelanggan **Married** memiliki pengeluaran lebih merata untuk semua kategori produk.

### Segmentasi Berdasarkan Pendapatan:
- Pelanggan dengan pendapatan rendah lebih banyak mengalokasikan pengeluaran pada kebutuhan dasar (daging dan ikan).
- Pelanggan dengan pendapatan tinggi cenderung mengalokasikan anggaran lebih besar pada produk premium seperti wine.

---

## Rekomendasi Bisnis
- Fokuskan promosi produk premium (wine, daging) kepada pelanggan dengan pendapatan tinggi, terutama yang tidak memiliki anak.
- Promosi bisa dipersonalisasikan berdasarkan insight yang sudah ditemukan, bisa melakukan wawancara dengan segmen-segmen yang sudah dikelompokan untuk mencari pain poin dan promosi bisa lebih personalisasi
- Tawarkan bundling atau diskon untuk produk daging, buah, dan ikan.
- Promosikan produk ekonomis pada pelanggan dengan jumlah anak lebih banyak.
- Gunakan hasil segmentasi ini untuk menyusun kampanye pemasaran yang spesifik, seperti penawaran eksklusif untuk pelanggan Single dengan pendapatan tinggi atau paket hemat untuk keluarga besar.
- Sediakan variasi produk yang sesuai dengan karakteristik setiap segmen pelanggan untuk meningkatkan efisiensi pemasaran dan memaksimalkan pendapatan.

