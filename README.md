Supermarket Sales Analysis

## Latar Belakang
Dataset ini berisi data transaksi penjualan dari 3 cabang supermarket (Cabang A, B, dan C), selama periode Januari – Maret 2019. Dataset terdiri dari 1.000 transaksi dengan 20 variabel meliputi informasi cabang, produk, pelanggan, metode pembayaran, dan rating kepuasan.

## Tujuan Analisis
Analisis ini bertujuan untuk menjawab 6 pertanyaan bisnis:
1. Cabang mana yang memiliki performa penjualan terbaik?
2. Kategori produk apa yang memberikan kontribusi penjualan terbesar?
3. Bagaimana pola atau tren penjualan berdasarkan waktu?
4. Segmen pelanggan mana yang paling banyak berbelanja?
5. Metode pembayaran apa yang paling sering digunakan pelanggan?
6. Bagaimana tingkat kepuasan pelanggan di setiap cabang?

## Tools
Microsoft Excel (Pivot Table, Data Cleaning, Dashboard, Visualisasi)

## Informasi Dataset
- Sumber:[Dataset Supermarket Sales](https://www.kaggle.com/datasets/muhdaniyal/supermarket-sales-cleaned-dataset)
- Periode: Januari – Maret 2019
- Jumlah Baris: 1.000 transaksi
- Jumlah Kolom: 20 variabel ( 17 kolom asli + 3 tambahan: day, month, year)

### Penjelasan Kolom
- Invoice ID = Nomor unik setiap transaksi 
- Branch = Cabang supermarket (A, B, C) 
- City = Kota lokasi cabang 
- Customer Type = Tipe pelanggan (Member / Normal) 
- Gender = Jenis kelamin pelanggan 
- Product Line = Kategori produk 
- Unit Price = Harga satuan produk 
- Quantity = Jumlah produk yang dibeli 
- Tax = Pajak 5% dari total pembelian 
- Total = Total pembayaran termasuk pajak 
- Date = Tanggal transaksi 
- Time = Waktu transaksi 
- Payment = Metode pembayaran (Ewallet / Cash / Credit Card) 
- COGS = Harga pokok penjualan 
- Gross Margin Percentage = Persentase margin kotor 
- Gross Income = Pendapatan kotor 
- Rating = Rating kepuasan pelanggan (skala 1-10) 
Catatan: Kolom Gross Margin Percentage memiliki nilai yang sama untuk semua transaksi yaitu sebesar (4.76%).

## Ringkasan Data
Total Penjualan = 322,966,749 
Total Transaksi = 1.000 
Rata-rata Penjualan per Transaksi = 322,97 

---

## Insight & Rekomendasi

### 1. Performa Penjualan per Cabang
Insight:
Cabang C mencatat penjualan tertinggi sebesar 110.569, diikuti Cabang A (106.200) dan Cabang B (106.198). Selisih antara Cabang A dan B sangat tipis, namun Cabang B berada di posisi terendah.
![Dashboard](https://github.com/salzabilaaa/supermarket-sales-analysis/blob/8eb4ec931abd356cd7bc6ca9337df0ea8b87efc5/penjualan%20percabang.png)

Rekomendasi:
Meskipun selisihnya sangat tipis, Cabang B berada di posisi terendah baik dari sisi penjualan maupun rating kepuasan pelanggan. Untuk meningkatkan performa Cabang B, disarankan untuk memperbaiki kualitas pelayanan dan memberlakukan program diskon pada produk-produk tertentu guna menarik lebih banyak pelanggan

### 2. Kategori Produk dengan Penjualan Terbesar
Insight:
Food and Beverages menjadi kategori produk dengan penjualan tertinggi (56.145), sedangkan Health and Beauty mencatat penjualan terendah (49.194).
![Dashboard](![Dashboard](https://github.com/salzabilaaa/supermarket-sales-analysis/blob/8eb4ec931abd356cd7bc6ca9337df0ea8b87efc5/penjualan%20percabang.png))

Rekomendasi:
Untuk mendongkrak penjualan kategori Health and Beauty, supermarket dapat menjalankan beberapa strategi — seperti memberlakukan diskon berkala pada produk-produk pilihan, menyediakan tester produk agar pelanggan dapat mencoba sebelum membeli, serta menempatkan produk Health and Beauty di lokasi yang lebih strategis dan mudah terlihat di dalam toko.

### 3. Pola Penjualan Berdasarkan Waktu
Insight:
Penjualan tertinggi terjadi di bulan Januari (116.292), kemudian turun signifikan di Februari (97.219), dan kembali naik di Maret (109.456).
![Dashboard](https://github.com/salzabilaaa/supermarket-sales-analysis/blob/d7235171fb112522967b0de9bbc9119383d0fb2c/pola%20penjualan%20perbulan.png)

Rekomendasi:
Penjualan mengalami penurunan di bulan Februari dan kembali naik di bulan Maret. Pola ini mengindikasikan adanya fluktuasi permintaan pelanggan antar bulan. Untuk mengantisipasi penurunan di bulan Februari, supermarket dapat menjalankan program promosi khusus seperti diskon, bundling produk, atau event belanja tematik guna mendorong minat pelanggan untuk berbelanja lebih banyak.

### 4. Segmen Pelanggan
Insight:
Segmen Member dan Normal hampir seimbang — Member 50.1% dan Normal 49.9%. Tidak ada dominasi signifikan dari salah satu segmen.
![Dashboard](https://github.com/salzabilaaa/supermarket-sales-analysis/blob/e1a3a5735fb032746f97f1602dd0c61b58c51e17/segmen%20pelanggan.png)

Rekomendasi:
Meskipun jumlah Member dan Non-Member hampir seimbang, mempertahankan dan menumbuhkan segmen Member tetap menjadi prioritas karena pelanggan Member cenderung lebih loyal. Supermarket dapat memperkuat program loyalitas dengan memberikan reward poin, diskon eksklusif, atau penawaran khusus ketika pelanggan mencapai jumlah pembelian tertentu, sehingga mendorong pelanggan Non-Member untuk bergabung menjadi Member

### 5. Metode Pembayaran
Insight:
Ketiga metode pembayaran digunakan secara merata — Ewallet (34.5%), Cash (34.4%), dan Credit Card (31.1%). Credit Card memiliki penggunaan paling rendah dibanding dua metode lainnya.
![Dashboard](https://github.com/salzabilaaa/supermarket-sales-analysis/blob/290b5a02fb1d4b39bca62368f00fdab369ae9d8e/metode%20pembayaran.png)
Rekomendasi:
Ketiga metode pembayaran digunakan secara merata oleh pelanggan, menunjukkan bahwa supermarket sudah memiliki sistem pembayaran yang cukup baik. Namun penggunaan Credit Card sedikit lebih rendah dibanding Ewallet dan Cash. Untuk meningkatkan penggunaan Credit Card, supermarket dapat menjalin kerjasama dengan bank atau penyedia kartu kredit untuk menawarkan cashback atau cicilan 0% pada transaksi tertentu, sehingga pelanggan lebih terdorong untuk menggunakan metode pembayaran ini.

### 6. Rating Kepuasan Pelanggan per Cabang
Insight:
Cabang A dan C memiliki rating kepuasan tertinggi (masing-masing 7.0 dan 7.1), sedangkan Cabang B memiliki rating terendah (6.8). Ini sejalan dengan performa penjualan Cabang B yang juga paling rendah.
![Dashboard]()

**Rekomendasi:**
Cabang B memiliki rating kepuasan terendah (6.8) dibanding Cabang A (7.0) dan Cabang C (7.1), yang sejalan dengan performa penjualannya yang juga paling rendah. Hal ini mengindikasikan adanya korelasi antara kepuasan pelanggan dan penjualan. Untuk meningkatkan rating kepuasan di Cabang B, supermarket dapat melakukan evaluasi rutin terhadap kualitas pelayanan, meningkatkan pelatihan staf, serta membuka saluran feedback bagi pelanggan agar permasalahan dapat diidentifikasi dan ditangani dengan cepat.

