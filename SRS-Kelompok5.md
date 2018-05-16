<html>
<body>
<div align="center"><h1> Software Requirements Specification</h1></div>

<p align="center"><b>Version 1.5 </b><br>
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

Sistem perangkat lunak yang akan dikembangkan adalah perangkat lunak aplikasi Pola Hidup Sehat. Sistem ini dirancang untuk mempermudah pengguna (user) mengetahui aktivitas seperti jalan sehat, jogging, maupun bersepeda dengan GPS yang dimana fungsinya 
adalah memberikan statistik kepada kita tentang kecepatan, jarak, dan waktu berolahraga kita, perhitungan BMR (Basal Metabolic Rate), serta perhitungan kalori.

<b>1.3. Definisi, Akronim dan Singkatan</b>


| Definisi, Akronim dan Singkatan |	Penjelasan |
| -------- | ----------- |
| IEEE |	Institute of Electrical and Electronics Engineer. |
| BMR | adalah kebutuhan energi minimal yang dibutuhkan tubuh untuk menjalankan proses tubuh yang vital |
| SPMP dan SRS | adalah dokumen yang menggambarkan secara detail spesifikasi kebutuhan software dalam pembangunan proyek perangkat lunak Aplikasi Pahat Berbasis Android. |

<b>1.4. Referensi </b>

- IEEE Std. 830-1998, IEEE Recommended Practice for Software Requirement Specifications.

<b>1.5. Overview</b>

- Bagian pertama berisi penjelasan tentang dokumen SPL yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan oleh
perangkat lunak yang dikembangkan, definisi, referensi dan deskripsi umum.

- Bagian kedua berisi penjelasan secara umum mengenai perangkat lunak Pola Hidup Sehat yang akan dikembangkan, meliputi fungsi dari 
perangkat lunak, karakteristik pengguna, batasan dan asumsi yang diambil dalam pengembangan perangkat lunak.

- Bagian ketiga berisi uraian kebutuhan perangkat lunak secara lebih detail.

<b><h4>BAB 2.GAMBARAN UMUM</h4></b>

<b>2.1. Perspektif Produk</b>

Perangkat lunak yang dibuat (disebut dengan PAHAT) merupakan sebuah perangkat lunak yang digunakan untuk membantu melakukan proses pola 
hidup sehat dengan memantau aktifitas olahraga serta memantau asupan yang dikonsumsi.Prosesnya dimana user bisa memilih olahraga yang diinginkan lalu dapat melihat jalur olahraganya serta memberikan informasi berupa berapa 
jarak yang sudah ditempuh dan berapa kalori yang sudah terbakar.Selanjutnya user bisa melakukan perhitungan BMR dan mengetahui berapa kalori yang telah dikonsumsi.

<b>2.1.1. Antarmuka Sistem</b>

![](http://i68.tinypic.com/2zfsk7s.jpg)

Aplikasi Pahat ini memiliki 1 user yaitu si pengguna aplikasi itu sendiri. User dapat melihat jalur tracking, mengetahui jumlah kalori terbakar setelah melakukan olahraga, mengetahui kalori ideal dari perhitungan BMR dan mengetahui kalori yang dikonsumsi setelah menginputkan makanan atau minuman apa saja yang telah dikonsumsi.

<b>2.1.2. Antarmuka Pengguna</b>

<table>
<tr>
	<td><p align="center">Splashscreen</td>
	<td><p align="center"><img src="http://i64.tinypic.com/315bt6e.png"></p> </td>
	<td><p align="center">Tampilan saat user membuka aplikasi</td>
</tr>
<tr>
	<td><p align="center">Form Login</td>
	<td><p align="center"><img src="http://i65.tinypic.com/s6twuq.png"></p> </td>
	<td><p align="center">Tampilan form login. User login dengan memasukkan username dan password </td>
</tr>
<tr>
	<td><p align="center">Menu Olahraga</td>
	<td><p align="center"><img src="http://i68.tinypic.com/2e2gjmq.png"></p> </td>
	<td><p align="center">Tampilan menu. User dapat memilih olahraga Lari, Bersepeda maupun Jalan</td>
</tr>
<tr>
	<td><p align="center">Lari</td>
	<td><p align="center"><img src="http://i66.tinypic.com/fpcd4z.png"></p> </td>
	<td><p align="center">Tampilan saat user memilih olahraga Lari. Terdapat track, jarak yang ditempuh dan kalori terbakar</td>
</tr>
<tr>
	<td><p align="center">Bersepeda</td>
	<td><p align="center"><img src="http://i63.tinypic.com/2d9cxzo.png"></p> </td>
	<td><p align="center">Tampilan saat user memilih olahraga Bersepeda. Terdapat track, jarak yang ditempuh dan kalori terbakar</td>
</tr>
<tr>
	<td><p align="center">Jalan</td>
	<td><p align="center"><img src="http://i68.tinypic.com/27y77k1.png"></p> </td>
	<td><p align="center">Tampilan saat user memilih olahraga Jalan. Terdapat track, jarak yang ditempuh dan kalori terbakar</td>
</tr>
<tr>
	<td><p align="center">Jalan</td>
	<td><p align="center"><img src="http://i68.tinypic.com/27y77k1.png"></p> </td>
	<td><p align="center">Tampilan saat user memilih olahraga Jalan. Terdapat track, jarak yang ditempuh dan kalori terbakar</td>
</tr>
<tr>
	<td><p align="center">Menu</td>
	<td><p align="center"><img src="http://i66.tinypic.com/2dl4zrp.png"></p> </td>
	<td><p align="center">Tampilan menu</td>
</tr>
<tr>
	<td><p align="center">Menu Perhitungan BMR</td>
	<td><p align="center"><img src="http://i68.tinypic.com/33k4o7m.png"></p> </td>
	<td><p align="center">Tampilan menu</td>
</tr>
<tr>
	<td><p align="center">Menu Daftar Makanan dan Minuman</td>
	<td><p align="center"><img src="http://i65.tinypic.com/2v2y2y8.png"></p> </td>
	<td><p align="center">Tampilan ini menampilkan daftar makanan dan minuman</td>
</tr>
<tr>
	<td><p align="center">Menu Perhitungan Kalori Konsumsi</td>
	<td><p align="center"><img src="http://i68.tinypic.com/2d6s2a8.png"></p> </td>
	<td><p align="center">Tampilan ini menampilkan pilihan makanan dan minuman apa saja yang dikonsumsi, lalu akan dihitung jumlah kalorinya</td>
</tr>
<tr>
	<td><p align="center">Menu Data Kalori</td>
	<td><p align="center"><img src="http://i63.tinypic.com/b8mdea.png"></p> </td>
	<td><p align="center">Tampilan ini menampilkan report dari kalori yang terbakar, kalori ideal hasil perhitungan BMR dan jumlah kalori dari makanan / minuman yang sudah dikonsumsi</td>
</tr>
</table>

<b>2.1.3. Antarmuka Perangkat Keras</b>

Kebutuhan minimum perangkat keras yang dapat digunakan adalah:

- Seperangkat komputer

- Smartphone 

![](http://i67.tinypic.com/b8jx2g.jpg)

<b>2.1.4. Antarmuka Perangkat Lunak</b>

Perangkat lunak yang diperlukan oleh aplikasi ini adalah:

- Android Studio

- Firebase

- Balsamiq Mockup

<b>2.1.5. Antarmuka Komunikasi</b>

Aplikasi ini membutuhkan koneksi internet untuk menjalankannya. 

<b>2.1.6. Batasan memori</b>

<b>2.1.7. Operasi-operasi</b>

| Operasi | Fungsi |
| ----- | ----- |
| Login | Digunakan untuk masuk akses ke aplikasi |
| Pilih Olahraga | Digunakan untuk memilih olahraga apa yang ingin dilakukan |
| Perhitungan BMR | Digunakan untuk menghitung BMR agar mengetahui kalori ideal |
| Pilih makanan | Digunakan untuk memilih makanan yang dikonsumsi |
| Pilih minuman | Digunakan untuk memilih minuman yang dikonsumsi |
|  Perhitungan kalori konsumsi | Digunakan untuk menghitung berapa kalori kita setelah mengkonsumsi makanan atau minuman |

<b>2.1.8. Kebutuhan Adaptasi</b>


<b>2.2. Spesifikasi Kebutuhan Fungsional</b>

![](http://i66.tinypic.com/11jn1vt.jpg)

![](http://i68.tinypic.com/204gpi.jpg)

<b>2.2.1 Login User </b>

![](http://i67.tinypic.com/20r8bkh.jpg)

Untuk dapat menggunakan aplikasi, user harus login terlebih dahulu dengan cara :

1. User mengaktifkan fungsi login 
2. Sistem menampilkan halaman login yang terdiri dari email dan password 
3. User mengisi email dan password 
4. Sistem melakukan validasi dari email dan password 
5. Jika login gagal maka member akan diminta mengulangi proses login 
6. Jika login berhasil maka member akan diarahkan ke menu aplikasi

<b>2.2.2 User Pilih Olahraga </b>

![](http://i64.tinypic.com/2j5gos9.jpg)

User dapat memilih olahraga dengan cara:

1. User pilih menu olahraga
2. Sistem memberikan 3 pilihan olahraga
3. User memilih olahraga
4. Sistem menampilkan track untuk olahraga
5. Setelah user olahraga, sistem akan menampilkan jarak yang ditempuh dan kalori yang terbakar

<b>2.2.3 Perhitungan BMR User</b>

![](http://i66.tinypic.com/117xp2c.jpg)

User dapat mengetahui kalori ideal dari perhitungan BMR, dengan cara:

1. User pilih menu Hitung BMR
2. Sistem memberikan kolom Usia,Berat Badan dan Tinggi Badan
3. User mengisi kolom yang disediakan
4. Sistem akan melakukan perhitungan BMR untuk mengetahui kalori ideal user
5. Sistem menampilkan kalori ideal user

<b>2.2.4 Kalori Konsumsi User </b>

![](http://i64.tinypic.com/kdlkp4.jpg)

User dapat mengetahui kalori konsumsi dengan cara :

1. User memilih menu Daftar Makanan dan Minuman
2. Sistem memberikan daftar makanan dan minuman serta jumlah kalori yang terkandung didalamnya
3. User memilih makanan atau minuman yang telah ia konsumsi
4. Sistem menghitung keseluruhan jumlah kalori yang telah user konsumsi
5. Sistem menampilkan kalori konsumsi user

<b>2.2.5 Login Admin </b>

![](http://i63.tinypic.com/vpb58o.jpg)

Untuk dapat menggunakan web, admin harus login terlebih dahulu dengan cara :

1. Admin mengaktifkan fungsi login 
2. Sistem menampilkan halaman login yang terdiri dari username dan password 
3. Admin mengisi username dan password 
4. Sistem melakukan validasi dari username dan password 
5. Jika login gagal maka admin akan diminta mengulangi proses login 
6. Jika login berhasil maka admin akan diarahkan ke menu web


<b>2.2.5 Admin Kelola User </b>

![](http://i67.tinypic.com/yzc05.jpg)

Admin dapat mengelola user dengan cara :

1. Sistem memberikan kolom data user
2. Admin dapat mengedit, menghapus dan menambah user
3. Jika admin berhasil mengedit, menghapus dan menambah user maka sistem akan menampilkan data terbarunya


<b>2.3. Spesifikasi Kebutuhan Non-fungsinoal</b>

- Availability
 
Ketersediaan aplikasi yang dapat di-update sewaktu-waktu dan dapat beroperasi terus menerus selama 24 jam per hari tanpa berhenti, karena aplikasi ini akan bersifat android-based dan akan diakses oleh pengguna yang membutuhkan dari berbagai tempat pada waktu yang berbeda-beda.

- Security 

Aplikasi yang dikembangkan nantinya harus memiliki tingkat keamanan yang tinggi dimana setiap user yang masuk tidak dapat seenaknya mengubah data yang berada di dalam aplikasi ini. 

- Usability
 
Aplikasi ini diharapkan memudahkan user dalam penggunaannya.

- Accessibility
 
Aplikasi bisa digunakan kapanpun dan dimanapun selama terkoneksi internet.

- Portability
 
Aplikasi ini memberi kemudahan dalam pengaksesan sistem khususnya terkait dengan faktor waktu dan lokasi pengaksesan, serta perangkat atau teknologi yang digunakan untuk mengakses.

<b>2.4. Karakteristik Pengguna</b>

- Pengguna diharapkan dapat memiliki koneksi internet untuk menjalankan aplikasi.

- Pengguna diharapkan dapat memahami menu yang diberikan aplikasi serta dapat menggunakan tombol, pulldown menu dan lain-lain. 

<b>2.5. Batasan-batasan</b>

- Aplikasi Pahat ini belum bisa membagikan kegiatan kita ke media sosial.


<b>2.6. Asumsi-asumsi Keterkaitan</b>


<b>2.7. Kebutuhan Penyeimbang</b>


<b><h4>BAB 3.DESKRIPSI RINCI KEBUTUHAN</h4></b>

<b>3.1 Kebutuhan antarmuka eksternal</b>

Kebutuhan antarmuka eksternal pada perangkat lunak Aplikasi Hidup Sehat mencakup kebutuhan antarmuka pemakai, antarmuka perangkat keras, dan antarmuka perangkat lunak.


<b>3.2 Kebutuhan Fungsional</b>

<b>3.2.1 Login User </b>

| Nama Fungsi | Login User |
| ----- | ----- |
| Ref | Bag 2.1.2, Login User |
| Trigger | Membuka aplikasi PAHAT |
| Precondition | Halaman utama Login pada aplikasi |
| Basic Path | 1. Sistem menampilkan halaman Login yang terdiri dari email dan password |
| | 2. User memasukkan email dan password |
| | 3. Sistem memvalidasi email dan password |
| Alternative | Tidak ada |
| Post Condition | User dapat login dan dapat mengakses aplikasi PAHAT |
| Exception Push | Tidak ada koneksi |

<b>3.2.2 Navbar Menu User </b>

| Nama Fungsi | Navbar Menu User |
| ----- | ----- |
| Ref | Bag 2.1.2, Navbar Menu User |
| Trigger | Mengklik tombol navbar menu |
| Precondition | Halaman utama aplikasi |
| Basic Path | 1. User mengklik tombol navbar menu |
| | 2. Sistem menampilkan halaman utama aplikasi  dan daftar menu yang terdiri dari menu olahraga, hitung BMR, Daftar makanan dan minuman, Data Kalori|
| Alternative | Tidak ada |
| Post Condition | User dapat mengakses menu dari aplikasi PAHAT |
| Exception Push | Tidak ada koneksi |

<b>3.2.3 Olahraga </b>

| Nama Fungsi | Olahraga |
| ----- | ----- |
| Ref | Bag 2.1.2, Menu Olahraga |
| Trigger | Mengklik tombol Olahraga pada navbar menu |
| Precondition | Halaman utama menu Olahraga |
| Basic Path | 1. User mengklik tombol Olahraga pada navbar menu |
| | 2. Sistem menampilkan 3 pilihan olahraga |
| | 3. User memilih olahraga |
| | 4. Sistem menampilkan track olahraga yang dipilih |
| | 5. Setelah user berolahraga, sistem menampilkan jarak yang sudah ditempuh dan kalori yang terbakar |
| Alternative | Tidak ada |
| Post Condition | User dapat mengetahui track, jarak dan kalori yang terbakar |
| Exception Push | Tidak ada koneksi |

<b>3.2.4 BMR </b>

| Nama Fungsi | BMR |
| ----- | ----- |
| Ref | Bag 2.1.2, Menu BMR |
| Trigger | Mengklik tombol Perhitungan BMR pada navbar menu |
| Precondition | Halaman utama menu Perhitungan BMR |
| Basic Path | 1. User mengklik tombol Perhitungan BMR pada navbar menu |
| | 2. Sistem menampilkan 3 kolom yakni kolom usia, berat badan dan tinggi badan |
| | 3. User mengisi 3 kolom tersebut sebagai data untuk melakukan perhiutngan BMR |
| | 4. Sistem melakukan perhitungan BMR |
| | 5. User mengetahui kalori ideal melalui perhitungan BMR |
| Alternative | Tidak ada |
| Post Condition | User dapat mengetahui kalori ideal |
| Exception Push | Tidak ada koneksi |

<b>3.2.5 Daftar Makanan dan Minuman serta Hitung Konsumsi Kalori </b>

| Nama Fungsi | Daftar Makanan dan Minuman  |
| ----- | ----- |
| Ref | Bag 2.1.2, Menu Daftar Makanan dan Minuman  |
| Trigger | Mengklik tombol Daftar Makanan dan Minuman  pada navbar menu |
| Precondition | Halaman utama menu Daftar Makanan dan Minuman  |
| Basic Path | 1. User mengklik tombol Daftar Makanan dan Minuman  pada navbar menu |
| | 2. Sistem menampilkan daftar makanan dan minuman serta kandungan kalorinya |
| | 3. User mengklik tombol hitung kalori |
| | 4. Sistem menampilkan kolom makanan dan minuman |
| | 5. User mengisi kolom tersebut dengan makanan atau minuman apa saja yang sudah dikonsumsi |
| | 6. Sistem menghitung kalori yang dikonsumsi |
| | 7. Sistem menampilkan konsumsi kalori |
| Alternative | Tidak ada |
| Post Condition | User dapat mengetahui kalori yang dikonsumsinya |
| Exception Push | Tidak ada koneksi |

<b>3.2.6 Report Kalori </b>

| Nama Fungsi | Data Kalori Anda  |
| ----- | ----- |
| Ref | Bag 2.1.2, Menu Data Kalori Anda  |
| Trigger | Mengklik tombol Data Kalori Anda pada navbar menu |
| Precondition | Halaman utama menu Data Kalori Anda  |
| Basic Path | 1. User mengklik tombol Data Kalori Anda pada navbar menu |
| | 2. Sistem menampilkan kalori terbakar, kalori ideal dan banyaknya kalori pada makanan/minuman yang dikonsumsi |
| Alternative | Tidak ada |
| Post Condition | User dapat mengetahui kalori terbakar, kalori ideal dan kalori yang dikonsumsinya |
| Exception Push | Tidak ada koneksi |


<b>3.3 Persyaratan Non-fungsional yang Rinci</b>

3.3.1 Structur Logis dari Data

![](http://i63.tinypic.com/2nuhaav.jpg)

Deskripsi :

<b> Tabel User </b>

| Data Item | Type | Deskripsi |
| ----- | ----- | ----- |
| id_user | integer | id user auto increment |
| email | varchar | email yang digunakan user untuk login |
| password | varchar | password yang digunakan user untuk login |

<b> Tabel Olahraga </b>

| Data Item | Type | Deskripsi |
| ----- | ----- | ----- |
| id_or | integer | id or auto increment |
| nama_or | varchar | nama olahraga |
| jarak_or | varchar | jarak yang ditempuh user saat berolahraga |
| kal_burn | varchar | kalori yang terbakar user setelah berolahraga |

<b> Tabel BMR </b>

| Data Item | Type | Deskripsi |
| ----- | ----- | ----- |
| id_bmr | integer | id_bmr auto increment |
| umur | integer | umur user |
| tinggi_bdn | varchar | tinggi badan user |
| berat_bdn | varchar | berat badan user |
| kal_ideal | varchar | hasil perhitunga BMR |

<b> Tabel Menu_food </b>

| Data Item | Type | Deskripsi |
| ----- | ----- | ----- |
| id_food | integer | id food auto increment |
| nama_food | varchar | nama makanan |
| kal_food | varchar | kandungan kalori pada makanan |

<b> Tabel Menu_drink </b>

| Data Item | Type | Deskripsi |
| ----- | ----- | ----- |
| id_drink | integer | id drink auto increment |
| nama_drink | varchar | nama minuman |
| kal_drink | varchar | kandungan kalori pada minuman |

<b> Tabel Kalori </b>

| Data Item | Type | Deskripsi |
| ----- | ----- | ----- |
| id_kalori | integer | id kalori auto increment |
| id_food | integer | makanan yang dipilih |
| id_drink | integer | minuman yang dipilih |
| kal_consum | varchar | hasil perhitungan jumlah kalori pada makanan dan minuman yang dikonsumsi |

<b> Tabel Report Kalori </b>

| Data Item | Type | Deskripsi |
| ----- | ----- | ----- |
| id_report | integer | id report auto increment |
| id_user | integer | info user |
| kal_burn | varchar | kalori yang terbakar pada user setelah berolahraga|
| kal_ideal | varchar | kalori ideal user yang didapatkan dari perhitungan BMR |
| kal_consum | varchar | jumlah kalori pada makanan / minuman yang dikonsumsi |



<b><h4>BAB 4.INFORMASI PENDUKUNG</h4></b>
