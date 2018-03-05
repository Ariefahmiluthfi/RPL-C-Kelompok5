Software Requirements Specification

Version 1.0

26 Maret 2018

![](http://i64.tinypic.com/t00pzl.png)


Nama Perangkat Lunak

Nama Kelompok :
1. Arie Fahmi Luthfi
2. Diky Anwar
3. Shafa Dhiyanti
4. Stephan Dwiki Alkine

Jurusan D3 Teknik Informatika
Politeknik Negeri Indramayu

I. Pendahuluan

1.1. Tujuan

Dokumen ini berisi Spesifikasi Kebutuhan Perangkat Lunak (SKPL) atau Software Requirement Spesification (SRS) untuk Aplikasi Pola Hidup
Sehat ( Pola Hidup Sehat ) .Tujuan dari penulisan dokumen ini adalah untuk memberikan penjelasan mengenai perangkat lunak yang akan 
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

![](http://i67.tinypic.com/jrywzs.png)

2.1.2. Antarmuka pengguna

Aplikasi ini dikembangkan dalam bentuk aplikasi android. Perangkat lunak ini dilengkapi dengan menu untuk pengaksesan berbagai
fungsi yang disediakan. Interaksi antara pengguna dan perangkat lunak dilakukan dengan menggunakan smartphone.


![](http://i66.tinypic.com/25jjl7k.jpg)![](http://i66.tinypic.com/w05pvd.jpg) ![](http://i66.tinypic.com/xx15x.jpg) ![](http://i65.tinypic.com/vxey5v.jpg) ![](http://i66.tinypic.com/2agncp0.jpg) ![](http://i63.tinypic.com/2cfa79i.jpg) ![](http://i67.tinypic.com/23mr5t1.jpg) ![](http://i64.tinypic.com/vzwppx.jpg)

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

III. Requirement specification

Berikut adalah kebutuhan perangkat lunak untuk perancang sistem aplikasi Jalan Sehat, diantaranya yaitu sebagai berikut :

3.1 Kebutuhan Antarmuka Eksternal

Akan disediakan penjelasan rinci dari semua masukan (input) dan luaran (output) dari aplikasi Jalan Sehat

3.1.1 Daftar Masukan

Daftar berbeda dari setiap modulnya, yang diberikan sebagai berikut.

3.1.1.1 Module Login

Disini User / pengguna diwajibkan untuk menginputkan email dan sandi dan apabila user/pengguna salah dalam memasukan email dan kata sandi maka pengguna tidak dapat menggunakan aplikasinya

3.1.1.2 Module Menu

Disini User / Pengguna setelah berhasil login yaitu memilih menu, user boleh memilih menu yang tersedia didalam aplikasi ini

3.1.2 Daftar Keluaran

3.1.2.1 Laporan Hasil

Disini user mendapatkan segala informasi ketika selesai melakukan kegiatan olahraga, informasi-informasi tersebut berupa, berupa seberapa jauh kita berolahraga, informasi kebutuhan kalori yang dibutuhkan dll

3.1.2.2 Laporan Penyimpanan

Disini Data hasil dari kegiatan selama olahraga akan disimpan dalam firebase dan dengan otomatis datanya tersimpan

3.2 Kebutuhan Atribut Kualitas Perangkat Lunak

Ada sejumlah atribut kualitas perangkat lunak yang dapat ditampilkan sebagai kebutuhan. Atribut yang diinginkan harus dispesifikasikan sedemikian sehingga hasilnya dapat diverifikasi. Uraian minimum pada bagian ini berisi sebuah tabel dengan kolom: Kriteria Kualitas, Tuntutan Kualitas. Butir kualitas yang dapat dipertimbangkan antara lain: keandalan (reliability), ketersediaan (availability), keamanan (security), keremawatan (maintainability), kepemindahan (portability). Bila diperlukan uraian khusus, dapat dilakukan dengan menguraikannya menjadi sub-bab tersendiri.

3.2.1	Kehandalan

Bagian ini berisi spesifikasi factor-faktor yang diperlukan untuk mencapai keandalan sistem pada saat diserahkan.

3.2.2	Ketersediaan.

Bagian ini berisi spesifikasi factor-faktor yang diperlukan untuk menjamin tingkat ketersediaan seluruh sistem saat sistem beroperasi, seperti checkpoint, recovery dan restart.

3.2.3	Keamanan

Bagian ini berisi faktor untuk memproteksi perangkat lunak dari akses, penggunaan, pengubahan, penghancuran atau pengungkapan (disclosure) yang tidak disengaja atau yang merusak. Kebutuhan yang spesifik termasuk hal-hal berikut:

Penggunaan teknik kriptografi
Penyimpanan data log/history
Pemberian suatu fungsi ke modul-modul yang berbeda
Pembatasan komunikasi terhadap suatu area tertentu dalam program
Pemeriksaan integritas data untuk peubah-peubah kritis
3.2.4	Keremawatan (Maintainability)

Bagian ini menentukan atribut perangkat lunak yang berhubungan dengan kemudahan perawatan dari perangkat lunak tersebut. Atribut tersebut dapat berupa kebutuhan akan tingkat modularitas, antarmuka, kompleksitas, dan lain-lain. Penulisan atribut keremawatan tidak dilakukan hanya atas dasar pemikiran atas praktik perancangan yang baik saja, tetapi harus didasari pada tuntutan kondisi sistem. 3.2.5	Kepemindahan (Portability)

Atribut dari perangkat lunak yang berhubungan dengan kemudahan pemindahan perangkat lunak ke mesin dan/atau sistem operasi lain. Atribut ini berbentuk antara lain:

Persentase komponen yang berisi kode yang bergantung pada host
Persentase kode yang bergantung pada host
Penggunaan bahasa yang kepemindahannya terbukti
Penggunaan suatu kompilator tertentu atau subset bahasa tertentu
Penggunan suatu sistem operasi tertentu
3.3	Batasan Perancangan

Bagian ini menspesifikasikan batasan atas keputusan-keputusan perancangan yang dituntut oleh standar lain, keterbatasan perangkat keras, dan lain-lain. Standar atau aturan yang ada dapat menurunkan spesifikasi kebutuhan khusus antara lain:

Format laporan
Penamaan data
Kebutuhan penelusuran audit
Sebagai contoh, bagian ini dapat menentukan kebutuhan perangkat lunak untuk menelusuri aktivitas pemrosesan. Penelusuran ini diperlukan agar suatu aplikasi sesuai dengan peraturan. Kebutuhan penelusuran audit, sebagai contoh, menyatakan bahwa semua perubahan harus dicatat pada suatu file khusus untuk penelusuran dengan isi sebelum dan sesudah dilakukan. Contoh lain adalah menyatakan lingkungan implementasi (seperti sistem operasi, DBMS, kakas pengembangan, bahasa pemrograman, kompilator) bila memang merupakan tuntutan yang ditentukan oleh pelanggan

3.4	Matriks Keterunutan

Bagian ini berisi daftar seluruh kebutuhan beserta identifikasinya serta cara verifikasi yang direncanakan, yaitu: Inspeksi, Analisis, Demonstrasi. Inspeksi dilakukan dengan mengamati produk yang dihasilkan (biasanya kode program) yang dibandingkan dengan standar atau spesifikasi yang ada. Analisis dilakukan dengan menerapkan pengukuran matematis/kuantitatif terhadap hasil yang didapat dari penerapan produk. Demonstrasi dilakukan dengan mengamati perilaku produk akhir, yaitu melihat kesesuaian antara masukan dan keluaran.

3.5	Informasi tambahan

Dukungan informasi yang digunakan, antara lain:

Daftar isi
Index
Lampiran
3.5.1	Daftar isi dan Index

Daftar isi dan index adalah cukup penting dan harus mengikuti standard yang ada.

3.5.2	Lampiran-lampiran Lampiran tidak selalu menjadi bagian dari spesifikasi kebutuhan aktual dan tidak harus selalu ada. Lampiran dapat berisi:

Contoh format masukan/keluaran, deskripsi analisa biaya, hasil survey
Deskripsi dari masalah yang dipecahkan oleh perangkat lunak.
Instruksi khusus, dan media yang cocok untuk pengamatan, dan kebutuhan lain.
Flow Map atau prosedur manual yang merupakan lingkungan tempat perangkat lunak yang dispesifikasikan akan dijalankan.
Lampiran lain yang dianggap perlu dan berhubungan dengan spesifikasi perangkat lunak
