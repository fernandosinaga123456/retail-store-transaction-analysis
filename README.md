# Retail Store Transaction Analysis
> **Tools:** Microsoft Excel | Python | Power BI
> **Oleh:** Fernando H Sinaga |

---

## Latar Belakang

Toko retail menghasilkan ratusan transaksi setiap harinya, 
tapi seberapa banyak dari data itu yang benar-benar dimanfaatkan?

Pertanyaan itulah yang mendorong saya untuk mengerjakan proyek ini. 
Dengan 23.100 data transaksi dari 50 toko dan 1.000 produk, saya 
mencoba menjawab pertanyaan-pertanyaan bisnis yang sederhana namun 
penting: 
Kategori mana yang paling menguntungkan? 
Toko mana yang 
paling perform? 
Apakah ada tren yang perlu diwaspadai?

Proyek ini adalah latihan nyata saya dalam mengolah data mentah, 
mulai dari tahapan data cleaning di Excel, menganalisisnya dengan Python, 
hingga menyajikannya dalam dashboard Power BI yang bisa langsung 
digunakan untuk pengambilan keputusan.

---

## Alur Kerja

### 1. Data Cleaning - Microsoft Excel
Perjalanan dimulai dari data yang belum sempurna. Duplikat dihapus, 
missing values ditangani, format tanggal distandarisasi, dan kolom 
yang tergabung dipisahkan. Setelah proses ini, data siap untuk berbicara.

### 2. Analisis Data - Python
Dengan data yang bersih, saatnya menggali lebih dalam. Menggunakan 
Pandas, setiap transaksi dianalisis untuk menemukan pola penjualan, 
performa per kategori produk, tren bulanan, hingga store terbaik.

**Key Metrics yang ditemukan:**
| Metric | Value |
|---|---|
| Total Revenue | 27.1M |
| Total Transactions | 23.100 |
| Total Products | 1.000 |
| Total Stores | 50 |

### 3. Visualisasi Data - Power BI
Semua temuan divisualisasikan dalam dashboard interaktif yang bisa 
di-filter berdasarkan tahun (2023, 2024, 2025), menampilkan tren 
transaksi, revenue per kategori, top stores, dan distribusi 
metode pembayaran.

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

## Contact

| Platform | Link |
|---|---|
| GitHub | [fernandosinaga123456](https://github.com/fernandosinaga123456) |
| Email | [fernandosinaga2002@gmail.com](mailto:fernandosinaga2002@gmail.com) |
| LinkedIn | [Fernando Hasiholan Sinaga](https://www.linkedin.com/in/fernandohasiholansinaga/) |
| Instagram | [@fernandosng_](https://www.instagram.com/fernandosng_) |
