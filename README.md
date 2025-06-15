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

  ![Image](https://github.com/user-attachments/assets/ddd93138-5c94-4ac5-9cbf-23287fcf6812)

  Grafik bar menunjukkan bahwa segmen **Berpotensi Hilang** memiliki jumlah pelanggan tertinggi **(6957)**, diikuti oleh pelanggan **Hilang (6149)**. Sementara itu, segmen **Loyal** memiliki jumlah paling sedikit **(4039)**, yang menandakan basis pelanggan yang konsisten tetapi relatif kecil. Tingginya angka pada segmen yang berisiko seperti “Berpotensi Hilang” dan “Hilang” menunjukkan adanya tantangan dalam mempertahankan pelanggan.

  Fokuskan strategi retensi seperti promosi eksklusif atau email re-engagement untuk pelanggan yang berpotensi hilang dan hilang guna meminimalkan churn.
  
- 🥧 Proporsi Pelanggan per Segmen
  
  ![Image](https://github.com/user-attachments/assets/d744bbb9-bda7-419b-a522-e2c9e267bd5d)
  
  Diagram pie menunjukkan bahwa sekitar **39,9%** pelanggan masuk ke segmen Berpotensi Hilang, menjadikannya kelompok dengan proporsi terbesar. Segmen Hilang dan Loyal masing-masing berkontribusi sekitar **35,3%** dan **24,7%**. Komposisi ini mengindikasikan bahwa sebagian besar pelanggan berada dalam status yang tidak stabil atau rawan pergi.

  Optimalkan pengalaman pelanggan dan berikan insentif loyalitas khusus untuk memperbesar proporsi pelanggan Loyal serta memperkecil porsi pelanggan yang berisiko.


## ▶️ Cara Menjalankan
1. Clone repo ini.
2. Jalankan `RFM_Analysis.ipynb` di Jupyter/Colab.

## 👤 Author
Koko  
Bandung, 2025

## 📄 License
Proyek ini dibuat untuk tujuan edukasi dan portofolio.
