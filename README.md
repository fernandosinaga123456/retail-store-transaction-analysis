# Retail Store Transaction Analysis
> **Tools:** Microsoft Excel | Python | Power BI |
> **Oleh:** Fernando Hasiholan Sinaga 

---

## Latar Belakang

Toko retail menghasilkan ratusan transaksi setiap harinya, namun tidak semua data tersebut dimanfaatkan secara optimal untuk pengambilan keputusan bisnis.
Dengan 23.100 data transaksi dari 50 toko dan 1.000 produk, proyek ini berusaha menjawab pertanyaan bisnis yang sederhana namun penting: kategori mana yang paling menguntungkan, toko mana yang performanya paling tinggi, dan apakah ada tren yang perlu diwaspadai.

Proyek ini merupakan latihan nyata dalam mengolah data dari awal, mulai dari data cleaning di Excel, analisis menggunakan Python, hingga penyajian dalam dashboard Power BI yang dapat digunakan langsung sebagai dasar pengambilan keputusan bisnis.

---

## Alur Kerja

### 1. Data Cleaning - Microsoft Excel
Tahapan pertama adalah membersihkan data yang belum siap dianalisis. Duplikat dihapus, missing values ditangani, format tanggal distandarisasi, dan kolom yang tergabung dipisahkan. Setelah seluruh proses ini selesai, data sudah bersih dan siap untuk dianalisis lebih lanjut.

### 2. Analisis Data - Python
Tahapan kedua adalah eksplorasi data menggunakan Python. Dengan library Pandas, setiap transaksi dianalisis untuk menemukan pola penjualan, performa per kategori produk, tren bulanan, hingga store dengan performa terbaik.

**Key Metrics yang ditemukan:**
| Metric | Value |
|---|---|
| Total Revenue | 27.1M |
| Total Transactions | 23.100 |
| Total Products | 1.000 |
| Total Stores | 50 |

### 3. Visualisasi Data - Power BI
Tahapan ketiga adalah menyajikan seluruh temuan dalam dashboard interaktif menggunakan Power BI. Dashboard dapat difilter berdasarkan tahun (2023, 2024, 2025) dan menampilkan tren transaksi, revenue per kategori, top stores, serta distribusi metode pembayaran.

![Store Dashboard](Store%20Dashboard.png)

---

##  Temuan & Insight Utama

###  Transaction Trend
- Volume transaksi stabil di 0.1bn dari Januari 2024 hingga pertengahan 2025
- Terjadi **penurunan drastis** di Juli 2025, ini adalah **red flag** 
  yang perlu investigasi lebih lanjut
- Bisnis mengalami stagnasi growth, perlu strategi customer acquisition baru

###  Revenue per Category
- **Electronics** menjadi top performer (~0.4bn)
- Mayoritas kategori berada di range 0.3–0.35bn (distribusi cukup merata)
- **Grocery** menjadi kategori terendah (~0.32bn), peluang untuk dioptimalkan

###  Top 5 Stores by Revenue
- **Store S3** memimpin dengan revenue ~60M
- Gap antar top 5 stores tidak terlalu besar (33% difference)
- S3 bisa dijadikan benchmark best practice untuk stores lainnya

###  Payment Method Distribution
- Distribusi sangat merata: Credit Card (20.45%), Cash (20.13%), 
  Mobile Wallet (20.12%), UPI (19.97%), Debit Bit Card (19.33%)
- Digital payment mendominasi ~80% transaksi
- Cash masih signifikan, segmen ini perlu dipertahankan

---

##  Rekomendasi Bisnis

- **Investigasi penurunan Juli 2025**, cek sistem, kompetitor, atau 
  seasonal effect
- **Launch customer acquisition campaign**, untuk mengatasi stagnasi
- **Double down on Electronics**, expand product range & premium options
- **Revitalize Grocery**, bundling strategy & subscription model
- **Jadikan S3 sebagai benchmark**, audit dan scale best practice-nya
- **Incentivize digital payment**, cashback untuk non-cash transaction

---

## Kesimpulan

Dari keseluruhan analisis terhadap 23.100 transaksi, bisnis ini menunjukkan performa yang stabil namun mulai menghadapi tantangan pertumbuhan. Volume transaksi stagnan di angka 0.1bn sejak awal 2024 dan terjadi penurunan drastis di Juli 2025 yang perlu diinvestigasi lebih lanjut, baik dari sisi sistem, kompetitor, maupun seasonal effect.

Electronics tetap menjadi kategori terkuat dengan revenue sekitar 0.4bn, sementara distribusi antar kategori lainnya cukup merata di kisaran 0.3 hingga 0.35bn. Grocery menjadi kategori dengan performa terendah dan masih memiliki ruang untuk dioptimalkan melalui strategi bundling atau subscription model.

Dari sisi toko, Store S3 memimpin dengan revenue sekitar 60M dan dapat dijadikan benchmark best practice bagi toko lainnya. Distribusi metode pembayaran sangat merata dengan digital payment mendominasi sekitar 80% transaksi, menunjukkan kesiapan pelanggan terhadap ekosistem pembayaran digital.

Secara keseluruhan, bisnis ini membutuhkan strategi customer acquisition baru untuk keluar dari fase stagnasi, optimalisasi kategori Grocery, serta investigasi menyeluruh terhadap anomali Juli 2025 sebelum berdampak lebih jauh pada performa bisnis.

## Contact

| Platform | Link |
|---|---|
| GitHub | [fernandosinaga123456](https://github.com/fernandosinaga123456) |
| Email | [fernandosinaga2002@gmail.com](mailto:fernandosinaga2002@gmail.com) |
| LinkedIn | [Fernando Hasiholan Sinaga](https://www.linkedin.com/in/fernandohasiholansinaga/) |
| Portfolio | [datascienceportfol.io/fernandosinaga_h](https://www.datascienceportfol.io/fernandosinaga_h) |
| Instagram | [@fernandosng_](https://www.instagram.com/fernandosng_) |
