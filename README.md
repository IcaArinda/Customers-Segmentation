# Customer Segmentation Analysis Based on Income and Spending Behavior

## Background
Perusahaan sering mengalami kesulitan dalam mengelompokkan konsumen secara efektif. 
Padahal, segmentasi konsumen penting untuk membantu perusahaan dalam merancang kebijakan 
pemasaran seperti promo, program loyalitas, dan pemberian benefits agar lebih tepat sasaran.

## Data Description
Dataset yang digunakan merupakan data konsumen yang bersumber dari Kaggle (Mall Customers Dataset).
Variabel yang digunakan dalam analisis ini meliputi:
- Gender (dummy variable)
- Annual Income
- Spending Score
Variabel tersebut merepresentasikan karakteristik demografis serta perilaku belanja konsumen.

## Objective
Tujuan dari proyek ini adalah mengelompokkan konsumen ke dalam beberapa segmen berdasarkan 
annual income dan spending score untuk mengidentifikasi perbedaan daya beli dan pola konsumsi 
antar kelompok konsumen.

## Methodology
Analisis dilakukan menggunakan metode K-Means Clustering. 
Jumlah cluster optimal ditentukan menggunakan metode Elbow.

## Key Findings
Hasil segmentasi menunjukkan bahwa konsumen dapat dikelompokkan ke dalam 5 segmen utama 
dengan karakteristik pendapatan dan perilaku belanja yang berbeda.

5 Segmentasi yang dihasilkan sebagai berikut:
1. High Income – High Spending → pelanggan premium
2. High Income – Low Spending → potensial, perlu nurturing
3. Low Income – High Spending → sensitif promo
4. Low Income – Low Spending → low priority
5. Mid Income – Mid Spending → mass market

## Business Insight
Hasil segmentasi ini dapat digunakan oleh perusahaan untuk:
- Menargetkan promo secara lebih efektif
- Mengidentifikasi konsumen berpotensi tinggi
- Menyusun strategi pricing dan loyalty program

## Notebook
Detail analisis dan proses pemodelan dapat dilihat pada file:
- K_MEANS_CUSTOMERS_SEGMENTATION.ipynb
