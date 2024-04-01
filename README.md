

## Data Wrangling and Visualization Project - Analisis Layanan Iklan Berdasarkan Jenis Kendaraan yang Cepat Laku di Pasar Online Platform e-Bay Kleinanzeigen


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

* Analisis 1
  trend tahun registrasi pada jenis kendaraan
  grafik garis menunjukkan seberapa banyak jenis kendaraan yang dijual dan diiklankan berdasarkan tahun registrasi. Kendaran yang memiliki tahun registrasi dari tahun 1910-1995 hanya memiliki sedikit saja dari jumlah jenis kendaraan yang dijual.
  Jenis kendaraan yang tahun registrasinya pada tahun 2000, tercatat ada 6.760 jenis kendaraan yang dijual secara online di platfrom e-Bay.
  Lalu jenis kendaraan yang tahun registrasinya dari tahun 2001-2005 tercatat mengalami penurunan jumlah jenis kendaraan, dan mengalami kenaikan jumlah jenis kendaraan yang tahun registrasinya tahun 2016 sebesar 1293 kendaraan.


* Analisis 2
  Total Ketersediaan jenis kendaraan
  Dari visualisasi tersebut tercatat bahwa total ketersediaan jenis kendaaraan terbanyak dimiliki oleh jenis kendaraan bertipe limousine, yaitu dengan total 26.061 unit. Terendah adalah andere, yaitu 615 unit.

* Analisis 3
  Sedangkan jika dilihat berdasarkan brand, terbanyak dimiliki oleh brand bmw dengan 16.698 unit, dan terendah dimiliki oleh brand porsche dengan 119 unit

* Analisis 4
  Dari visualiasi tersebut, rata-rata harga kendaraan berdasarkan jenis kendaraan dan gearbox, tertinggi diperoleh jenis kendaraan bertipe suv sebesar 4.037 Euro, dengan gearbox automatic. Dapat dilihat bawah harga kendaraan dengan gearbox automatic lebih dominan mahal dibandingkan gearbox manual.

* Analisis 5
  Rata-rata harga kendaraan berdasarkan tipe bahan bakar, harga tertinggi diperoleh jenis kendaraan bertipe hybrid sebesar 3.261 Euro. untuk jenis gearbox-nya juga lebih dominan dengan tipe automatic.

* Analisis 6
  Total rata-rata power kendaraan berdasarkan tipe kendaraan dan gearbox yaitu tertinggi dimiliki oleh jenis kendaraan bertipe andere dengan gearbox not-exit atau tidak diketahui jenisnya sebesar 207.2 PS. dan powerPS dengan gearbox automatic lebih dominan kekuatannya dibandingkan yang lainnya, lalu diikuti dengan gearbox jenis manual.

* Analisis 7
  Rata-rata harga kendaraan berdasarkan jenis kendaraan dan brand, tertinggi dimiliki oleh jenis kendaraan bertipe cabrio dengan brand lada sebesar 5.000 Euro. dan yang terendah dimiliki oleh jenis kendaraan yang bertipe other dengan brand hyundai sebesar 550 Euro.

* Analisis 8
  Dari visualisasi tersebut, dapat dilihat distribusi jumlah hari iklan kendaraan yang dipasang untuk dijual, sebelum kendaraan tersebut terjual.
  dimana analisis yang dipilih berdasarkan brand.

## G. Kesimpulan

* Analisis 1
 tahun 1980-2016 adalah tahun untuk dapat dilakukan penjualan kendaraan. Pada tahun 2000 menjadi tahun tertinggi dengan total  kendaraan 6.760 unit.

* Analisis 2
  total ketersediaan jenis kendaaraan terbanyak dimiliki oleh jenis kendaraan bertipe limousine, yaitu dengan total 26.061 unit. Terendah adalah andere, yaitu 615 unit.

* Analisis 3
  Ketersediaan kendaraan berdasarkan brand, terbanyak dimiliki oleh brand bmw dengan 16.698 unit, dan terendah dimiliki oleh brand porsche dengan 119 unit

* Analisis 4
  rata-rata harga kendaraan berdasarkan jenis kendaraan dan gearbox, tertinggi diperoleh jenis kendaraan bertipe suv sebesar 4.037 Euro, dengan gearbox automatic.

* Analisis 5
  Rata-rata harga kendaraan berdasarkan tipe bahan bakar, harga tertinggi diperoleh jenis kendaraan bertipe hybrid sebesar 3.261 Euro.

* Analisis 6
  Total rata-rata power kendaraan berdasarkan tipe kendaraan dan gearbox yaitu tertinggi dimiliki oleh jenis kendaraan bertipe andere dengan gearbox not-exit atau tidak diketahui jenisnya sebesar 207.2 PS.

* Analisis 7
  Rata-rata harga kendaraan berdasarkan jenis kendaraan dan brand, tertinggi dimiliki oleh jenis kendaraan bertipe cabrio dengan brand lada sebesar 5.000 Euro. dan yang terendah dimiliki tipe other dengan brand hyundai sebesar 550 Euro.

* Analisis 8
  Berdasarkan total hari iklan terpasang, dapat ditemukan bahwa jenis kendaraan berdasarkan brand yang terjual cepat secara online dibandingkan yang lain.

## H. Rekomendasi

Rekomendasi yang tepat untuk manajer tim pemasaran berdasarkan temuan bahwa jenis kendaraan berdasarkan merek yang terjual cepat secara online adalah sebagai berikut:

1. Penekanan pada Iklan Berbasis Merek: Dalam strategi pemasaran online, fokuskan upaya iklan lebih pada merek-merek kendaraan yang telah terbukti terjual dengan cepat. Ini dapat mencakup peningkatan anggaran iklan, peningkatan frekuensi, atau peningkatan kreativitas dalam iklan untuk merek-merek ini.

2. Optimasi Situs Web dan Platform Online: Pastikan bahwa situs web dan platform online Anda dioptimalkan untuk meningkatkan visibilitas dan konversi kendaraan merek yang terjual cepat. Ini mungkin melibatkan peningkatan SEO, tampilan yang lebih menarik, dan navigasi yang intuitif.

3. Analisis Data Lanjutan: Terus pantau dan analisis data penjualan untuk memahami tren lebih lanjut tentang merek-merek kendaraan yang terjual cepat. Ini akan membantu dalam penyesuaian strategi pemasaran secara real-time.

Kolaborasi dengan Pihak Eksternal: bisa melalui kemitraan iklan atau kampanye gabungan lainnya.

4. Personalisasi Konten: Lebih lanjut personalisasikan konten pemasaran untuk target audiens yang cenderung membeli merek kendaraan tertentu. Ini bisa melibatkan penggunaan data pelanggan untuk menyesuaikan pesan iklan.

Dengan menerapkan rekomendasi ini, manajer tim pemasaran dapat memanfaatkan temuan tentang merek kendaraan yang terjual cepat secara online untuk meningkatkan kinerja keseluruhan kampanye pemasaran mereka.

## I. Stakeholder
Manajer Tim Marketing e-Bay Kleinanzeigen

## J. Link
* LinkedIn : https://www.linkedin.com/in/fathonah-zuchriyah/
* Youtube :
* Medium : https://medium.com/@afhazachra/data-wrangling-and-visualization-project-analisis-jenis-kendaraan-yang-cepat-laku-di-pasar-8dfa05889098
