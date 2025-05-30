# Quantium Virtual Internship – Task 1: Data Preparation and Customer Analytics

## 📌 Deskripsi Proyek

Repository ini berisi hasil pengerjaan **Task 1** dari program **Quantium Virtual Internship** yang diselenggarakan oleh [Forage](https://www.theforage.com/).  
Dalam tugas ini, saya menganalisis data transaksi dan perilaku pelanggan untuk mengidentifikasi pola pembelian dan memberikan rekomendasi komersial kepada klien.

## 🧰 Tools & Teknologi

- Bahasa Pemrograman: **R**
- Lingkungan Pengembangan: **RStudio**
- Paket yang digunakan:
  - `ggplot2`
  - `readr`
  - `dplyr`
  - `tidyr`
  - `data.table`
  - `lubridate`

## 📂 Struktur Direktori

- `QVI_transaction_data.xlsx` – Dataset transaksi
- `QVI_purchase_behaviour.csv` – Dataset perilaku pembelian
- `quantium_analysis.Rmd` – RMarkdown untuk analisis utama
- `quantium_analysis.html` – Output HTML dari RMarkdown
- `quantium_analysis.pdf` – Output PDF dari RMarkdown
- `quantium-virtual-internship-project.ipynb` – Notebook opsional (jika ada)
- `InsideSherpa_Task1_DraftSolutions - Template.pdf` – Template solusi dari program
- `README.md` – Penjelasan proyek


## 🧪 Langkah Analisis

1. **Eksplorasi Data**:
   - Memeriksa struktur dan tipe data
   - Mengidentifikasi nilai hilang dan outlier

2. **Pembersihan Data**:
   - Mengubah format tanggal
   - Menghapus produk non-chips
   - Menstandarkan nama merek dan ukuran kemasan

3. **Penggabungan Data**:
   - Menggabungkan data transaksi dan perilaku pelanggan berdasarkan `LYLTY_CARD_NBR`

4. **Analisis Segmentasi Pelanggan**:
   - Menganalisis perilaku pembelian berdasarkan `LIFESTAGE` dan `PREMIUM_CUSTOMER`
   - Menghitung metrik seperti total penjualan, jumlah transaksi, dan rata-rata pembelian per pelanggan

5. **Visualisasi Data**:
   - Membuat grafik batang dan boxplot untuk menggambarkan distribusi penjualan dan pola belanja

## 📈 Temuan Utama

- Segmen **Mainstream Young Singles/Couples** memiliki pembelian chips tertinggi.
- Merek **Tyrrells** populer di kalangan pelanggan **Mainstream** dan **Premium**.
- Pelanggan **Budget** membeli dalam volume besar namun harga per unit lebih rendah.

## 💡 Rekomendasi

- Fokuskan strategi pemasaran pada segmen **Mainstream Young Singles/Couples**.
- Tingkatkan visibilitas merek **Tyrrells**.
- Tawarkan promosi bundling untuk pelanggan **Budget** guna mendorong volume pembelian.

## 📜 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

📊 Untuk melihat hasil analisis lengkap, silakan buka file `quantium_analysis.html` atau `quantium_analysis.pdf` di repository ini.

📫 Jika Anda punya masukan, silakan buka [Issue](https://github.com/sayidmufaqih/quantium-internship-task1/issues) atau hubungi saya via [GitHub](https://github.com/sayidmufaqih).

---

*Referensi gaya: [minji-mia/Quantium-Virtual-Internship](https://github.com/minji-mia/Quantium-Virtual-Internship), [talibizhar1/Quantium-Data-Analyst-Virtual-Internship](https://github.com/talibizhar1/Quantium-Data-Analyst-Virtual-Internship)*

