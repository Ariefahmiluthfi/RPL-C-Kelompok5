<html>
<body>
<div align="center"><h1> Software Testing Document</h1></div>

<p align="center"><b>Version 1.0 </b><br>
<p align="center">7 Mei 2018</b>
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

<b><h4>1. Pendahuluan</b></h4>

<b>1.1 Tujuan Pembuatan Dokumen</b>

Dokumen ini digunakan sebagai panduan untuk melakukan pengujian terhadap perangkat lunak Aplikasi Pola Hidup Sehat (PAHAT) . Dokumen ini dipakai untuk melihat kemampuan dari program yang telah dirancang agar sesuai dengan keinginan dari pengguna. Pembuatan dokumen ini ditujukan untuk menguji perangkat lunak Aplikasi Pola Hidup Sehat (PAHAT) yang merupakan bagian dari tugas mata kuliah Proyek 2.

<b>1.2 Deskripsi Umum Sistem</b>

Perangkat lunak yang akan diuji adalah "Aplikasi Pola Hidup Sehat (PAHAT)". Perangkat lunak ini adalah perangkat lunak yang digunakan untuk mempermudah pengguna (user) mengetahui aktivitas seperti jalan sehat, jogging, maupun bersepeda dengan GPS yang dimana fungsinya adalah memberikan statistik kepada kita tentang kecepatan, jarak, dan waktu berolahraga kita, perhitungan BMR (Basal Metabolic Rate), serta perhitungan kalori.

<b>1.3 Deskripsi Dokumen (Ikhtisar)</b>

Dalam dokumen ini berisi 3 bagian utama yaitu Pendahuluan, Identifikasi
dan Rencana Pengujian, Deskripsi dan Uji Hasil.

<b>1.4 Definisi dan Singkatan</b>

| Singkatan | Definisi 
| ----- | ----- |
| PAHAT | Pola Hidup Sehat |
| SKPL | Spesifikasi Kebutuhan Perangkat Lunak, atau dalam bahasa inggris-nya sering juga disebut sebagai Software Requirements Spesification (SRS), dan merupakan spesifikasi dari perangkat lunak yang akan dikembangkan |
| SKPL-SK.K-xxxx | kode yang digunakan untuk merepresentasikan kebutuhan (requirement) pada SK, dengan SK merupakan kode perangkat lunak, SK.K adalah kode fase, dan xxxx adalah digit/nomor kebutuhan (requirement) |
| DFD | Data Flow Diagram, diagram dan notasi yang digunakan untuk menunjukkan aliran data pada perangkat lunak |
| ERD | Entity Relationship Diagram, diagram dan notasi yang digunakan untuk merepresentasikan struktur data statis pada perangkat lunak |
| DPPL-Akkses.K-xxxx | kode yang digunakan untuk mengimplementasikan perancangan pada Akkses, dengan Akkses merupakan kode perangkat lunak, Akkses.K adalah kode fase, dan xxxx adalahdigit/nomor perancangan |


<b>1.5 Dokumen Referensi</b>

- Ernita H. GL03. Dokumen Uji Perangkat Lunak (DUPL) SDS. Bogor.
- Sistem Pentiketan Elektronik Konser.2013. Spesifikasi Kebutuhan Perangkat Lunak (SKPL)SPEK. Bogor.
- Sistem Pentiketan Elektronik Konser.2013. Dokumen Perancangan Perangkat Lunak (DPPL)SPEK. Bogor.

<b><h4>2. Lingkungan Pengujian Perangkat Lunak</b></h4>

<b>2.1 Perangkat Lunak Pengujian</b>

Perangkat lunak ini diujikan dengan beberapa perangkat lain, yaitu :

- Sistem Operasi : Windows 10
- Bahasa pemrograman : Java dan PHP
- Database : MySQL

<b>2.2 Perangkat Keras Pengujian</b>

Perangkat keras yang diperlukan untuk menguji aplikasi PAHAT ini adalah satu set komputer dengan spesifikasi :

- Processor : Intel(R) Core(TM) i3-2367MCPU @ 1.40GHz
- Memory : 4096MB RAM


Dan smartphone dengan spesifikasi :

- RAM : 2GB
- Android : Lollipop 5.0.2

<b>2.3 Material Pengujian</b>

Pada program "Aplikasi Pola Hidup Sehat" ini, user dapat melakukan register tanpa melalui admin. Admin sendiri dapat mengelola user tersebut. User dapat melakukan olahraga dengan menggunakan maps dan melihat kalori terbakar, melakukan perhitungan BMR dan melakukan perhitungan konsumsi kalori.

<b>2.4 Sumber Daya Manusia</b>

Persyaratan sumber daya manusia yang akan terlibat dalam proses pengujian perangkat lunak ini adalah :

- Memahami konsep pemrograman berorientasi objek dalam bahasa Java
- Memahami proses pengujiam perangkat lunak berorientasi objek
- Memahami konsep pemrograman database MySQL

<b>2.5 Prosedur Umum Pengujian</b>

<b>2.5.1 Pengenalan dan Latihan</b>

Penguji aplikasi ini hanya diberikan latihan kembali tentang SQL, dan
pengenalan lebih lanjut tentang Android Studio dan Java. Pada dasarnya penguji telah memiliki pengetahuan tentang hal yang disebutkan sebelumnya tetapi latihan yang diberikan hanya bersifat penyegaran kembali.

<b>2.5.2 Persiapan Awal</b>

<b>2.5.2.1 Persiapan Prosedural</b>

Pengujian ini dilakukan di luar lingkungan kampus. Dimana pengujian ini dilakukan oleh tim penguji yang telah di tentukan oleh Dosen mata kuliah Rekayasa Perangkat Lunak (RPL). Alat yang digunakan 1 buah laptop dengan software yang telah di instalasi dan 1 buah smartphone yang telah diinstal aplikasi PAHAT.

<b>2.5.2.2 Persiapan Perangkat Keras</b>

Perangkat keras yang perlu dipesiapkan adalah :
Sebuah perangkat komputer yang dilengkapi dengan :

- Processor : Intel(R) Core(TM) i3-2367MCPU @ 1.40GHz
- Memory : 4096 MB RAM


Sebuah handphone dengan spesifikasi :

- RAM : 2GB
- Android : Lollipop 5.0.2

<b>2.5.2.3 Persiapan Perangkat Lunak</b>

Persiapan yang harus dilakukan untuk menyiapkan perangkat lunak untuk diuji di lingkungan sistem operasi Microsoft Windows 10 adalah sebagai berikut :

1. Persiapkan sistem operasi Microsoft Windows.
2. Instal aplikasi PAHAT pada smartphone
3. Perangkat lunak yang akan di uji di copy ke sebuah direktori,
misalnya C:\XAMPP\htdocs.
4. Browser Google Chrome.
5. Database di import ke phpMyAdmin di database MySQL.
6. Sublime Text untuk melihat source code.

<b>2.5.3 Pelaksanaan </b>

Pelaksanaan pengujian dilakukan dengan mengeksekusi perangkat lunak aplikasi PAHAT dengan mengikuti skenario tertentu yang dibuat berdasarkan
skenario yang tedapat pada dokumen SKPL-SPEK.

<b>2.5.4 Pelaporan Hasil </b>

Dokumen hasil uji dari aplikasi ini akan diberikan kepada asisten
praktikum dan dievaluasi oleh asisten dan kelompok lain yang bertindak
sebagai klien dari kelompok kami. Sehingga aplikasi mendapatkan umpan
balik dalam pengembangan perangkat lunak ini selanjutnya.

<b><h4>3. Identifikasi dan Rencana Pengujian</b></h4>

<table>  
	<thead>  
<tr>
	<td rowspan="2" align="center"><strong>Kelas Uji</td>
	<td rowspan="2" align="center"><strong>Butir Uji </td>
	<td colspan="2" align="center"><strong>Identifikasi</td>
	<td rowspan="2" align="center"><strong>Tingkat Pengujian</td>
	<td rowspan="2" align="center"><strong>Jenis Pengujian</td>
	<td rowspan="2" align="center"><strong>Penguji</td>
</tr>
		<tr>
			<td align="center"><strong>SKPL-DPPL</td>
			<td align="center"><strong>DUPL</td>
		</tr>
<tr>
	<td rowspan="3" align="center"><strong>Register User</td>
	<td>Data email dan password benar</td>
	<td>SKPL-SPEK.K-0001</td>
	<td>DUPL-01</td>
	<td>Pengujian Sistem</td>
	<td>Black Box</td>
	<td>Arie</td>
<tr>
	<td>Data email tidak ada lambang "@"</td>
	<td></td>
	<td>DUPL-02</td>
	<td>Pengujian Sistem</td>
	<td>Black Box</td>
	<td>Arie</td>
<tr>
	<td>Password tidak 8 digit</td>
	<td></td>
	<td>DUPL-03</td>
	<td>Pengujian Sistem</td>
	<td>Black Box</td>
	<td>Arie</td>
</tr>		

</thead>  
</table>

<b><h4>4. Deskripsi dan Hasil Uji</b></h4>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">DUPL-01</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Data email dan password benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Memeriks a apakah data baru masuk ke database</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Tabel user sudah ada di database</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">16/05/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Arie</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1. Ketikkan data yang akan ditambahkan</li>
					<li>2. Klik tombol Register</li>
				</ul>
</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Username:Arie Fahmi</li>
					<li>Email: ariefahmi300897@gmail.com</li>
					<li>Password: 123</li>
					<li>No HP: 083100145917</li>
					<li>Alamat: Indramayu</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					Data user yang diisikan saat register masuk ke database
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Belum bisa register sebagai user jika data belum semua terisi</li>
					<li>Tombol Register menyimpan semua data user agar bisa masuk ke database</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					
				</ul>
			</td>
		</tr>
	</thead>
</table>




