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
| password | varchar | 20 | Tidak | Tidak | - | password yang digunakan user untuk login |

<b> Tabel Olahraga </b>

| Nama Field | Jenis | Volume | Laju | Primary Key | Constraint Integrity | Deskripsi |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| id_or | integer | 11 | Primary Key | Iya | auto_increment | id or auto increment |
| nama_or | varchar | 20 | Tidak | Tidak | - | Nama olahraga |
| jarak_or | integer | 11 | Tidak | Tidak | - | jarak yang ditempuh user saat berolahraga |
| kal_burn | varchar | 20 | Tidak | Tidak | - | kalori yang terbakar user setelah berolahraga |

<b> Tabel BMR </b>

| Nama Field | Jenis | Volume | Laju | Primary Key | Constraint Integrity | Deskripsi |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| id_bmr | integer | 11 | Primary Key | Iya | auto_increment | id bmr auto increment |
| umur | integer | 11 | Tidak | Tidak | - | umur user |
| tinggi_bdn | integer | 11 | Tidak | Tidak | - | tinggi badan user |
| berat_bdn | integer | 11 | Tidak | Tidak | - | berat badan user |
| kal_ideal | integer | 11 | Tidak | Tidak | - | hasil perhitungan BMR |

<b> Tabel Menu_food </b>

| Nama Field | Jenis | Volume | Laju | Primary Key | Constraint Integrity | Deskripsi |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| id_food | integer | 11 | Primary Key | Iya | auto_increment | id food auto increment |
| nama_food | varchar | 20 | Tidak | Tidak | - | nama makanan |
| kal_food | integer | 11 | Tidak | Tidak | - | kandungan kalori pada makanan |

<b> Tabel Menu_drink </b>

| Nama Field | Jenis | Volume | Laju | Primary Key | Constraint Integrity | Deskripsi |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| id_drink | integer | 11 | Primary Key | Iya | auto_increment | id drink auto increment |
| nama_drink | varchar | 20 | Tidak | Tidak | - | nama makanan |
| kal_drink | integer | 11 | Tidak | Tidak | - | kandungan kalori pada minuman |

<b> Tabel Kalori </b>

| Nama Field | Jenis | Volume | Laju | Primary Key | Constraint Integrity | Deskripsi |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| id_kalori | integer | 11 | Primary Key | Iya | auto_increment | id kalori auto increment |
| id_food | integer | 11 | Tidak | Foreign Key | - | makanan yang dipilih |
| id_drink | integer | 11 | Tidak | Foreign Key | - | minuman yang dipilih |
| kal_consum | integer | 11 | Tidak | Tidak | - | hasil perhitungan jumlah kalori pada makanan dan minuman yang dikonsumsi |

<b> Tabel Report Kalori </b>

| Nama Field | Jenis | Volume | Laju | Primary Key | Constraint Integrity | Deskripsi |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| id_report | integer | 11 | Primary Key | Iya | auto increment | id report auto increment |
| id_user | integer | 11 | Tidak | Foreign Key | - | info user |
| kal_burn | integer | 11 | Tidak | Tidak | - | kalori yang terbakar pada user setelah berolahraga |
| kal_ideal | integer | 11 | Tidak | Tidak | - | kalori ideal user yang didapatkan dari perhitungan BMR |
| kal_consum | integer | 11 | Tidak | Tidak | - | jumlah kalori pada makanan / minuman yang dikonsumsi |



<b>2.2.1 Definisi Domain/Type</b>

<b>Data User</b>

| Domain Name | Power Designer Type |
| ----- | ----- |
| id_user | primary key |
| email | string |
| password | string |

<b>Data Olahraga</b>

| Domain Name | Power Designer Type |
| ----- | ----- |
| id_or | primary key |
| nama_or | string |
| jarak_or | number |
| kal_burn | number | 

<b>Data BMR</b>

| Domain Name | Power Designer Type |
| ----- | ----- |
| id_bmr | primary key |
| umur | number |
| tinggi_bdn | number |
| berat_bdn | number |
| kal_ideal | number |

<b>Data Menu_food</b>

| Domain Name | Power Designer Type |
| ----- | ----- |
| id_food | primary key |
| nama_food | string |
| kal_food | number |

<b>Data Menu_drink</b>

| Domain Name | Power Designer Type |
| ----- | ----- |
| id_drink | primary key |
| nama_drink | string |
| kal_drink | number |

<b>Data Kalori</b>

| Domain Name | Power Designer Type |
| ----- | ----- |
| id_kalori | primary key |
| id_food | foreign key |
| id_drink | foreign key |
| kal_consum | number |

<b>Data Report Kalori</b>

| Domain Name | Power Designer Type |
| ----- | ----- |
| id_report | primary key |
| id_user | foreign key |
| kal_burn | number |
| kal_ideal | number |
| kal_consum | number |


<b>2.2.2 Conceptual Data Model</b>

<b>2.2.3 Physical Data Model</b>

<b>2.2.4 Daftar Tabel Aplikasi</b>

| Nama Tabel | Primary Key | Data Store | E/R | Deskripsi isi |
| ----- | ----- | ----- | -----| ----- |
| User | id_user | D1 | - | Berisi email dan password user yang digunakan untuk login |
| Olahraga | id_or | D2 | - | Berisi nama olahraga, jarak olahraga dan kalori terbakar |
| BMR | id_bmr | D3 | - | Berisi data umur, tinggi badan, berat badan dan kalori ideal |
| Menu_food | id_food | D4 | - | Berisi data nama food dan kandungan kalorinya |
| Menu_drink | id_drink | D5 | - | Berisi data nama drink dan kandungan kalorinya |
| Kalori | id_kalori | D6 | - | Berisi makanan, minuman yang dipilih dan kalori konsumsi |
| Report_kalori | id_report | D7 | - | Berisi data user, info kalori terakar, ideal dan kalori konsumsi user |


<b>2.3 Deskripsi Modul</b>

| Nama Modul | Keterangan |
| ----- | ----- |
| Otentikasi | Modul yang digunakan untuk memberika  validasi akses user |
| Tracking | Modul yang digunakan untuk mengelola data jarak yang ditempuh user saat berolahraga dengan menggunakan maps |
| Kalori Burn | Modul yang digunakan untuk mengelola data kalori terbakar user setelah berolahraga |
| BMR | Modul yang digunakan untuk melakukan perhitungan BMR agar mengetahui kalori ideal user |
| Kalori Konsumsi | Modul yang digunakan untuk mengelola makanan dan minuman apa saja yang sudah dikonsumsi user lalu dihitung keseluruhan kalori yang dikonsumsi |
| Report Kalori | Modul yang digunakan untuk membuat laporan data kalori user |
| Riwayat Tracking | Modul yang digunakan untuk mengetahui riwayat tracking user |
| Riwayat Kalori Burn | Modul yang digunakan untuk mengetahui riwayat kalori terbakar user |
| Riwayat BMR | Modul yang digunakan untuk mengetahui riwayat kalori ideal user melalui perhitungan BMR sebelumnya |
| Riwayat Kalori Konsumsi | Modul yang digunakan untuk mengetahui riwayat konsumsi kalori user |

<b><h4>BAB 3.DESKRIPSI PERANCANGAN RINCI</b></h4>

<b>3.1 Diagram Konteks</b>

![](http://i64.tinypic.com/28md8bm.png)

<b>3.1.1 DFD Level 0</b>

![](http://i67.tinypic.com/r0bnsm.png)

<b>3.1.1.1 DFD Level 1 Proses 1 ( Mengolah data user ) </b>

![](http://i66.tinypic.com/2us917k.jpg)

<b>3.1.1.2 DFD Level 1 Proses 2 ( Mengolah data olahraga )</b>

![](http://i68.tinypic.com/zo2hg.jpg)

<b>3.1.1.3 DFD Level 1 Proses 3 ( Mengolah data BMR )</b>

![](http://i68.tinypic.com/10dtahx.jpg)

<b>3.1.1.4 DFD Level 1 Proses 4 ( Mengolah menu food )</b>

![](http://i64.tinypic.com/2d6taon.jpg)

<b>3.1.1.5 DFD Level 1 Proses 5 ( Mengolah menu drink )</b>

![](http://i68.tinypic.com/2cngtis.jpg)

<b>3.1.1.6 DFD Level 1 Proses 6 ( Mengolah data kalori )</b>

![](http://i63.tinypic.com/n2d0lw.jpg)

<b>3.1.1.7 DFD Level 1 Proses 7 ( Mengolah data report kalori )</b>



<b>3.2 Deskripsi Rinci Tabel</b>

<b>3.2.1 Tabel User </b>

- Identifikasi / Nama : User
- Deskripsi Isi : Berisi semua user dalam aplikasi
- Jenis : Tabel Referensi
- Volume : -
- Laju : -
- Primary key : id_user

| Id Field | Deskripsi | Tipe & Length | Boleh NULL | Default | Keterangan |
| ----- | ----- | ----- | ----- | ----- | ----- |
| id_user | merupakan key dari tabel user | int | No | - | Primary key yang unik dari setiap user, bersifat auto increment |
| email | menyatakan email user | varchar(20) | No | - | Email akan digunakan sebagai username untuk login user |
| password | menyatakan password user | varchar(20) | No | - | password akan digunakan untuk login user, password harus sesuai dengan email agar login berhasil |

<b>3.2.2 Tabel Olahraga </b>

- Identifikasi / Nama : Olahraga
- Deskripsi Isi : Berisi nama olahraga, jarak olahraga dan kalori terbakar
- Jenis : Tabel Referensi
- Volume : -
- Laju : -
- Primary key : id_or

| Id Field | Deskripsi | Tipe & Length | Boleh NULL | Default | Keterangan |
| ----- | ----- | ----- | ----- | ----- | ----- |
| id_or | merupakan key dari tabel olahraga | int | No | - | Primary key yang unik dari jenis olahraga, bersifat auto increment |
| nama_or | menyatakan nama olahraga | varchar(20) | No | - | nama olahraga |
| jarak_or | menyatakan jarak olahraga | varchar | No | -| jarak yang ditempuh user setelah olahraga, dapat diketahui menggunakan maps |
| kal_burn | menyatakan kalori terbakar | varchar(20) | No | - | menyatakan jumlah kalori terbakar setelah user berolahraga |

<b>3.2.3 Tabel BMR </b>

- Identifikasi / Nama : BMR
- Deskripsi Isi : Berisi data user yaitu umur, tinggi badan dan berat badan, kalori ideal
- Jenis : Tabel Referensi
- Volume : -
- Laju : -
- Primary key : id_bmr

| Id Field | Deskripsi | Tipe & Length | Boleh NULL | Default | Keterangan |
| ----- | ----- | ----- | ----- | ----- | ----- |
| id_bmr | merupakan key dari tabel bmr | int | No | - | Primary key yang unik dari setiap perhitungan BMR, bersifat auto increment |
| umur | menyatakan umur user | int | No | - | data umur user untuk melakukan perhitungan BMR |
| tinggi_bdn | menyatakan tinggi badan user | varchar(20) | No | - | data tinggi badan user untuk melakukan perhitungan bmr |
| berat_bdn | menyatakan berat badan user | varchar(20) | No | - | data tinggi badan user untuk melakukan perhitungan bmr |
| kal_ideal | menyatakan kalori ideal user | varchar(20) | No | - | menyatakan kalori ideal user yang didapatkan dari perhitungan bmr | 

<b>3.2.4 Tabel Menu_food </b>

- Identifikasi / Nama : Menu_food
- Deskripsi Isi : Berisi daftar makanan dan kandungan kalorinya
- Jenis : Tabel Referensi
- Volume : -
- Laju : -
- Primary key : id_food

| Id Field | Deskripsi | Tipe & Length | Boleh NULL | Default | Keterangan |
| ----- | ----- | ----- | ----- | ----- | ----- |
| id_food | merupakan key dari tabel menu_food | int | No | - | Primary key yang unik dari setiap food, bersifat auto increment |
| nama_food | menyatakan nama makanan | varchar(20) | No | - | menyatakan nama makanan untuk perhitungan konsumsi kalori |
| kal_food | menyatakan kalori yang terkandung pada makanan | varchar(20) | No | - |  menyatakan kandungan kalori pada makanan untuk perhitungan konsumsi kalori |

<b>3.2.5 Tabel Menu_drink </b>

- Identifikasi / Nama : Menu_drink
- Deskripsi Isi : Berisi daftar minuman dan kandungan kalorinya
- Jenis : Tabel Referensi
- Volume : -
- Laju : -
- Primary key : id_drink

| Id Field | Deskripsi | Tipe & Length | Boleh NULL | Default | Keterangan |
| ----- | ----- | ----- | ----- | ----- | ----- |
| id_drink | merupakan key dari tabel menu_drink | int | No | - | Primary key yang unik dari setiap drink, bersifat auto increment |
| nama_drink | menyatakan nama minuman | varchar(20) | No | - | menyatakan nama minuman untuk perhitungan konsumsi kalori |
| kal_drink | menyatakan kalori yang terkandung pada minuman | varchar(20) | No | - |  menyatakan kandungan kalori pada minuman untuk perhitungan konsumsi kalori |
 


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
