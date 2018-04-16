<html>
<body>
<div align="center"><h1> Software Design Description</h1></div>

<p align="center"><b>Version 1.0 </b><br>
<p align="center">5 Maret 2018</b>
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

<b><h4>BAB 1.PENDAHULUAN</b></h4>

<b>1.1 Tujuan</b>

Tujuan pembuatan SDD (Software Design Description) ini adalah untuk menjelaskan langkah-langkah desain dan proses-proses dalam pembuatan sistem aplikasi yang akan diterapkan pada Aplikasi Pola Hidup Sehat berbasis Android, dan juga memberi definisi kebutuhan untuk sistem, spesifikasi kebutuhan fungsional.

Dokumen perancangan ini dibuat berdasarkan spesifikasi kebutuhan Aplikasi Pola Hidup Sehat berbasis Android yang akan dibuat. Dalam rangka membangun aplikasi tersebut, tentunya deskripsi perancangan untuk aplikasi tersebut dibutuhkan, khususnya oleh para pengembang dan pembangun aplikasi tersebut.

Aplikasi Pola Hidup Sehat ini memudahkan kita untuk mengetahui aktivitas seperti jalan maupun jogging dengan GIS (Geographic Informatic System) yang dimana fungsinya memberikan statistik kepada kita tentang kecepatan, jarak dan waktu berolahraga kita. Selain itu aplikasi ini juga bisa melakukan perhitungan BMR (Basal Metabolic Rate) agar kita menerapkan pola hidup yang sehat.

<b>1.2 Lingkup</b>

Aplikasi Pola Hidup Sehat (Pahat) adalah sebuah aplikasi berbasis android yang mempermudah masyarakat menerapkan pola hidup sehat. Penggunaan aplikasi ini dengan Login melalui email, memilih olahraga, melakukan perhitungan BMR, melihat daftar kandungan kalori pada makanan dan minuman, menghitung konsumsi kalori, dan melihat hasil kalori dari tubuh kita. Aplikasi ini hanya menggunakan 1 user.

<b>1.3 Definisi, Akronim dan Singkatan</b>

| Definisi, Akronim dan Singkatan | Penjelasan |
| ----- | ----- |
| DFD | Data Flow Diagram. Diagram yan menggambarkan aliran data |
| ERD | Entity Relationship Diagram. Diagram yang menggambarkan entitas suatu objek beserta relasinya |
| SKPL | Spesifikasi Kebutuhan Perangkat Lunak. Sebuah dokumen yang berisi analisis terhadap suatu perangkat lunak yang akan dibangun yang dijabarkan dalam suatu spesifikasi kebutuhan. |
| SDD | Software Design Description. Dokumen untuk menjelaskan langkah-langkah desain dan proses-proses dalam pembuatan sistem aplikasi yang akan diterapkan pada aplikasi. |
| User | Pengguna aplikasi |

<b>1.4 Referensi</b>

Dokumen ini memiliki beberapa referensi dalam pembuatannya, yaitu sebagai berikut:


- IEEE Draft Standard for Software Design Descriptions

<b>1.5 Ikhtisar Dokumen</b>

Dokumen SDD ini berisi deskripsi rancangan perangkat lunak yang akan dikembangkan berdasarkan dokumen SRS. Dalam dokumen SDD ini dijabarkan perincian rancangan perangkat lunak yang dikembangkan, sehingga dapat diimplementasikan hingga level teknis. Gambaran umum dokumen ini terdapat pada penjelasan dibawah ini .

a. Bab 1, merupakan bab pendahuluan yang berisikan tentang overview dari rencana pengembangan perangkat lunak secara umum, seperti tujuan penulisan dokumen, lingkup masalah, definisi dan istilah, serta referensi.

b. Bab 2, merupakan deskripsi perancangan global yang berisi tentang perancangan perangkat lunak secara umum seperti lingkungan operasi yang akan digunakan untuk implementasi perangkat lunak, pemodelan data-data yang akan digunakan dalam perangkat lunak, dan daftar tabel yang digunakan sebagai database dalam perangkat lunak yang dikembangkan.

c. Bab 3, merupakan deskripsi perancangan rinci yang berisi tentang rincian keseluruhan atau detail menyeluruh dari perangkat lunak yang akan dikembangkan, seperti pendeskripsian secara rinci database yang akan digunakan didalam perangkat lunak dan rincian pemrosesan yang terjadi didalam perangkat lunak yang dikembangkan.

<b><h4>BAB 2.DESKRIPSI PERANCANGAN GLOBAL</b></h4>

<b>2.1 Rancangan Lingkungan Implementasi</b>

Aplikasi Pola Hidup Sehat akan dikembangkan menjadi perangkat lunak berbasis android yang membutuhkan komputer dengan spesifikasi sebagai berikut :

- Sistem Operasi  : Windows, Android

- DBMS	: Firebase

- Tools	: Android Studio, Edraw Max

- Bahasa pemrograman : Java

<b>2.2 Deskripsi Data</b>

Deskripsi tabel-tabel yang terdapat pada database pembuatan aplikasi PAHAT adalah sebagai berikut :

<b>Tabel User</b>

| Nama Field | Jenis | Volume | Laju | Primary Key | Constraint Integrity | Deskripsi |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | 
| id_user | integer | 11 | Primary key | Iya | auto_increment | id_user auto increment |
| email | varchar | 20 | Tidak | Tidak | - | email yang digunakan user untuk login |
| password | varchar | 20 | Tidak | Tidak | password yang digunakan user untuk login |

2.2.1 Definisi Domain/Type

2.2.2 Conceptual Data Model

2.2.3 Physical Data Model

2.2.4 Daftat Tabel Aplikasi

2.3 Deskripsi Modul


<b><h4>BAB 3.DESKRIPSI PERANCANGAN RINCI</b></h4>

<b>3.1 Diagram Konteks</b>

![](http://i64.tinypic.com/28md8bm.png)

3.1.1 DFD Level 0

![](http://i67.tinypic.com/r0bnsm.png)

3.1.1.1 DFD Level 1 Proses 1 ( Mengolah data user )

![](http://i66.tinypic.com/2us917k.jpg)

3.1.1.2 DFD Level 1 Proses 2 ( Mengolah data olahraga )

![](http://i68.tinypic.com/zo2hg.jpg)

3.1.1.3 DFD Level 1 Proses 3 ( Mengolah data BMR )

![](http://i68.tinypic.com/10dtahx.jpg)

3.1.1.4 DFD Level 1 Proses 4 ( Mengolah menu food )

![](http://i64.tinypic.com/2d6taon.jpg)

3.1.1.5 DFD Level 1 Proses 5 ( Mengolah menu drink )

![](http://i68.tinypic.com/2cngtis.jpg)

3.1.1.6 DFD Level 1 Proses 6 ( Mengolah data kalori )

![](http://i63.tinypic.com/n2d0lw.jpg)

3.1.1.7 DFD Level 1 Proses 7 ( Mengolah data report kalori )



<b>3.2 Deskripsi Rinci Tabel</b>

     Identifikasi/Nama : Login
     
     Deskripsi Isi     : Data Login
     
     Jenis             : Tabel data Induk
     
     Volume            : 10 Record
     
     Laju              : 10 Record/bulan
     
     Primary Key       : Id User

3.2.1 Tabel A

<b>3.3 Deskripsi Rinci Modul</b>

3.3.1 Modul A

3.3.1.1 Fungsi Modul

3.3.1.2 Spesifikasi Layar Utama

3.3.1.3 Spesifikasi Query

(jika ada)

3.3.1.4 Spesifikasi Field Data Layar

3.3.1.5 Spesifikasi Obyek Pada Layer

3.3.1.6 Spesifikasi Proses / Algoritma

3.3.2 Modul B

3.4 Matriks Keturunan
