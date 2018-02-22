SOFTWARE REQUIEREMENTS SPECIFICATION ( SRS )

BAB 1 PENDAHULUAN

1.1 Tujuan

Dokumen ini berisi Spesifikasi Kebutuhan Perangkat Lunak (SKPL) atau Software Requirement Spesification (SRS) untuk Aplikasi JAHAT ( Jalan Sehat ) .Tujuan dari penulisan dokumen ini adalah untuk memberikan penjelasan mengenai perangkat lunak yang akan dibangun baik berupa gambaran umum maupun penjelasan detail dan menyeluruh.

Pengguna dari dokumen ini adalah pengembang perangkat lunak aplikasi Jalan Sehat pengguna (user) dari perangkat lunak atau personil-personil yang terlibat dalam sistem.Dokumen ini akan digunakan sebagai bahan acuan dalam proses pengembangan dan sebagai bahan evaluasi pada saat proses pengembangan perangkat lunak maupun di akhir pengembangannya. Dengan adanya dokumen SRS ini diharapkan pengembangan perangkat lunak akan lebih terarah dan lebih terfokus serta tidak menimbulkan ambiguitas terutama bagi pengembang perangkat lunak aplikasi Jalan Sehat.

1.2 Lingkup

Perangkat lunak yang akan dikembangkan adalah perangkat lunak aplikasi Jalan Sehat, yaitu merupakan perangkat lunak yang digunakan untuk mempermudah pengguna (user) mengetahui aktivitas seperti jalan sehat, jogging, maupun bersepeda dengan GPS yang dimana fungsinya adalah memberikan statistik kepada kita tentang kecepatan, jarak, waktu berolahraga kita, serta perhitungan MBR ( Metabolic Basic Rate ) . Aplikasi jalan sehat ini dapat melakukan hal-hal berikut ini :

1.2.1 Fasilitas Login untuk admin dan pengguna ( user )

1.2.2 Melakukan perhitungan MBR ( Metabolic Basic Rate )

1.2.3 Menentukan jalur serta menampilkannya di GPS

1.2.4 Admin dapat melihat, mengedit, menambah dan menghapus pengguna ( user )

1.2.5 Memberikan informasi berupa kandungan kalori pada makanan dan minuman

1.3 Definisi, Akronim, Singkatan

Akronim dan Singkatan :
- APB : Aplikasi Jalan Sehat (JAHAT)
- SRS : Software Requirement Specification
- lot : lokasi penempatan
Definisi :
- Software Requirement Specification adalah perangkat lunak yang akan
dibuat dan sebagai penyembatani komunikasih pembuat dengan
pengguna.
- use case adalah situasi dimana sistem anda digunakan untuk memenuhi
satu atau lebih kebutuhan pemakaian anda.

1.4 Referensi

1.5 Overview

BAB 2 GAMBARAN UMUM

2.1 Perspektif Produk

2.1.1 Antarmuka Sistem

2.1.2 Antarmuka Pengguna

2.1.3 Antarmuka Perangkat Keras

2.1.4 Antarmuka Perangkat Lunak

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
