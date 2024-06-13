# Loan Prediction Based on Customer Behavior
Final Project Bootcamp Data Science Rakamin Academy - Studi Independen Bersertifikat (SIB) Batch 5 

|   	| **Distinct Team**    	|
|---	|----------------------	|
| 1 	| Wahyu Afriza         	|
| 2 	| Alyani Noor Septalia 	|
| 3 	| Bilqis Nafida Azza   	|
| 4 	| Hanif Zaki Nur Fauzi 	|
| 5 	| Muhamad Fahrurrozi   	|
| 6 	| Muhammad Rofi'i      	|
| 7 	| Windy Agelina Manalu 	|

## Dataset
Bersumber dari Kaggle Dataset dengan judul [Loan Prediction Based on Customer Behavior](https://www.kaggle.com/datasets/subhamjain/loan-prediction-based-on-customer-behavior)

## Problem 
Perusahaan melakukan sebagian proses Loan Approval secara manual dan dikerjakan dengan waktu yang cukup lama. Sehingga perusahaan perlu memiliki solusi untuk mengidentifikasi perilaku pelanggan yang cenderung berisiko gagal membayar pengembalian pinjaman untuk meningkatkan efisiensi dan efektivitas baik dalam tenaga kerja, waktu, dan juga cost.

## Insight Summary dari [Exploratory Data Analysis](https://github.com/fahru-razi/Loan_Prediction_Based_on_Customer-Behavior/tree/88ecd0d6d35b4781219d74aa51784914acbc1c54/EDA)
Dalam penentuan pemberian kredit kepada nasabah, dapat menerapkan prinsip analisa 5C yang meliputi Character (Watak), Capacity (Kemampuan), Capital (Modal), Condition (Kondisi), dan Collateral (Jaminan).
  - **Capacity**

    Nasabah dengan penghasilan income Low cenderung lebih tinggi dalam tingkat risiko kredit dengan persentase 15.02% dari total nasabah dengan kategori penghasilan yang sama
    
  - **Capital**

    Dari data didapatkan bahwa nasabah dengan modal atau kepemilikan harta tidak memiliki mobil dan menyewa rumah memiliki angka risiko yang lebih tinggi dengan persentase masing masing yaitu 11.10% dan 12.56% di setiap kategori kelasnya. Dari data data dapat dirumuskan hipotesis dengan pemberian kredit lebih baik diberikan kepada nasabah yang memiliki harta tetap dibandingkan dengan kepemilikan sementara.
  - **Condition**

    Nasabah dengan status single dan rentang usia Millennials cenderung memiliki tingkat resiko cukup tinggi dalam gagal bayar pinjaman dengan persentase daripada nasabah yang sudah menikah dan/atau nasabah berusia selain millennials dengan masing-masing persentase 12.53% dan 13.37%  di setiap kategori kelasnya.
  - **Collateral**

    Nasabah yang menyewa rumah cenderung lebih tinggi untuk tingkat risiko gagal bayar pinjaman dengan persentase 12.56% dari pada nasabah yang memiliki rumah pribadi 9% dan juga nasabah yang belum mempunyai rumah pribadi 9.95%. Sehingga dalam hal ini, lembaga pemberi pinjaman tidak disarankan untuk memberikan pinjaman terutama dalam jumlah banyak kepada nasabah dengan kepemilikan rumah menyewa dan tanpa kepemilikan rumah.
    
Dalam kemampuan nasabah, nasabah dengan income low lebih berpotensi gagal bayar pinjaman dengan persentase 15%, dibanding dengan nasabah yang memiliki income medium 14%, dan income high 12%. Selain itu, pada feature Age tidak ada perbedaan yang signifikan antara 3 generasi yaitu Gen X, Millennials, dan Baby Boomers dengan risiko gagal bayar pinjaman. Dan untuk feature Experience juga tidak ada perbedaan yang signifikan, namun semakin lama pengalaman nasabah maka semakin kecil nasabah berpotensi gagal bayar pinjaman. Begitu juga dengan feature Current_Job_Yrs, tidak ada perbedaan yang signifikan, namun nasabah dengan current job rendah atau junior maka potensi gagal bayar pinjaman lebih tinggi daripada mid-level dan senior.
