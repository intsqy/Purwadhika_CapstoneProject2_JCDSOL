# Supermarket Customer Analysis

## Deskripsi
Project ini bertujuan untuk menganalisis data pelanggan supermarket guna memahami pola consumer behavior, seperti hubungan antara pendapatan, status pernikahan, jumlah anak, dan pengeluaran untuk kategori produk tertentu (wine dan produk daging). Insight yang dihasilkan digunakan untuk mendukung pengambilan keputusan strategis, seperti segmentasi pelanggan dan pengembangan strategi pemasaran.

## Tujuan
1. Menganalisis hubungan antara pendapatan, jumlah anak, status pernikahan, dan pengeluaran.
2. Melakukan segmentasi pelanggan berdasarkan variabel-variabel penting.
3. Memberikan insight bisnis yang relevan untuk meningkatkan efisiensi strategi pemasaran.

## Dataset
Dataset yang digunakan berisi informasi mengenai:
- **Pendapatan (Income):** Pendapatan tahunan pelanggan.
- **Status Pernikahan (Marital_Status):** Status pernikahan pelanggan (Single, Married, Single Parent.).
- **Jumlah Anak di Rumah (Kidhome)
- **Pengeluaran Pelanggan untuk Wine (MntWines)** 
- **Pengeluaran Pelanggan untuk Produk Daging (MntMeatProducts)** 

### Langkah Pembersihan Data
1. Menghapus nilai kosong (missing values) pada kolom kritis seperti pendapatan.
2. Menggabungkan kategori status pernikahan yang serupa menjadi grup yang lebih relevan (contoh: Single dan Alone digabung, Widow dan Divorced digabung).
3. Menghapus outlier pada pendapatan.

## Analisis yang Dilakukan
1. Eksplorasi Data**
2. Segmentasi Pelanggan**
3. Visualisasi Data**

## Hasil dan Insight
   - Terdapat korelasi positif yang kuat (0.65) antara pendapatan dan pengeluaran total.
   - Semakin banyak anak di rumah, semakin kecil pengeluaran untuk produk seperti wine dan daging (korelasi -0.53).
   - Pelanggan dengan pendapatan tinggi tanpa anak memiliki pengeluaran tertinggi untuk produk premium.

## Rekomendasi Bisnis
1. **Targetkan Pelanggan dengan Pendapatan Tinggi**:
   - Fokuskan promosi produk premium (wine, daging) pada pelanggan dengan pendapatan tinggi dan tanpa anak.
2. **Fokus pada Produk Ekonomis untuk Pelanggan dengan Banyak Anak**:
   - Tawarkan bundling atau diskon pada produk.
3. **Pengembangan Strategi Segmentasi**:
   - Gunakan hasil segmentasi ini untuk menyusun campaign yang menyentuh hati sesuai dengan insight yang ditemukan.
