
<center><h2><b>Software Requirements Specification</h2></b>

<h3>Versi 1.2

<h3>2 Februari 2018
 
 ![](http://i68.tinypic.com/24fbuvd.png)


<h2>Aplikasi Pola Hidup Sehat ( Pahat )</h2>

Nama Kelompok : <br>

Arie Fahmi Luthfi<br>Diky Anwar<br>Shafa Dhiyanti<br>Stephan Dwiki Alkine

Jurusan D3 Teknik Informatika
<br>Politeknik Negeri Indramayu
<br>2017
</center>

<b>1. Pendahuluan</b>

1.1. Tujuan

Dokumen ini berisi Spesifikasi Kebutuhan Perangkat Lunak (SKPL) atau Software Requirement Spesification (SRS) untuk Aplikasi Pola Hidup
Sehat (Pahat). Tujuan dari penulisan dokumen ini adalah untuk memberikan penjelasan mengenai perangkat lunak yang akan 
dibangun baik berupa gambaran umum maupun penjelasan detail dan menyeluruh.

Pengguna dari dokumen ini adalah pengembang perangkat lunak aplikasi Pola Hidup Sehat pengguna (user) dari perangkat lunak atau 
personil-personil yang terlibat dalam sistem. Dokumen ini akan digunakan sebagai bahan acuan dalam proses pengembangan dan sebagai bahan 
evaluasi pada saat proses pengembangan perangkat lunak maupun di akhir pengembangannya. Dengan adanya dokumen SRS ini diharapkan 
pengembangan perangkat lunak akan lebih terarah dan lebih terfokus serta tidak menimbulkan ambiguitas terutama bagi pengembang 
perangkat lunak aplikasi Pola Hidup Sehat.

1.2. Lingkup

Perangkat lunak yang akan dikembangkan adalah perangkat lunak aplikasi Pola Hidup Sehat, yaitu merupakan perangkat lunak yang digunakan 
untuk mempermudah pengguna (user) mengetahui aktivitas seperti jalan sehat, jogging, maupun bersepeda dengan GPS yang dimana fungsinya 
adalah memberikan statistik kepada kita tentang kecepatan, jarak, dan waktu berolahraga kita, serta perhitungan BMR (Basal Metabolic Rate).
Aplikasi ini dapat melakukan hal-hal berikut ini :

1.2.1 Fasilitas Login untuk pengguna (user)

1.2.2 Melakukan perhitungan BMR (Basal Metabolic Rate)

1.2.3 Menentukan jalur serta menampilkannya di GPS

1.2.4 Memberikan informasi berupa kandungan kalori pada makanan dan minuman

1.3. Definisi, akronim, singkatan

Definisi :

Software Requirement Specification adalah perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasih pembuat dengan pengguna.
Use case adalah situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda. 
Akronim dan Singkatan :
Pahat : Aplikasi Pola Hidup Sehat
SRS : Software Requirement Specification
lot : lokasi penempatan

1.4. Referensi

Nazruddin Safaat H, Android : Pemrograman Aplikasi Mobile Smartphone dan Tablet PC Berbasis Android (Revisi 2). Informatika.2014.

1.5. Overview

- Bagian pertama berisi penjelasan tentang dokumen SPL yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan oleh
perangkat lunak yang dikembangkan, definisi, referensi dan deskripsi umum.

- Bagian kedua berisi penjelasan secara umum mengenai perangkat lunak Pola Hidup Sehat yang akan dikembangkan, meliputi fungsi dari 
perangkat lunak, karakteristik pengguna, batasan dan asumsi yang diambil dalam pengembangan perangkat lunak.

- Bagian ketiga berisi uraian kebutuhan perangkat lunak secara lebih detail.

<b>2. Gambaran Umum</b>

Tuliskan produk secara umum dan hindari penulisan pernyataan yang berulang dan
ambigu (harus jelas subjek predikat dan objeknya)

2.1. Perspektif produk

Perangkat lunak yang dibuat (disebut dengan PAHAT) merupakan sebuah perangkat lunak yang digunakan untuk membantu melakukan proses pola 
hidup sehat dengan memantau aktifitas olahraga serta memantau asupan yang dikonsumsi.

Prosesnya dimana user bisa memilih olahraga yang diinginnkan lalu dapat melihat jalur olahraganya serta memberikan informasi berapa 
jarak yang sudah ditempuh dan berapa kalori yang sudah terbakar.Selanjutnya dimana si user bisa memantau asupannya dengan kita melakukan
perhitungan BMR.

2.1.1. Antarmuka sistem

![](http://i66.tinypic.com/503g5.png)

2.1.2. Antarmuka pengguna

Aplikasi ini dikembangkan dalam bentuk aplikasi android. Perangkat lunak ini dilengkapi dengan menu untuk pengaksesan berbagai
fungsi yang disediakan. Interaksi antara pengguna dan perangkat lunak dilakukan dengan menggunakan smartphone.


<center>

![](http://i65.tinypic.com/30v2lgp.png) 

![](http://i64.tinypic.com/mifnr8.png)

[](http://i66.tinypic.com/2lbiziq.png)

![](http://i67.tinypic.com/4kwxa0.png)

![](http://i67.tinypic.com/jtmfyf.png)

![](http://i67.tinypic.com/4g4y8n.png)

![](http://i66.tinypic.com/2vt8o6g.png)

![](http://i68.tinypic.com/sqj9ty.png)

![](http://i64.tinypic.com/2nl7dr8.png)

![](http://i67.tinypic.com/2me35t3.png)

![](http://i67.tinypic.com/2u8h4ox.png)

![](http://i65.tinypic.com/mli0qu.png)

![](http://i66.tinypic.com/ix5qtk.png)

![](http://i65.tinypic.com/nrzvc.png)

![](http://i66.tinypic.com/5c0jl3.png)

</center>


2.1.3. Antarmuka perangkat keras
Kebutuhan minimum perangkat keras yang dapat digunakan adalah:


- Seperangkat komputer


- Smartphone 

Semua perangkat keras yang digunakan merupakan perangkat standar dalam sistem komputer dan
menggunakan port standar yang ada. 

2.1.4. Antarmuka perangkat lunak

Perangkat lunak yang diperlukan oleh aplikasi ini adalah:


- Mobile Aplikasi Pola Hidup Sehat

2.1.5. Antarmuka komunikasi

Aplikasi ini menggunakan internet untuk menjalankannya. 

2.1.6. Batasan memori


2.1.7. Operasi-operasi

- Login melalui mobile

- Pilih olahraga

- Hitung BMR

- Data Kalori

2.1.8. Kebutuhan adaptasi



2.2. Spesifikasi Kebutuhan fungsional

![](http://i67.tinypic.com/awh1c.png)

2.3. Spesifikasi kebtuhan non-fungsinoal

- Design layout mobile

2.4. Karakteristik pengguna

Karakteristik pengguna dari Aplikasi Pola Hidup Sehat ini adalah semua yang ingin menggunakannya untuk menerapkan pola hidup sehat dengan berolahraga dan mengatur pola makan.

2.5. Batasan-batasan

- Aplikasi Pahat ini belum bisa membagikan kegiatan kita ke media sosial.


2.6. Asumsi-asumsi keterkaitan


2.7. Kebutuhan penyeimbang


<b>3.Deskripsi Rinci Kebutuhan</b>

3.1 Kebutuhan antarmuka eksternal

Kebutuhan antarmuka eksternal pada perangkat lunak Aplikasi Hidup Sehat mencakup kebutuhan antarmuka pemakai, antarmuka perangkat keras, dan antarmuka perangkat lunak.


3.2 Kebutuhan Fungsional

Kebutuhan Fungsional adalah kebutuhan yang harus dipenuhi agar suatu sistem dapat berjalan atau dapat dikatakan kebutuhan tambahan yang memiliki input, proses, dan output. Kebutuhan fungsional yang harus ada dalam sistem yang akan dikembangkan ini adalah sebagai berikut:

1.	Sistem harus dapat menyediakan informasi mengenai pola hidup sehat secara lebih detail, cepat dan efektif.
2.	Sistem harus dapat mempermudah user dalam proses kegiatan olahraga. 

Aktor yang ada dalam dalam lingkup sistem adalah

a.	User

Yang dilakukan adalah : Login, Melakukan kegiatan kegiatan pola hidup sehat (berjalan, berlari, bersepeda dll), dan Memilih menu-menu yang tersedia

3.2.1 Memilih olahraga

3.2.2 Menampilkan jalur olahraga

3.2.3 Melakukan Perhitungan BMR

3.2.4 Melihat data kandungan kalori

3.2.5 Menghitung konsumsi kalori

3.2.6 Menampilkan jarak dan kalori yang terbakar saat olahraga

3.2.7 Menampilkan laporan kalori user

3.3 Persyaratan Non-fungsional yang Rinci

3.3.1 Structur Logis dari Data

![](http://i68.tinypic.com/2jacnth.png)

3.3.2 Keamanan

Untuk memproteksi perangkat lunak dari akses, penggunaan, penghancuran atau pengungkapan (disclosure) yang tidak sengaja atau yang merusak. Kebutuhan yang spesifik termasuk hal-hal berikut :

1.	Adanya backup data sehingga data lebih reliable
2.	Penyimpanan data log/history
3.	Pemberian suatu fungsi ke modul-modul yang berbeda
4.	Pembatasan komunikasi terhadap suatu area tertentu dalam program,
5.	Pemeriksaan integritas data peubah-peubah kritis

3.3.3 Pemeliharaan

Adanya pemeliharaan dan pengecekan berkala dan terus-menerus yang akan dilakukan terhadap program yang berjalan ataupun pengecekan baik terhadap perangkat lunak itu sendiri ataupun hardware yang digunakan. Untuk pemeliharaan tiap harinya, system ini dilengkapi antivirus sehingga meminimalkan kerusakan pada system serta terdapat back up data untuk mencegah hal-hal yang tidak terduga yang tidak diinginkan

<b>4. Informasi Pendukung</b>
