# proyekvisdat
Dokumentasi proyek visualisasi data pembuatan Dashbord visualisasi Data Penyebab Kematian di Indonesia Tahun 2000-2022

## Dataset
Data yang digunakan berasal dari Kaggle dengan judul Cause of Death in Indonesia (https://www.kaggle.com/datasets/hendratno/cause-of-death-in-indonesia) yang berisi kumpulan data dari Publikasi Profil Kesehatan Indonesia untuk tahun 2000 sampai tahun 2021 dan data yang berasal dari website covid19.go.id terkait data kematian yang disebabkan oleh covid19.
Data dari Publikasi Profil Kesehatan Indonesia tahun 2000 sapai tahun 2021 dipublikasikan di website resmi kemetrian kesehatan (https://pusdatin.kemkes.go.id/download.php?file=download/pusdatin/profil-kesehatan-indonesia/).

## Visualisai Data
### Data type (jenis penyebab kematian) 
Divisualisasikan dengan bentuk tabel untuk setiap. Bentuk tabel dipilih karena tujuan dari visualsasi data type adalah menunjukkan banyaknya jumlah kematian untuk bencana non alam dan penyakit, bencana alam, dan bencana sosial.
![type](https://user-images.githubusercontent.com/107907913/174727089-08a1adea-9416-4ab7-b910-be50625c8af5.jpg)

### Data cause (penyebab kematian) 
Divisualisasikan dengan treemap. Visualisasi ini dipilih karena tujuan dari visualisasi data tersebut adalah untuk memperlihatkan banyaknya kematian berdasarkan penyebabkan, Selain itu karena treemap merupakan cara visualisasi yang efisien untuk merepresentasikan data hirearki. Dimensi dari kotak dan warnanya membantu untuk secara langsung membandingkan antar penyebab kematian.
![cause](https://user-images.githubusercontent.com/107907913/174727246-d8c0f966-72d3-46e0-8ade-fdcdaf75a593.jpg)

### Data type (jenis penyebab kematian) dan cause (penyebab 
kematian) 
Divusialisasikan Bersama untuk melihat banyaknya jumlah kematian berdasarkan penyebab dalam setiap jenis penyebab.
![typecause](https://user-images.githubusercontent.com/107907913/174727378-8cf834c1-a409-4d9c-820c-a0f55dc52fee.jpg)

### Data laju jumlah kematian berdasarkan penyebab 
Divisualisasikan menggunakan line chart. Jenis visualisasi ini dipilih karena dengan line chart dapat dilihat perubahan jumlah kematian untuk setiap penyebab dari tahun ke tahun.
![laju](https://user-images.githubusercontent.com/107907913/174727443-0d9c2125-bcc3-4aff-815d-e8467053369b.jpg)

## Dashboard
![dashboard](https://user-images.githubusercontent.com/107907913/174727647-96854ad2-482b-4eea-87d8-fafdc1db402d.jpg)
Dashboard tersebut selain menyatukan semua visualisasi menjadi satu juga terdapat filter tahun untuk menunjukkan data pada tahun tertentu. Di bawah filter tahun juga terdapat legenda yang berisi keterangan setiap penyebab kematian.
