# 👗 Clothes Sales - Exploratory Data Analysis

## 📌 Project Overview
Proyek ini merupakan analisis eksplorasi data (EDA) pada dataset penjualan pakaian 
periode Januari 2023 – September 2024. Analisis dilakukan untuk mengidentifikasi 
pola penjualan, performa channel, segmentasi customer, dan tingkat pembatalan transaksi 
guna menghasilkan insight yang actionable bagi bisnis.

---

## ❓ Business Questions
1. Revenue dan jumlah customer tertinggi/terendah terjadi di bulan apa?
2. Platform mana (in-store, online, mobile app, third-party) yang paling menghasilkan revenue dan profit?
3. Berapa banyak produk yang menghasilkan 80% revenue?
4. Berapa banyak transaksi yang gagal/dibatalkan?
5. Customer mana yang berpotensi untuk dipertahankan dan mana yang sudah lama tidak bertransaksi?

---

## 📂 Dataset
- **Sumber:** Kaggle
- **Periode:** Januari 2023 – September 2024
- **Jumlah data:** ~9,800 transaksi
- **Kolom utama:** saleID, saleDate, productName, productCategory, 
totalAmount, totalCost, customerID, salesChannel, status, salespersonName

---

## 🛠️ Tools & Library
- **Python** — pandas, matplotlib, seaborn
- **Jupyter Notebook**

---

## 📊 Methods
| Analisis | Metode |
|---|---|
| Tren bulanan | Groupby + Moving Average |
| Performa channel | Groupby + Bar Chart |
| Prioritas produk | Pareto ABC Classification |
| Pembatalan transaksi | Descriptive + Cross-tabulation |
| Segmentasi customer | RFM Analysis |

---

## 💡 Key Insights
- Revenue dan customer tertinggi terjadi di **Januari 2024**, terendah di **Juli 2024**
- **In-store** mendominasi revenue dan profit, sementara **third-party** memiliki margin tertinggi (25.9%)
- Dibutuhkan **50.4% produk** (1270 dari 2518) untuk menghasilkan 80% revenue — distribusi penjualan merata
- Cancellation rate konsisten tinggi **~40%** di semua channel dan kategori — mengindikasikan masalah sistemik
- Terdapat **609 Champions** dan **949 At Risk** customer yang perlu treatment berbeda

---

## ⚠️ Limitations
- Seluruh customer hanya melakukan 1 kali transaksi sehingga cohort analysis 
dan RFM kurang optimal untuk mengukur loyalitas sesungguhnya
- Data Oktober 2024 tidak diikutkan karena tidak lengkap satu bulan penuh

---
