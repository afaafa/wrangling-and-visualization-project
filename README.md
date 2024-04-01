

## Data Wrangling and Visualization Project - Analisis Jenis Kendaraan yang Cepat Laku di Pasar Online Platform e-Bay Kleinanzeigen


## A. Latar Belakang

Ebay Kleinanzeigen merupakan platform online yang populer untuk jual-beli barang bekas dan layanan di Jerman. Platform ini digunakan oleh pengguna untuk menawarkan berbagai kategori produk, seperti kendaraan, perumahan, barang elektronik, dan lainnya. Salah satunya adalah jual beli mobil bekas. Manajer tim pemasaran meminta tim data analis untuk melihat tipe kendaraan yang paling laku, dan bagaimana strategi untuk meningkatkan layanan iklan dan kepuasan pengguna dalam jual beli kendaraan di platform e-Bay?

## B. Objektif

* Bagaimana trend distribusi tahun registrasi pada jenis kendaraan?
* Berapa jumlah total kendaraan berdasarkan jenis kendaraan yang tersedia untuk dijual?
* Berapa jumlah Kendaraan berdasarkan merk/brand yang tersedia untuk dijual?
* Berapa harga rata-rata kendaraan berdasarkan jenis kendaraan dan jenis gearbox-nya?
* Berapa harga rata-rata kendaraan menurut jenis bahan bakar dan jenis gearbox-nya?
* Berapa power rata-rata kendaraan menurut jenis kendaraan dan jenis gearbox-nya?
* Berapa harga rata-rata kendaraan menurut merk/brand dan jenis kendaraan?
* Tipe kendaraan apa yang cepat terjual jika melihat jumlah hari dari iklan dipasang?

## C. Goals/Tujuan

meningkatkan layanan iklan dan kepuasan pengguna dalam jual beli kendaraan mobil di platform e-Bay.

## D. Dataset

Dataset yang akan digunakan ini memiliki lebih dari 370.000 mobil bekas dari Ebay-Kleinanzeigen.

Berikut link dataset yang digunakan : https://data.world/data-society/used-cars-data

1. Deskripsi Dataset
- dateCrawled : saat iklan ini pertama kali diunggah, semua nilai bidang diambil dari tanggal ini
- name : nama mobil
- seller : penjual
- offerType : tipe penawaran
- price : harga
- abtest : membandingkan dua versi dari fitur atau spesifikasi yang berbeda untuk melihat mana yang lebih efektif atau diminati oleh konsumen.
- vehicleType : tipe kendaraan
- yearOfRegistration : pada tahun berapa mobil pertama kali didaftarkan
- gearbox : jenis transmisi mobil
- powerPS : kekuatan mobil di PS (Horse Power)
- model
- kilometer : berapa kilometer yang telah ditempuh oleh mobil
- monthOfRegistration : pada bulan berapa mobil pertama kali didaftarkan
- fuelType : jenis bahan bakar yang digunakan
- brand: merek kendaraan
- notRepairedDamage : jika mobil mengalami kerusakan yang belum diperbaiki
- nrOfPicture : jumlah gambar dalam iklan
- postalCode : kode pos
- lastSeenOnline: kapan crawler melihat iklan ini terakhir kali online

## E. Dashboard Visualisasi

Visualisasi yang dibuat menggunakan Tableau

Link Tableau : https://public.tableau.com/app/profile/fathonah.zuchriyah/viz/visualisationproject_17118645651070/Dashboard2#1


## F. Analisis

* Trend tahun registrasi pada jenis kendaraan
  grafik garis menunjukkan seberapa banyak jenis kendaraan yang dijual dan diiklankan berdasarkan tahun registrasi. Kendaran yang memiliki tahun registrasi dari tahun 1910-1995 hanya memiliki sedikit saja dari jumlah jenis kendaraan yang dijual.
  Jenis kendaraan yang tahun registrasinya pada tahun 2000, tercatat ada 21.317 jenis kendaraan yang dijual secara online di platfrom e-Bay.
  Lalu jenis kendaraan yang tahun registrasinya dari tahun 2001-2005 tercatat mengalami penurunan jumlah jenis kendaraan, dan mengalami kenaikan jumlah jenis kendaraan yang tahun registrasinya tahun 2016

* Total ketersediaan jenis kendaraan
  Dari visualisasi tersebut tercatat bahwa total ketersediaan jenis kendaaraan terbanyak dimiliki oleh jenis kendaraan bertipe limousine, yaitu dengan total 56.027 unit. Terendah adalah andere, yaitu 1957 unit.
  Sedangkan jika dilihat berdasarkan brand, terbanyak dimiliki oleh brand volkswagen dengan 42.923 unit, dan terendah dimiliki oleh brand mazda dengan 3.746 unit

* Rata-rata harga kendaraan
  Dari visualiasi tersebut, rata-rata harga kendaraan berdasarkan jenis kendaraan dan gearbox, tertinggi diperoleh jenis kendaraan bertipe suv sebesar 3.849 Euro, dengan gearbox automatic. dapat dilihat bawah harga kendaraan dengan gearbox automatic lebih dominan mahal dibandingkan gearbox manual.
  Rata-rata harga kendaraan berdasarkan tipe bahan bakar, harga tertinggi diperoleh jenis kendaraan bertipe hybrid sebesar 3.29 Euro. untuk jenis gearbox-nya juga lebih dominan dengan tipe automatic.
  Rata-rata harga kendaraan berdasarkan jenis kendaraan dan brand, tertinggi dimiliki oleh jenis kendaraan bertipe cabrio dengan brand mini sebesar 5.730 Euro. dan yang terendah dimiliki oleh jenis kendaraan yang bertipe other dengan brand jaguar sebesar 578 Euro.
  Total rata-rata power kendaraan berdasarkan tipe kendaraan dan gearbox yaitu tertinggi dimiliki oleh jenis kendaraan bertipe suv dengan gearbox automatic sebesar 177.5 PS. dan powerPS dengan gearbox automatic lebih dominan kekuatannya dibandingkan yang lainnya.

* Total distribusi jumlah hari iklan dipasang sebelum terjual
  Dari visualisasi tersebut, dapat dilihat distribusi jumlah hari iklan kendaraan yang dipasang untuk dijual, sebelum kendaraan tersebut terjual.
  dimana analisis yang dipilih berdasarkan brand yang memiliki harga tertinggi dan terendah, yaitu brand mini dan jaguar.

## G. Kesimpulan

## H. Rekomendasi

## I. Stakeholder
Manajer Tim Marketing e-Bay Kleinanzeigen

## J. Link
* Youtube :
* Medium : https://medium.com/@afhazachra/data-wrangling-and-visualization-project-analisis-jenis-kendaraan-yang-cepat-laku-di-pasar-8dfa05889098
* LinkedIn : https://www.linkedin.com/in/fathonah-zuchriyah/
