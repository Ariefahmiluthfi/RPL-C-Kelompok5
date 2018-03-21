
##<center>**Software Design Description**

###Versi 1.0

###4 Maret 2018
 
 ![](http://i68.tinypic.com/24fbuvd.png)


##Aplikasi Pola Hidup Sehat ( Pahat )

Nama Kelompok :

1. Arie Fahmi Luthfi
2. Diky Anwar
3. Shafa Dhiyanti
4. Stephan Dwiki Alkine

Jurusan D3 Teknik Informatika
<br>Politeknik Negeri Indramayu
<br>2018
</center>

##BAB 1 Pendahuluan

1.1 Tujuan

Tujuan pembuatan SDD (Software Design Description) ini adalah untuk menjelaskan langkah-langkah desain dan proses-proses dalam pembuatan sistem aplikasi yang akan diterapkan pada Aplikasi Pola Hidup Sehat berbasis Android, dan juga memberi definisi kebutuhan untuk sistem, spesifikasi kebutuhan fungsional.

Dokumen perancangan ini dibuat berdasarkan spesifikasi kebutuhan Aplikasi Pola Hidup Sehat berbasis Android yang akan dibuat. Dalam rangka membangun aplikasi tersebut, tentunya deskripsi perancangan untuk aplikasi tersebut dibutuhkan, khususnya oleh para pengembang dan pembangun aplikasi tersebut.

Aplikasi Pola Hidup Sehat ini memudahkan kita untuk mengetahui aktivitas seperti jalan maupun jogging dengan GIS (Geographic Informatic System) yang dimana fungsinya memberikan statistik kepada kita tentang kecepatan, jarak dan waktu berolahraga kita. Selain itu aplikasi ini juga bisa melakukan perhitungan BMR           ( Basal Metabolic Rate ) agar kita menerapkan pola hidup yang sehat.

1.2 Lingkup

Aplikasi Pola Hidup Sehat (Pahat) adalah sebuah aplikasi berbasis android yang mempermudah masyarakat menerapkan pola hidup sehat. Penggunaan aplikasi ini dengan Login melalui email, memilih olahraga, melakukan perhitungan BMR, melihat daftar kandungan kalori pada makanan dan minuman, menghitung konsumsi kalori, dan melihat hasil kalori dari tubuh kita. Aplikasi ini hanya menggunakan 1 user.

1.3 Definisi, Akronim dan Singkatan

| Definisi, Akronim dan Singkatan | Penjelasan |
| ----- | ----- |
| DFD | Data Flow Diagram. Diagram yan menggambarkan aliran data |
| ERD | Entity Relationship Diagram. Diagram yang menggambarkan entitas suatu objek beserta relasinya |
| SKPL | Spesifikasi Kebutuhan Perangkat Lunak. Sebuah dokumen yang berisi analisis terhadap suatu perangkat lunak yang akan dibangun yang dijabarkan dalam suatu spesifikasi kebutuhan. |
| SDD | Software Design Description. Dokumen untuk menjelaskan langkah-langkah desain dan proses-proses dalam pembuatan sistem aplikasi yang akan diterapkan pada aplikasi. |
| User | Pengguna aplikasi |

1.4 Referensi

Dokumen ini memiliki beberapa referensi dalam pembuatannya, yaitu sebagai berikut:


- IEEE Draft Standard for Software Design Descriptions

1.5 Ikhtisar Dokumen

Dokumen SDD ini berisi deskripsi rancangan perangkat lunak yang akan dikembangkan berdasarkan dokumen SRS. Dalam dokumen SDD ini dijabarkan perincian rancangan perangkat lunak yang dikembangkan, sehingga dapat diimplementasikan hingga level teknis. Gambaran umum dokumen ini terdapat pada penjelasan dibawah ini .

a. Bab 1, merupakan bab pendahuluan yang berisikan tentang overview dari rencana pengembangan perangkat lunak secara umum, seperti tujuan penulisan dokumen, lingkup masalah, definisi dan istilah, referensi.

b. Bab 2, merupakan deskripsi perancangan global yang berisi tentang perancangan perangkat lunak secara umum seperti lingkungan operasi yang akan digunakan untuk implementasi perangkat lunak, pemodelan data-data yang akan digunakan dalam perangkat lunak, dan daftar tabel yang digunakan sebagai database dalam perangkat lunak yang dikembangkan.

c. Bab 3, merupakan deskripsi perancangan rinci yang berisi tentang rincian keseluruhan atau detail menyeluruh dari perangkat lunak yang akan dikembangkan, seperti pendeskripsian secara rinci database yang akan digunakan didalam perangkat lunak dan rincian pemrosesan yang terjadi didalam perangkat lunak yang dikembangkan.

##BAB 2 Deskripsi Perancangan Global

2.1 Rancangan Lingkungan Implementasi

Aplikasi Pola Hidup Sehat akan dikembangkan menjadi perangkat lunak berbasis android yang membutuhkan komputer dengan spesifikasi sebagai berikut :

- Sistem Operasi	: Microsoft Windows 2010

- DBMS				: 

- Development Tools	: Draw IO

- Word Processor	: Microsoft Office Word 2010

- Bahasa pemrograman : Java

2.2 Definisi Domain

2.2.2 Conceptual Data Model

2.2.3 Physical Data Model

2.2.4 Daftar Tabel Aplikasi

2.3 Deskripsi Modul


##BAB 3 Deskripsi Perancangan Rinci

3.1 Diagram Konteks

![](http://i64.tinypic.com/5eguie.png)

3.1.1 DFD Level 0
![](http://i63.tinypic.com/2who2z8.png)

3.1.1.1 DFD Level 1
![](http://i67.tinypic.com/nvw3tu.png)

3.2 Deskripsi Rinci Tabel

3.2.1 Tabel A

3.3 Deskripsi Rinci Modul

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
