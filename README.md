Proyek segmentasi pelanggan coffee shop menggunakan metode RFM berdasarkan data transaksi bulan Maret 2024. \n

Tujuan utama dari analisis ini adalah untuk memahami pola perilaku pelanggan dan mengelompokkan mereka ke dalam segmen yang relevan, sehingga dapat membantu dalam penyusunan strategi pemasaran yang lebih efektif dan terarah. \n

Sumber dataset:
https://www.kaggle.com/datasets/reignrichard/coffee-store-sales 

Analisis dilakukan melalui beberapa tahapan. Tahap pertama adalah data cleaning dimana dilakukan penanganan missing value pada kolom customer ID, mengingat tanpa identifikasi pelanggan yang jelas, analisis segmentasi tidak dapat dilakukan. Selanjutnya dilakukan perhitungan nilai RFM yang terdiri dari Recency (waktu sejak transaksi terakhir), Frequency (jumlah transaksi per pelanggan), dan Monetary (total nilai pembelian per pelanggan). Berdasarkan skor RFM yang diperoleh, pelanggan kemudian dikelompokkan ke dalam tiga segmen utama yaitu Loyal, Biasa, dan Rendah. \n

Berdasarkan hasil analisis, terdapat 244 pelanggan (18.5%) yang tergolong dalam segmen Loyal, 558 pelanggan (42.4%) dalam segmen Biasa, dan 514 pelanggan (39.1%) dalam segmen Rendah. Masing-masing segmen menunjukkan karakteristik yang berbeda-beda. Pelanggan segmen Loyal merupakan yang paling aktif dengan recency rata-rata 60 hari, frekuensi transaksi 7.2 kali, dan kontribusi monetary sebesar $225.827. Segmen Biasa menunjukkan perilaku menengah dengan recency 157 hari, frekuensi 2.3 kali, dan monetary $73.256. Sementara segmen Rendah memiliki recency tertinggi 240 hari, frekuensi hanya 1 kali, dan monetary terendah $31.647. \n

<img width="1291" height="611" alt="image" src="https://github.com/user-attachments/assets/9e7d5980-6c4c-485a-bc88-5aeab6060d6d" /> \n

Dari hasil segmentasi ini, dapat digunakan beberapa insight bisnis yang cocok. Untuk segmen Loyal, saya sarankan untuk memberikan program loyalitas eksklusif dan penawaran produk premium terbaru. Untuk pelanggan segmen Biasa perlu ditingkatkan frekuensi kunjungannya melalui promo menarik untuk meningkatkan repeat order, sekaligus mengoptimalkan pengalaman berbelanja agar dapat dikonversi menjadi pelanggan Loyal. Sedangkan segmen Rendah memerlukan upaya reaktivasi dengan penawaran spesial dan evaluasi penyebab churn untuk meningkatkan customer retention. \n

Kemudian hasil analisis yang sudah saya lakukan di google colab, saya visualisasi menggunakan Power BI \n

<img width="913" height="523" alt="image" src="https://github.com/user-attachments/assets/4dc48d2b-c3f0-4d77-a286-8c60d6bc9ad3" />
