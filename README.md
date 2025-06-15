# 🎯 RFM Analysis: Skincare & Beauty E-Commerce

## 📌 Deskripsi Proyek
Proyek ini bertujuan melakukan segmentasi pelanggan toko e-commerce global yang menjual produk skincare dan kecantikan lainnya menggunakan metode RFM (Recency, Frequency, Monetary). Dengan analisis ini, bisnis dapat mengidentifikasi pelanggan setia, loyal , pelanggan berisiko kehilangan, dan pelanggan hilang.

## 🎯 Tujuan Analisis
- Menghitung nilai Recency, Frequency, dan Monetary untuk setiap pelanggan
- Menghitung skor RFM untuk setiap pelanggan berdasarkan data transaksi.
- Mengelompokkan pelanggan ke dalam segmentasi yang bermakna.
- Memberikan insight untuk hasil segmentasi pelanggan.

## 🧾 Dataset
Dataset transaksi pelanggan dengan kolom utama:
- `Customer_ID`
- `Order_ID`
- `Order_Date`
- `Sales`

Sumber: Dummy dataset dibuat untuk keperluan portofolio (Kaggle)

## 🛠️ Tools yang Digunakan
- Python (Pandas, Matplotlib, Seaborn)
- Google Colab / Jupyter Notebook

## 🔍 Alur Analisis
1. Data Cleaning & Preparation
2. Perhitungan nilai Recency, Frequency, Monetary
3. Pemberian skor R, F, M (1–5)
4. Segmentasi pelanggan berdasarkan RFM Score
5. Visualisasi segmentasi dan insight

## 📊 Hasil Utama (Highlight)
- 📊 Jumlah Pelanggan per Segmen
  
  ![Image](https://github.com/user-attachments/assets/a0abcc0a-b847-4b77-9365-064c8b0ffb31)

  Grafik bar menunjukkan bahwa segmen Berpotensi Hilang memiliki jumlah pelanggan tertinggi (5213), diikuti oleh Loyal (4776) dan Hilang (4422). Sementara itu, segmen Setia memiliki jumlah paling sedikit (3004), yang menandakan basis pelanggan    yang konsisten tetapi relatif kecil. Tingginya angka pada segmen yang berisiko seperti “Berpotensi Hilang” dan “Hilang” menunjukkan adanya tantangan dalam mempertahankan pelanggan.

  Fokuskan strategi retensi seperti promosi eksklusif atau email re-engagement untuk pelanggan yang berpotensi hilang dan hilang guna meminimalkan churn.
  
- 🥧 Proporsi Pelanggan per Segmen
  
  ![Image](https://github.com/user-attachments/assets/3e4ee904-e8b8-4513-b819-1ff8f944ee4e)
  
  Diagram pie menunjukkan bahwa sekitar 30% pelanggan masuk ke segmen Berpotensi Hilang, menjadikannya kelompok dengan proporsi terbesar. Segmen Loyal dan Hilang masing-masing berkontribusi sekitar 27% dan 25%, sedangkan Setia hanya sekitar       17%. Komposisi ini mengindikasikan bahwa sebagian besar pelanggan berada dalam status yang tidak stabil atau rawan pergi.

  Optimalkan pengalaman pelanggan dan berikan insentif loyalitas khusus untuk memperbesar proporsi pelanggan Setia dan Loyal serta memperkecil porsi pelanggan yang berisiko.


## ▶️ Cara Menjalankan
1. Clone repo ini.
2. Jalankan `RFM_Analysis.ipynb` di Jupyter/Colab.

## 👤 Author
Koko  
Bandung, 2025

## 📄 License
Proyek ini dibuat untuk tujuan edukasi dan portofolio.
