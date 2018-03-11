
##<center>**Software Requirements Specification**

###Versi 1.1

###26 Februari 2018
 
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

I. Pendahuluan

1.1. Tujuan

Dokumen ini berisi Spesifikasi Kebutuhan Perangkat Lunak (SKPL) atau Software Requirement Spesification (SRS) untuk Aplikasi Pola Hidup
Sehat ( Pahat ) .Tujuan dari penulisan dokumen ini adalah untuk memberikan penjelasan mengenai perangkat lunak yang akan 
dibangun baik berupa gambaran umum maupun penjelasan detail dan menyeluruh.

Pengguna dari dokumen ini adalah pengembang perangkat lunak aplikasi Pola Hidup Sehat pengguna (user) dari perangkat lunak atau 
personil-personil yang terlibat dalam sistem.Dokumen ini akan digunakan sebagai bahan acuan dalam proses pengembangan dan sebagai bahan 
evaluasi pada saat proses pengembangan perangkat lunak maupun di akhir pengembangannya. Dengan adanya dokumen SRS ini diharapkan 
pengembangan perangkat lunak akan lebih terarah dan lebih terfokus serta tidak menimbulkan ambiguitas terutama bagi pengembang 
perangkat lunak aplikasi Pola Hidup Sehat.

1.2. Lingkup

Perangkat lunak yang akan dikembangkan adalah perangkat lunak aplikasi Pola Hidup Sehat, yaitu merupakan perangkat lunak yang digunakan 
untuk mempermudah pengguna (user) mengetahui aktivitas seperti jalan sehat, jogging, maupun bersepeda dengan GPS yang dimana fungsinya 
adalah memberikan statistik kepada kita tentang kecepatan, jarak, waktu berolahraga kita, serta perhitungan BMR ( Basal Metabolic Rate ).
Aplikasi ini dapat melakukan hal-hal berikut ini :

1.2.1 Fasilitas Login untuk pengguna ( user )

1.2.2 Melakukan perhitungan BMR ( Basal Metabolic Rate )

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

II. Gambaran umum

Tuliskan produk secara umum dan hindari penulisan pernyataan yang berulang dan
ambigu (harus jelas subjek predikat dan objeknya)

2.1. Perspektif produk

Perangkat lunak yang dibuat (disebut dengan PAHAT) merupakan sebuah perangkat lunak yang digunakan untuk membantu melakukan proses pola 
hidup sehat dengan memantau aktifitas olahraga serta memantau asupan yang dikonsumsi.

Prosesnya dimana user bisa memilih olahraga yang diinginnkan lalu dapat melihat jalur olahraganya serta memberikan informasi berapa 
jarak yang sudah ditempuh dan berapa kalori yang sudah terbakar.Selanjutnya dimana si user bisa memantau asupannya dengan kita melakukan
perhitungan BMR.

2.1.1. Antarmuka sistem

![](http://i66.tinypic.com/125kuxj.png)

2.1.2. Antarmuka pengguna

Aplikasi ini dikembangkan dalam bentuk aplikasi android. Perangkat lunak ini dilengkapi dengan menu untuk pengaksesan berbagai
fungsi yang disediakan. Interaksi antara pengguna dan perangkat lunak dilakukan dengan menggunakan smartphone.


![](http://i66.tinypic.com/25jjl7k.jpg)![](http://i66.tinypic.com/w05pvd.jpg) ![](http://i66.tinypic.com/xx15x.jpg) ![](http://i65.tinypic.com/vxey5v.jpg) ![](http://i66.tinypic.com/2agncp0.jpg) ![](http://i63.tinypic.com/2cfa79i.jpg) ![](http://i67.tinypic.com/23mr5t1.jpg) ![](http://i64.tinypic.com/vzwppx.jpg) ![](http://i64.tinypic.com/2vabasi.jpg) ![](http://i64.tinypic.com/9qydch.jpg) ![](http://i63.tinypic.com/qyx3f6.jpg) ![](http://i66.tinypic.com/2567bwg.jpg) ![](http://i63.tinypic.com/rw81md.jpg) ![](http://i67.tinypic.com/iqc4eu.jpg) ![](http://i63.tinypic.com/2v8smcw.jpg) ![](http://i65.tinypic.com/wbcr9v.jpg) ![](http://i67.tinypic.com/2cnbi39.jpg) ![](http://i63.tinypic.com/2ynqm3a.jpg) ![](http://i68.tinypic.com/2mh8r9x.jpg) ![](http://i68.tinypic.com/2rpcvp5.jpg)

2.1.3. Antarmuka perangkat keras
Kebutuhan minimum perangkat keras yang dapat digunakan adalah:

1. Seperangkat komputer

2. Smartphone 

Semua perangkat keras yang digunakan merupakan perangkat standar dalam sistem komputer dan
menggunakan port standar yang ada. 

2.1.4. Antarmuka perangkat lunak

Perangkat lunak yang diperlukan oleh aplikasi ini adalah:

1. Sistem Operasi Windows.

2. Playstore

2.1.5. Antarmuka komunikasi

2.1.6. Batasan memori

Kalau belum diketahui, boleh diskip dulu

2.1.7. Operasi-operasi

Jelaskan setiap operasi pada produk perangkat lunak.

2.1.8. Kebutuhan adaptasi

Ada yang diadaptasi? kalau tidak ada, skip saja.

2.2. Spesifikasi Kebutuhan fungsional

Gambarkan use case yang berdasarkan pada kebutuhan fungsional produk perangkat
lunak (disesuaikan dengan operasi 2.1.7). Lihat contoh bagian “functional requirements
specifications”

2.3. Spesifikasi kebtuhan non-fungsinoal

lihat contoh bagian “non-functional requirements”

2.4. Karakteristik pengguna

Lihat contoh bagian “user characteristic”

2.5. Batasan-batasan

Jelaskan sendiri batasan produk kalian apa saja

2.6. Asumsi-asumsi keterkaitan

nomor registrasi maksimal sampai 999

2.7. Kebutuhan penyeimbang
Skip

3.0 Deskripsi Rinci Kebutuhan

3.1 Kebutuhan antarmuka eksternal

Kebutuhan antarmuka eksternal pada perangkat lunak Aplikasi Hidup Sehat mencakup kebutuhan antarmuka pemakai, antarmuka perangkat keras, dan antarmuka perangkat lunak.

3.1.1 Antarmuka Pemakai

Antarmuka pemakai akan dikembangkan dengan menggunakan modus grafik. Pengguna berinteraksi dengan perangkat lunak Aplikasi hidup Sehat melalui antarmuka android. Aplikasi ini memberikan user interface dan akan memberikan petunjuk penggunaan agar memudahkan user dalam penggunaan perangkat lunak ini

3.1.2 Antarmuka Perangkat keras

Kebutuhan perangkat keras yang dapat digunakan oleh aplikasi ini adalah: PC (Personal Computer), Papan Kunci (Keyboard), Mouse, Modem/internet/WiFi, Monitor dll

3.1.3 Antarmuka perangkat lunak

Komunikasi interface yang kamu gunakan adalah client:

	Client = Masyarakat umum

Perangkat lunak yang digunakan diantaranya yaitu :Android Studio, Firebase, dan CorelDraw X7

3.1.4 Antarmuka Komunikasi

	User = Masyarakat umum

3.2 Kebutuhan Fungsional

Kebutuhan Fungsional adalah kebutuhan yang harus dipenuhi agar suatu sistem dapat berjalan atau dapat dikatakan kebutuhan tambahan yang memiliki input, proses, dan output. Kebutuhan fungsional yang harus ada dalam sistem yang akan dikembangkan ini adalah sebagai berikut:

1.	Sistem harus dapat menyediakan informasi mengenai pola hidup sehat secara lebih detail, cepat dan efektif.
2.	Sistem harus dapat mempermudah user dalam proses kegiatan olahraga. 

Aktor yang ada dalam dalam lingkup sistem adalah

a.	User

Yang dilakukan adalah : Login, Melakukan kegiatan kegiatan pola hidup sehat (berjalan, berlari, bersepeda dll), dan Memilih menu-menu yang tersedia

3.2.1 Pencarian Artikel

3.2.2 Komunikasi

3.2.3 Tambahan Penulis

3.2.4 Tambahan Resensi

3.2.5 Ubah orang

3.2.6 Ubah status artikel

3.2.7 Masukan Komunikasi

3.2.8 Tentukan Resensi

3.2.9 Mengecek Status

3.2.10 Kirim Komunikasi

3.2.11 Menerbitkan Artikel

3.2.12 Menghapus Artikel

3.3 Persyaratan Non-fungsional yang Rinci

3.3.1 Structur Logis dari Data

![](http://i68.tinypic.com/25au81d.png)

3.3.2 Keamanan

Untuk memproteksi perangkat lunak dari akses, penggunaan, penghancuran atau pengungkapan (disclosure) yang tidak sengaja atau yang merusak. Kebutuhan yang spesifik termasuk hal-hal berikut :

1.	Adanya backup data sehingga data lebih reliable
2.	Penyimpanan data log/history
3.	Pemberian suatu fungsi ke modul-modul yang berbeda
4.	Pembatasan komunikasi terhadap suatu area tertentu dalam program,
5.	Pemeriksaan integritas data peubah-peubah kritis

3.3.3 Pemeliharaan

Adanya pemeliharaan dan pengecekan berkala yang akan dilakukan terhadap program yang berjalan ataupun pengecekan baik terhadap perangkat lunak itu sendiri ataupun hardware yang digunakan. Untuk pemeliharaan tiap harinya, system ini dilengkapi antivirus sehingga meminimalkan kerusakan pada system serta terdapat back up data untuk mencegah hal-hal yang tidak terduga yang tidak diinginkan
