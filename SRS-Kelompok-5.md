SOFTWARE REQUIEREMENTS SPECIFICATION ( SRS )

BAB 1 PENDAHULUAN

1.1 Tujuan

Dokumen ini berisi Spesifikasi Kebutuhan Perangkat Lunak (SKPL) atau Software Requirement Spesification (SRS) untuk Aplikasi Pola Hidup Sehat ( Pola Hidup Sehat ) .Tujuan dari penulisan dokumen ini adalah untuk memberikan penjelasan mengenai perangkat lunak yang akan dibangun baik berupa gambaran umum maupun penjelasan detail dan menyeluruh.

Pengguna dari dokumen ini adalah pengembang perangkat lunak aplikasi Pola Hidup Sehat pengguna (user) dari perangkat lunak atau personil-personil yang terlibat dalam sistem.Dokumen ini akan digunakan sebagai bahan acuan dalam proses pengembangan dan sebagai bahan evaluasi pada saat proses pengembangan perangkat lunak maupun di akhir pengembangannya. Dengan adanya dokumen SRS ini diharapkan pengembangan perangkat lunak akan lebih terarah dan lebih terfokus serta tidak menimbulkan ambiguitas terutama bagi pengembang perangkat lunak aplikasi Pola Hidup Sehat.

1.2 Lingkup

Perangkat lunak yang akan dikembangkan adalah perangkat lunak aplikasi Pola Hidup Sehat, yaitu merupakan perangkat lunak yang digunakan untuk mempermudah pengguna (user) mengetahui aktivitas seperti jalan sehat, jogging, maupun bersepeda dengan GPS yang dimana fungsinya adalah memberikan statistik kepada kita tentang kecepatan, jarak, waktu berolahraga kita, serta perhitungan BMR ( Basal Metabolic Rate ) . Aplikasi ini dapat melakukan hal-hal berikut ini :

1.2.1 Fasilitas Login untuk pengguna ( user )

1.2.2 Melakukan perhitungan BMR ( Basal Metabolic Rate )

1.2.3 Menentukan jalur serta menampilkannya di GPS

1.2.4 Memberikan informasi berupa kandungan kalori pada makanan dan minuman

1.3 Definisi, Akronim, Singkatan

Akronim dan Singkatan :
- Pahat : Aplikasi Pola Hidup Sehat
- SRS 	 : Software Requirement Specification
- lot 	 : lokasi penempatan

Definisi :
- Software Requirement Specification adalah perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasih pembuat dengan pengguna.
- Use case adalah situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda.

1.4 Referensi
Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah :
1. Nazruddin Safaat H, *Android : Pemrograman Aplikasi Mobile Smartphone dan Tablet PC Berbasis Android (Revisi 2)*. Informatika.2014.

1.5 Overview

- Bagian pertama berisi penjelasan tentang dokumen SPL yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan oleh perangkat lunak yang dikembangkan, definisi, referensi dan deskripsi umum.

- Bagian kedua berisi penjelasan secara umum mengenai perangkat lunak Pola Hidup Sehat yang akan dikembangkan, meliputi fungsi dari perangkat lunak, karakteristik pengguna, batasan dan asumsi yang
diambil dalam pengembangan perangkat lunak.

- Bagian ketiga berisi uraian kebutuhan perangkat lunak secara lebih detail. 
 

BAB 2 GAMBARAN UMUM

2.1 Perspektif Produk

Perangkat lunak yang dibuat (disebut dengan PAHAT) merupakan sebuah perangkat lunak yang digunakan untuk membantu melakukan proses pola hidup sehat dengan memantau aktifitas olahraga serta memantau asupan yang dikonsumsi.

Prosesnya dimana user bisa memilih olahraga yang diinginnkan lalu dapat melihat jalur olahraganya serta memberikan informasi berapa jarak yang sudah ditempuh dan berapa kalori yang sudah terbakar.Selanjutnya dimana si user bisa memantau asupannya dengan kita melakukan perhitungan BMR.


2.1.1 Antarmuka Sistem

2.1.2 Antarmuka Pengguna

Aplikasi ini dikembangkan dalam bentuk aplikasi android. Perangkat lunak ini dilengkapi dengan menu untuk pengaksesan berbagai
fungsi yang disediakan. Interaksi antara pengguna dan perangkat lunak dilakukan dengan menggunakan smartphone. 

2.1.3 Antarmuka Perangkat Keras

Kebutuhan minimum perangkat keras yang dapat digunakan adalah:

1. Seperangkat komputer

2. Smartphone 

Semua perangkat keras yang digunakan merupakan perangkat standar dalam sistem komputer dan
menggunakan port standar yang ada. 

2.1.4 Antarmuka Perangkat Lunak

Perangkat lunak yang diperlukan oleh aplikasi ini adalah:

1. Sistem Operasi Windows.

2. Browser Internet (Internet Explorer, Opera, Firefox, dll)


2.1.5 Antarmuka Komunikasi

2.1.6 Batasan-batasan Memori

2.1.7 Operasi-operasi

2.1.8 Kebutuhan-kebutuhan dalam tahapan adaptasi

2.2 Fungsi-fungsi Produk

2.3 Karakteristik Pengguna

2.4 Batasan-batasan

2.5 Asumsi-asumsi dan ketergantungan/keterkaitan

2.6 Kebutuhan-kebutuhan penyeimbang

BAB 3 KEBUTUHAN LAIN YANG SPESIFIK

Berikut adalah kebutuhan perangkat lunak untuk perancang sistem aplikasi Jalan Sehat, diantaranya yaitu sebagai berikut :

3.1 Kebutuhan Antarmuka Eksternal

Akan disediakan penjelasan rinci dari semua masukan (input) dan luaran (output) dari aplikasi Jalan Sehat

3.1.1 Daftar Masukan

Daftar berbeda dari setiap modulnya, yang diberikan sebagai berikut.

3.1.1.1 Module Login

Disini User / pengguna diwajibkan untuk menginputkan email dan sandi

3.1.1.2 Module Menu

Disini User / Pengguna setelah berhasil login yaitu memilih menu

3.1.2 Daftar Keluaran

3.1.2.1 Laporan Hasil

Disini user mendapatkan segala informasi ketika selesai melakukan kegiatan olahraga

3.1.2.2 Laporan Penyimpanan

Disini Data hasil dari kegiatan selama olahraga akan disimpan dalam database


BAB 4 INFORMASI PENDUKUNG
