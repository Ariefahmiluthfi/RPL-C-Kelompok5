<html>
<body>
<div align="center"><h1> Software Requirements Specification</h1></div>

<p align="center"><b>Version 1.2 </b><br>
<p align="center">22 Februari 2018</b>
<p align="center">
<img src="https://2.bp.blogspot.com/-dxdRgMQGbLk/WpA-Tp2rNGI/AAAAAAAAAh8/3_jBWFb7Cf48033QvB34D2WCwoN2sxZLgCLcBGAs/s1000/index.png"/>
</p>


<p align="center"><b>Aplikasi Pola Hidup Sehat ( PAHAT )
</b>
<p align="center">Kelompok 5 <br>
 Arie Fahmi Luthfi 				(1603064)<br>
 Diky Anwar		(1603065)<br>
 Shafa Dhiyanti			(1603083)<br>
 Stephan Dwiki Alkine			(1603085)<br><br><br>

<p align="center"><b>Jurusan Teknik Informatika</b><br>
<p align="center"><b>Politeknik Negeri Indramayu</b>
<p align="center"><b>2018</b>
</p>
</body>
</html>

<b><h4>BAB 1. PENDAHULUAN</h4></b>

<b>1.1. Tujuan</b>

Dokumen ini berisi Spesifikasi Kebutuhan Perangkat Lunak (SKPL) atau Software Requirement Spesification (SRS) untuk Aplikasi Pola Hidup
Sehat (Pahat). Tujuan dari penulisan dokumen ini adalah untuk memberikan penjelasan mengenai perangkat lunak yang akan 
dibangun baik berupa gambaran umum maupun penjelasan detail dan menyeluruh.

Pengguna dari dokumen ini adalah pengembang perangkat lunak aplikasi Pola Hidup Sehat pengguna (user) dari perangkat lunak atau 
personil-personil yang terlibat dalam sistem. Dokumen ini akan digunakan sebagai bahan acuan dalam proses pengembangan dan sebagai bahan 
evaluasi pada saat proses pengembangan perangkat lunak maupun di akhir pengembangannya. Dengan adanya dokumen SRS ini diharapkan 
pengembangan perangkat lunak akan lebih terarah dan lebih terfokus serta tidak menimbulkan ambiguitas terutama bagi pengembang 
perangkat lunak aplikasi Pola Hidup Sehat.

<b>1.2. Lingkup</b>

Perangkat lunak yang akan dikembangkan adalah perangkat lunak aplikasi Pola Hidup Sehat, yaitu merupakan perangkat lunak yang digunakan 
untuk mempermudah pengguna (user) mengetahui aktivitas seperti jalan sehat, jogging, maupun bersepeda dengan GPS yang dimana fungsinya 
adalah memberikan statistik kepada kita tentang kecepatan, jarak, dan waktu berolahraga kita, serta perhitungan BMR (Basal Metabolic Rate).
Aplikasi ini dapat melakukan hal-hal berikut ini :

1.2.1 Fasilitas Login untuk pengguna (user)

1.2.2 Melakukan perhitungan BMR (Basal Metabolic Rate)

1.2.3 Menentukan jalur serta menampilkannya di GPS

1.2.4 Memberikan informasi berupa kandungan kalori pada makanan dan minuman

<b>1.3. Definisi, akronim, singkatan</b>

Definisi :

Software Requirement Specification adalah perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasih pembuat dengan pengguna.
Use case adalah situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda. 
Akronim dan Singkatan :
Pahat : Aplikasi Pola Hidup Sehat
SRS : Software Requirement Specification
lot : lokasi penempatan

<b>1.4. Referensi </b>

Nazruddin Safaat H, Android : Pemrograman Aplikasi Mobile Smartphone dan Tablet PC Berbasis Android (Revisi 2). Informatika.2014.

<b>1.5. Overview</b>

- Bagian pertama berisi penjelasan tentang dokumen SPL yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan oleh
perangkat lunak yang dikembangkan, definisi, referensi dan deskripsi umum.

- Bagian kedua berisi penjelasan secara umum mengenai perangkat lunak Pola Hidup Sehat yang akan dikembangkan, meliputi fungsi dari 
perangkat lunak, karakteristik pengguna, batasan dan asumsi yang diambil dalam pengembangan perangkat lunak.

- Bagian ketiga berisi uraian kebutuhan perangkat lunak secara lebih detail.

<b><h4>BAB 2.GAMBARAN UMUM</h4></b>

Tuliskan produk secara umum dan hindari penulisan pernyataan yang berulang dan
ambigu (harus jelas subjek predikat dan objeknya)

<b>2.1. Perspektif produk</b>

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



<b>2.2. Spesifikasi Kebutuhan fungsional</b>

![](http://i67.tinypic.com/awh1c.png)

<b>2.3. Spesifikasi kebtuhan non-fungsinoal</b>



- Design layout mobile

<b>2.4. Karakteristik pengguna</b>

Karakteristik pengguna dari Aplikasi Pola Hidup Sehat ini adalah semua yang ingin menggunakannya untuk menerapkan pola hidup sehat dengan berolahraga dan mengatur pola makan.

<b>2.5. Batasan-batasan</b>

- Aplikasi Pahat ini belum bisa membagikan kegiatan kita ke media sosial.


<b>2.6. Asumsi-asumsi keterkaitan</b>


<b>2.7. Kebutuhan penyeimbang</b>


<b><h4>BAB 3.DESKRIPSI RINCI KEBUTUHAN</h4></b>

<b>3.1 Kebutuhan antarmuka eksternal</b>

Kebutuhan antarmuka eksternal pada perangkat lunak Aplikasi Hidup Sehat mencakup kebutuhan antarmuka pemakai, antarmuka perangkat keras, dan antarmuka perangkat lunak.


<b>3.2 Kebutuhan Fungsional</b>

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

<b>3.3 Persyaratan Non-fungsional yang Rinci</b>

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

<b><h4>BAB 4.INFORMASI PENDUKUNG</h4></b>
