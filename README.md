# Analisis Transaksi Transportasi Umum Transjakarta di bulan April 2023 - Dummy Data

## Links

---

[Data Source](https://www.kaggle.com/datasets/dikisahkan/transjakarta-transportation-transaction)

[Tableau](https://public.tableau.com/app/profile/nadia.syailendra8148/viz/TransjakartaDashboard_17757520465640/TransjakartaDashboard)

## Overview

---

In this project, I performed an end-to-end analysis process, including gathering business requirements, data cleaning, exploratory data analysis, statistical analysis, and developing interactive dashboards using Tableau. 

## Business Understanding

---

Tidak seperti bisnis komersil, transportasi publik umumnya tidak berusaha memaksimalkan profit, melainkan fokus terhadap mobilitas penumpang. 

Transportasi publik memudahkan penumpang menuju tujuannya secara efisien, aman dan dengan harga terjangkau.

### Problem Statement

---

Menganalisis rute koridor, arah rute dan jam-jam dimana jumlah penumpang tinggi pada transportasi Transjakarta selama bulan April 2023.

Tujuan: Analisis ini akan digunakan oleh operator Transjakarta untuk meningkatkan operasional yang lebih efisien dan nyaman 


### Key Questions

---

1. Rute koridor apa yang paling ramai penumpang?
2. Rute koridor cenderung ramai di arah pergi atau arah pulang?
3. Kapan jam sibuk (peak hour) terjadi?
4. Halte apa penumpang paling banyak naik?
5. Bagaimana distribusi usia penumpang transjakarta?
6. Apakah rata-rata waktu tempuh saat weekend lebih cepat dari weekday?


### Tools

---

Programming Language: Python, SQL

Library: Pandas

Visualization: Tableau

Presentation Slides: Canva


## Hasil Analisis

---

1. Rute yang paling ramai?
Rute koridor Cibubur - Balai Kota

2. Lebih ramai mana, rute arah pergi atau pulang?
Rute arah berangkat dan arah pulang memiliki jumlah penumpang yang hampir sama (konsisten)

3. Kapan peak hour nya?
Jam 5 - 9 di pagi hari dan 4 - 9 di malam hari

4. Halte apa yang paling ramai?
Halte Penjaringan

5. Mean penumpang Transjakarta 35

6. Menggunakan uji T-test untuk mengetahui apakah rata-rata waktu tempuh saat weekend lebih cepat dari weekday menghasilkan p-value 0.04 < 0.05

## Kesimpulan

---

Penumpang Transjakarta adalah warga Jabodetabek yang tinggal di daerah padat penduduk 

Penumpang menggunakan Transjakarta sebagai moda transportasi pilihan untuk pergi bekerja pada hari kerja atau berpergian ke daerah pusat kota di akhir pekan

Rata-rata penumpang berada dalam usia produktif yaitu 35-36 tahun


## Rekomendasi

---

Perencanaan alokasi bus sesuai dengan rute koridor dan peak hour agar penumpang nyaman dan tidak berdesakan di halte dan bus 

Penambahaan layanan feeder atau mikrotrans yang bisa lebih menjangkau ke daerah perumahan yang padat penduduk untuk kemudian diintegrasikan ke halte BRT terdekat

Mempertahankan layanan Transjakarta yang sudah bagus menghubungkan kehidupan penumpangnya
